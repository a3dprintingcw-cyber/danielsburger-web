# Daniels Burger · ordering demo

Pitch demo of pickup ordering for Daniels Burger, Caracasbaaiweg (Bottelier), Curaçao. Built by A3D.

- `index.html`: the customer ordering app and the kitchen board in one page
- `images.js`: the Daniels Burger logo (embedded)

The grey bar at the top is for the pitch only: it switches between the customer phone and the kitchen screen.

This is a demo. Orders stay in the browser and nothing is sent anywhere. The live version would follow the Volcano setup: a Cloudflare Worker and database, a kitchen board, Sentoo payments and WhatsApp or push updates when the food is ready.

Menu is in the `BURGERS`, `FRIES`, `DRINKS` and `ADDONS` lists in `index.html`, transcribed from their menu board on Instagram.

Still to confirm with Daniels:
- All prices (the menu board has no prices, the ones in the demo are placeholders in XCG)
- Drinks list (not on the menu board)
- Add on prices
- Opening hours: set to Tue to Thu 21:00 to 24:00, Fri and Sat 21:00 to 01:00, closed Sunday and Monday (from their Instagram bio)
