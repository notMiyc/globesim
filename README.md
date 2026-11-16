# GlobeSIM prototype

This is a free, front-end demonstration website/PWA starter.

## Run it
- Open `index.html` in a browser to test the interactive prototype.
- For installable PWA behavior, host the folder on an HTTPS static host. Then open the hosted site on a supported phone and use the browser's Add to Home Screen / Install option.
- The catalog, prices, and checkout are sample data only. Demo orders are held in browser memory and disappear when the page reloads.

## To become a real eSIM service
1. Have a parent/guardian or other responsible adult help review provider contracts, business requirements, privacy obligations, taxes, and payment processing.
2. Apply for a reseller/partner account with an eSIM wholesale provider.
3. Request sandbox credentials and API documentation.
4. Build a secure backend (never put provider API keys in browser JavaScript).
5. Connect the provider's destination/catalog endpoint to the plan list.
6. After a verified payment, create an order on the backend, receive the real eSIM profile/QR data, and deliver it securely.
7. Add order-status webhooks, usage/top-up support where available, customer support, refund handling, and privacy/security controls.
8. Test end-to-end in the provider sandbox before any live launch.

No real payments, eSIM profiles, QR codes, mobile data, or carrier service are included.
