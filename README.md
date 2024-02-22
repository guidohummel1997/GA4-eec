If you have any doubts please message me on Slack. 

Additional resources that can be useful: 
1. https://developers.google.com/analytics/devguides/collection/ga4/reference/events?sjid=11470055494011769802-EU&client_type=gtag#begin_checkout
2. https://developers.google.com/analytics/devguides/collection/ga4/reference/events?sjid=11470055494011769802-EU&client_type=gtag#add_shipping_info
3. https://developers.google.com/analytics/devguides/collection/ga4/reference/events?sjid=11470055494011769802-EU&client_type=gtag#add_payment_info

Please note that these links include a gtag call, and NOT a dataLayer push, which is what we want. 

The correct orders of the events are: 
1. "begin_checkout"
2. "add_shipping_info"
3. "add_payment_info"
