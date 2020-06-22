# API-Documentation
API Documentation

# 1. Create Order API

# Create Order API is used to create a gift card order & return the redemption code.
# The following are key elements for generating an Order.
# - Product Info
  - name : name of product from our catalog
  - code : product code from our catalog
# - Payment Info: This will have 
  - Amount 
  - method : GooglePay / ApplePay 
  - Stripe Token for fulfilling Payments made using Apple/Google Pay
  - StoreCredit amount, incase a StoreCash account credit is used to place order.
# - Sender Info
  - Sender name
  - sender Id
# - Receiver Info
  - Receiver name
  - Receiver email
      and/or
  - Phone 
# - Billing address
  - city
  - state
  - street
  - country (iso)
  - unit
  - zipcode

Create Order data will be secured at rest & in transit. Details will be shared with partners as part of integrations.

2.
3.
