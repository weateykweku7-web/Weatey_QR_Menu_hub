WEATEY QR MENU — STARTER APP

FEATURES
- Responsive dashboard, menu management, categories and availability toggles.
- Add/edit/delete menu items, descriptions, prices and optional photo URLs.
- Customer menu preview with category filters, basket and demo checkout.
- Order status changes, CSV exports, local analytics and promotion text generator.
- QR code generator with custom color/size and PNG download.
- WhatsApp sharing for promotions and optional order hand-off.
- Business settings, suggested subscription plans and income ideas.

RUN IT
1. Extract the ZIP in Acode or your file manager.
2. Open index.html in a browser or upload the files to a static host such as Netlify.
3. Internet is required for QRCode.js CDN and Google Fonts.
4. Set up business details, manage menu items, then generate a QR code using your deployed public URL.
5. Test with a second phone before printing QR codes.

IMPORTANT
This is a front-end prototype. Menu, settings and orders are stored in localStorage on the current browser only. They do not sync across devices and are not sent to a database. The customer preview is not yet a separately hosted public menu page. Checkout is demo-only and collects no payment. Subscription buttons are concepts, not live payment flows. QR generation requires the external QRCode.js CDN. Do not use a local file URL on printed QR codes.

INCOME IDEAS
- Charge restaurants a setup fee for menu creation and QR artwork.
- Offer monthly menu update/branding/report packages (example prices: GH₵49 and GH₵99/month; validate before selling).
- Sell printed table cards, stickers and packaging inserts.
- Add paid menu photography, copywriting and custom branding.

PRODUCTION NEXT STEPS
Build a public menu route and backend/database, authentication and access controls, server-side validation, backups, privacy terms, and verified payment-provider webhooks before taking real orders or subscriptions. Never trust browser-only payment confirmations or put API secrets in client-side JavaScript.

Suggested Android package identifier: com.weatey.qrmenu (suggestion only, not a published app).
