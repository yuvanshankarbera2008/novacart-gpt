# NOVA CART prototype

A responsive, mobile-first quick-commerce prototype for local stores in Chennai, Bengaluru and Hyderabad. It is a dependency-free HTML/CSS/JavaScript single-page app, so open `index.html` directly in a modern browser.

## Included journeys

- Customer home, location selection, search, product list/detail, store page, saved neighbourhood stores, cart, delivery tracking, rewards, support, and the store/operations dashboard.
- 36 sample products across groceries, bakery, pharmacy, stationery, home care and more; 9 sample local stores.
- Availability-confidence labels, realistic delivery ranges, substitute selection before checkout, stock reservation messaging, issue shortcuts, refund status and a help chat.
- A responsive desktop sidebar and a thumb-friendly mobile bottom navigation.

## Welcome offer and delivery logic

Use the Login button from any entry state, choose **Sign up**, complete name and password, and the welcome panel gives the test account:

- Three free delivery tokens. Tokens are not deducted when checkout occurs; clicking **Demo: mark as delivered** on tracking counts the delivery. A cancelled/failed order therefore cannot consume one.
- A 50% first-order discount is automatically added once carts pass ₹199, capped at ₹150. It applies alongside free delivery. It is removed after the first checkout.
- At ₹2,000 subtotal, delivery becomes free without using a token. Below that threshold, the cart tells the user exactly how much remains.
- Orders worth ₹500 or more provide a scratch-card interaction. Scratching awards a demo free-delivery token and stores it in Rewards; the mechanic can be swapped for coupons, points or other configured reward outcomes in a backend.

## Why the product addresses retention

The prototype deliberately shifts the value proposition from blanket promotions to reliability and local loyalty: saved local shops and store stamps encourage repeat use; high/medium/low availability labels and upfront substitutes reduce cancellations; stock reservation and honest ETA language reduce missed expectations; one-tap support and proactive refund visibility reduce friction. The admin dashboard calls out low stock, demand forecasting, support queue health, influencer conversion and a promo-spend guardrail, helping teams reward repeat orders rather than buy only first orders.

## Metrics to track

1. Repeat purchase rate.
2. Second- and third-order rate for new users.
3. Average delivery time and ETA accuracy.
4. Cancellation rate, including stock-related cancellations.
5. Monthly support tickets and time to resolution.
6. Promo spend as a percentage of revenue.
7. Saved-shop reorder rate and local-loyalty reward redemption.
