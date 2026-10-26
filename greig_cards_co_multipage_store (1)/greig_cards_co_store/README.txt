GREIG CARDS CO. MULTI-PAGE STORE STARTER

FILES
- index.html: home page
- singles.html: individual card listings with search, set filter and add-to-cart
- bundles.html: separate bundle listings
- sets.html: browse set categories
- checkout.html: cart and checkout placeholder
- README.txt: these instructions

PREVIEW
Open index.html in a browser. Keep all five HTML files in the same folder.

EDIT LISTINGS
Open singles.html in a text editor and find `const inventory=[`.
Open bundles.html and find `const bundles=[`.
Replace example names, set names, descriptions, conditions, and prices with accurate details from your actual stock. Prices are NZD examples only. Keep the products honest and in stock.

SET PAGES
The Browse by Set page links into Singles with a set filter query. To add sets, add a tile in sets.html and matching set names in the inventory array in singles.html.

ONLINE PAYMENTS
The cart stores items in the visitor's browser and calculates a demo subtotal. It does NOT charge a customer or create a real order.
To enable payment:
1. Set up a supported payment provider/payment link with a parent or guardian and confirm account eligibility, fees and shipping.
2. Create a real checkout/payment link in that provider's dashboard.
3. Open checkout.html and find `const PAYMENT_URL = "";`
4. Paste your real payment URL between the quotation marks.
A single hosted payment link may not automatically match the cart total or individual cart contents. For a proper dynamic checkout with exact totals, inventory and shipping, use an ecommerce platform or a secure backend/payment integration rather than only a static HTML site.
Never ask customers to send card details by email or enter payment-card numbers into this site.

HOSTING
You can deploy these static files to a static host such as GitHub Pages or Netlify, subject to their current terms and setup process. A custom domain may cost extra. Ask a parent/guardian to help with hosting, payments, public contact information and customer meetups.
