# Maestro Mobile Tests

Automated mobile test suite built with [Maestro](https://maestro.mobile.dev/) for a court booking app.

## What's Tested

**Checkout & Payment Flow**
- Navigate to court booking and add to cart
- Validate checkout screen elements
- Select credit/debit card as payment method
- Back navigation validation
- Checkout data and cost summary validation
- Card details entry and validation
- Change card flow
- OTP entry and payment confirmation
- Receipt screen validation

## Tech Stack

- [Maestro](https://maestro.mobile.dev/)
- YAML

## Run Tests
```bash
maestro test checkout-payment.yaml
```