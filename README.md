# Amplify Fusion Shopify Demo

An Amplify Fusion Shopify Demo that responds to an order completion webhook from Shopify and does the following:

* Creates a CSV file of the oder and uploads to AWS S3
* Checks if the order total exceeds a threshold and if so, generates a Shopify coupon code and emails it to the customer for future purchases

A demo video can be viewed [here](https://youtu.be/T_a0OQ4b_rg).

To use:
* Import the project export zip file into your Fusion tenant
* Configure the AWS connector with your AWS credentials
* Configure the Email connector with your SMTP server credentials
* Configure the GraphQL connector with your Shopify app credentials (e.g. API Key)
* Enable integration and copy URL and paste it into your Shopify Order Completion webhook

A How-To video can be viewed [here](https://youtu.be/iA4tQUEKHX0).