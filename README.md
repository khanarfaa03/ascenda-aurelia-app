# Ascenda Aurelia App

**Rise To Gold. Health is Wealth. Wealth is Health.**

A mobile-first consultancy app for **Ascenda Aurelia**, offering two services:

- 🥗 **Nutrition & Diet Consultancy** with Dr. Uzma Shaheen (Nutritionist & Dietician)
- 💰 **Personal Budgeting & Financial Consultancy** with Ms. Arfaa Khan (Financial Analyst & Advisor)

**Live demo:** https://claude.ai/artifact/YJJoLKkDc632aAp8K9BvmB

## Features

- Login and sign up
- Service information and expert profiles
- First chat free (5 messages), then Rs. 100 (nutrition) or Rs. 150 (finance)
- **Aurelia Gold**: Rs. 500 for a free consultation in both services for 30 days
- UPI QR payment with transaction ID (UTR) entry
- Burgundy and gold branding with the Ascenda Aurelia logo

## Tech

A single self-contained `index.html` (HTML, CSS and JavaScript). No build step. Data is saved in the browser's localStorage.

## Run it

Open `index.html` in any browser, or host it free on GitHub Pages or Netlify.

## Customise

Edit the top of the `<script>` section in `index.html`:

- `CUR`, `GOLD`, `FREE_MSGS` for currency, Gold price and free messages
- `EX` for expert names, prices and service text
- `UPI` for the UPI ID

## Limitations

- Payments are not verified automatically. Check each UTR in your bank statement.
- Accounts and chats are stored on the device only.
- Expert replies are automatic placeholders. Live chat and payment verification need a backend.

## Roadmap

- Flutter version for Google Play (APK/AAB)
- Backend with real login, live chat and a payment gateway (Razorpay)

## License

© Ascenda Aurelia. All rights reserved.
