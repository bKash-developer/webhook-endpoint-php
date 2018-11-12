# webhook-endpoint-php
1. To get completed transaction notification through bKash-Webhook, a merchant needs to be subscribed first to the bKash-Webhook.
2. A merchant who wants to use bKash-Webhook needs to develop en endpoint first where bKash-Webhook will send a SubscriptionConfirmationRequest.
3. Merchant must confirm the bKash-Webhook subscription through the endpoint.
4. Merchant endpoint also receives transaction notification after successful SubscriptionConfirmation.
5. Merchant endpoint must be implemented in such a way that it should be able to receive SubscriptionConfirmation and Notification message and process them accordingly.
