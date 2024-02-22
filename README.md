Additional resources that can be useful: 
1. https://developers.google.com/analytics/devguides/collection/ga4/reference/events?sjid=11470055494011769802-EU&client_type=gtag#begin_checkout
2. https://developers.google.com/analytics/devguides/collection/ga4/reference/events?sjid=11470055494011769802-EU&client_type=gtag#add_shipping_info
3. https://developers.google.com/analytics/devguides/collection/ga4/reference/events?sjid=11470055494011769802-EU&client_type=gtag#add_payment_info

Please note that these links include a gtag call, and NOT a dataLayer push. We want a dataLayer push which is why I've included that in each snippets. 

The correct orders of the events are: 
1. "**begin_checkout**"
2. "**add_shipping_info**"
3. "**add_payment_info**"
---------------------------------------------------
1. These are the detailed instructions about the "**begin_checkout**" event:
   - "push" the code once the user, when seeing the cart, clicks the violet button "Check out".
   - If a user then goes back to the cart page, do not "push" it again (to prevent double tracking). 
  
2. These are the detailed instructions about the "**add_shipping_info**" event:
   - "push" the code once the user, when checking out, after inserting its billing info, clicks the violet button "Continue to payment".
   - If a user then goes back to the cart page, do not "push" it again (to prevent double tracking). 

3. These are the detailed instructions about the "**add_payment_info**" event:
   - "push" the code once the user, when checking out, after inserting its payment details, clicks the violet button "Pay now".
   - Do not "push" the code when a user reaches the thank you page. 
   - If a user then goes back to the cart page, do not "push" it again (to prevent double tracking).
  
   
If you have any doubts please message me on Slack. 
