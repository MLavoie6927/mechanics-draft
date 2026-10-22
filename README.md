# Mechanics Draft

A responsive mobile-mechanic website concept built from the structural approach of the existing cybersecurity portfolio: a sticky navigation shell, strong hero, progressive one-page sections, reusable cards, calls to action, and accessible vanilla JavaScript interactions.

## Preview

Open `index.html` directly, or serve the folder with any static web server.

## Customize before publishing

- Replace the draft business name.
- Add the real city, service radius, hours, phone, and email.
- Connect the request form to a booking, email, or CRM provider.
- Add only verified credentials, pricing, warranties, and reviews.
- Add appropriate privacy, terms, and accessibility information.

## Vehicle data

The cascading year, make, model, and configuration selectors use the public FuelEconomy.gov Web Services catalog administered by Oak Ridge National Laboratory for the U.S. Department of Energy and U.S. Environmental Protection Agency. The interface presents the latest 30 model years and never generates vehicle records when the service is unavailable.

## Payment activation

The request preview leads to `checkout.html`, which summarizes the selected $25, $35, or $50 travel fee. Card collection is intentionally delegated to a verified hosted payment provider. To activate real payment, add the mechanic's three amount-specific Stripe, Square, or PayPal hosted checkout URLs to `PAYMENT_URLS` in `checkout.js`. Never place secret API keys or raw card-handling code in this public repository.
