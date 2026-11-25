# Smart India Hackathon Workshop
# Date: 25/11/2026
## Reference Number: 26002643
## Name: Sam Jeswin A F

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
FarmLink is a mobile-friendly marketplace where farmers and FPOs can list available produce with quantity, location, harvest date, expected price, and basic quality details. Consumers, retailers, restaurants, and institutional buyers can browse listings, compare offers, place orders, and pay digitally. The platform will support both fixed-price listings and buyer bids so sellers can choose the option that suits them.

A logistics feature will group nearby orders and connect sellers with transport providers for pickup and delivery. Order tracking and digital receipts will make each transaction easier to follow. A simple dashboard will show the farmer the offered price, fees, transport cost, and expected net earnings before accepting an order.

The marketplace reduces reliance on multiple middlemen by helping producers reach more buyers directly. Its distinctive focus is to combine transparent net-price information, group logistics, and demand forecasts in one accessible service. The platform will complement existing market channels and follow applicable local trading rules.

## Technical Approach
Farmlink will be developed using web technologies to provide farmers and buyers an easy way to communicate

#### Software Requirements
```
Frontend: HTML, CSS, JavaScript
Backend: Python Django
Version updation: GitHub
Database: MySQL
Data Processing: NumPy and Pandas 
Development Environment: Visual Studio Code
```
- User app and buyer portal: Build a responsive web application, with a lightweight Android app or progressive web app for farmers. Use local-language labels, large buttons, and low-bandwidth pages.
- Core services: Use a REST API with a backend such as Python (Django/FastAPI) or Node.js, and PostgreSQL for user, listing, order, and payment records. Store product photos in secure object storage.
- Marketplace workflow: Verify farmer/FPO and buyer accounts; create produce listings; search and filter by crop, quantity, location, date, and price; place or accept offers; confirm orders; record payment status; and provide receipts and order updates.
- Payments and trust: Integrate a regulated payment provider or approved payment rails. Show the full price breakdown before order confirmation. Keep an audit trail for orders, cancellations, and complaints; do not store card or banking credentials directly.
- Demand forecasting: Start with historical listing, order, seasonal, and market-price data. Build a baseline time-series forecast by crop and area, then evaluate more advanced models only when sufficient reliable data is available. Display forecasts as estimates with confidence ranges, not guaranteed prices.
- Prototype process:Interview a small group of farmers/FPOs and buyers; build listing, search, ordering, and logistics screens; test a limited pilot for a few crops and locations; measure transaction completion, delivery time, farmer net realization, and buyer satisfaction; then improve based on feedback.

## Feasibility and Viability
The idea is feasible as a pilot because its first version can use common web and mobile technologies and focus on a small area, a few crops, and a limited set of buyers. The platform can begin with manual demand summaries and logistics matching before adding machine-learning forecasts or automated route optimization.

Potential challenges include limited smartphone connectivity or digital literacy, inaccurate quantity and quality information, seasonal supply changes, delayed payments, transport availability, perishability, disputes, and local market or licensing requirements. Forecasts may be weak when historical data is sparse, and a marketplace can struggle if it does not attract enough buyers and sellers at the same time.

To reduce friction we include assisted onboarding through FPOs and local partners; local-language, low-bandwidth design; clear listing standards and optional quality checks; transparent fees and cancellation; payment confirmation and grievance support;offering manual logistics coordinasion during the pilot.

A sustainable operating model could use a small, clearly disclosed transactions or logistics service fee. During the pilot, measure whether the farmer's net realization improves after all fees and transport costs, and whether buyers receive reliable quality and delivery.

## Impact and Benefits
- Farmers and FPOs: More buyer visibility, access to bulk demand, clearer price comparisons, and a view of expected net earnings before accepting an order.
- Consumers and institutions: More direct sourcing options, clearer product and price information, and the possibility of lower costs where reduced handling and transport expenses are passed through.
- Supply chain: Better coordination between orders and transport can reduce empty trips, avoibable delays, and produce damage. Forecasts can help sellers and buyers plan quantities, although outcomes depend on data quality and adoption.
- Rural communities: Digital listings and order records can support local commerce and help FPOs coordinate members' supply.
- Success measures: Track farmer net realization per unit, buyer price compared with local alternatives, share of orders delivered on time, spoilage or rejection rate, repeat orders, and participation by small producers and FPOs. Compare pilot results with a baseline and report limitations.

## Research and References
1. https://enam.gov.in/
2. https://enam.gov.in/stakeholders-Involved/traders
3. https://sfacindia.com/fpos.aspx/UploadFile/Statistics/UploadFile/Statistics/Aboutus.aspx
4. https://www.digitalindia.gov.in/
