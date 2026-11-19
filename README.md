# Business Growth AI — website starter

This is a responsive, static front-end prototype for Business Growth AI.

## Preview locally
Open `index.html` in a modern browser.

## Deploy
1. Create a GitHub repository and upload `index.html`.
2. Import the repository into a hosting provider that supports static sites.
3. Add your custom domain in the hosting dashboard.
4. Follow the DNS records shown by the hosting provider at your domain registrar.

## Important: prototype limitations
This package is a front-end prototype. It does **not** yet include:
- Live Gemini API calls
- User accounts / authentication
- Supabase database
- Subscription billing or payment processing
- Server-side monthly/daily request enforcement
- Admin dashboard

Do not put a Gemini API key in browser-side JavaScript. Live AI must be connected through a secure server-side endpoint, with authentication, usage tracking, rate limits, and billing controls. Enable paid subscriptions only after checkout, account verification, and entitlement checks are implemented and tested.

The displayed Rs. 499/month and 100 requests/month are the proposed product plan, not an active paid subscription.
