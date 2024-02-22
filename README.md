Additional resources that can be useful: 
1. https://developers.google.com/analytics/devguides/collection/ga4/reference/events?sjid=11470055494011769802-EU&client_type=gtag#begin_checkout
2. https://developers.google.com/analytics/devguides/collection/ga4/reference/events?sjid=11470055494011769802-EU&client_type=gtag#add_shipping_info
3. https://developers.google.com/analytics/devguides/collection/ga4/reference/events?sjid=11470055494011769802-EU&client_type=gtag#add_payment_info

Please note that these links include a gtag call, and NOT a dataLayer push. We want a dataLayer push which is why I've included that in each snippets. 

The correct orders of the events are: 
1. "begin_checkout"
2. "add_shipping_info"
3. "add_payment_info"

- These are the detailed instructions about the "begin_checkout" event: 
- These are the detailed instructions about the "add_shipping_info" event:
- These are the detailed instructions about the "add_payment_info" event:
  
If you have any doubts please message me on Slack. 
