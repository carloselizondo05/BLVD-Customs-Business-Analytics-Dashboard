# BLVD Customs — Business Analytics Dashboard

**Industry:** E-commerce · Streetwear & Custom Embroidery  
**Location:** Mississauga, ON  
**Period:** January 2021 – September 2021  
**Role:** Co-Founder · Data & Business Analytics

---

## Overview

BLVD Customs was a streetwear brand built from the ground up, handling design, production, marketing, and sales entirely online. From day one, every business decision — what to stock, how to price, who to market to, how to grow — was driven by data tracked in a live Google Sheets dashboard.

This project documents that analytics infrastructure: the questions we were asking as a business, the data we collected to answer them, and the decisions that followed.

> 📊 [View the Live Dashboard →](https://docs.google.com/spreadsheets/d/1z7cTvMU6dy4GsNDx1_Ip-Bn9XxaqkmnS3O8L3R_Fujc/edit?usp=sharing)

---

## Results

| Metric | Result |
|---|---|
| Total Revenue | $6,485.79 |
| Total Expenses | $4,942.64 |
| **Net Profit** | **$1,543.15** |
| Break-even | Month 4 (April 2021) |
| Units Sold | 204 (69 hoodies · 105 crewnecks · 27 t-shirts) |
| Instagram Follower Growth | 500+ in 3 months (organic) |

---

## Dashboard Structure

The dashboard is organized into three analytical areas, each built to answer specific business questions in real time.

---

### 1. Market & Demand Segmentation

The goal of this section was to understand *who* our customers were and *what* they wanted, so we could make smarter inventory and marketing decisions instead of guessing.

#### 1.1 Sizes Sold
**Business question:** What sizes should we keep in stock vs. order on demand?

Large was the dominant size across all product types, followed by Medium. This shaped our inventory strategy — we kept L and M in stock and treated S, XL, and XXL as order-on-demand to avoid dead inventory. Youth (Y) sizes appeared rarely enough that we stopped stocking them entirely.

#### 1.2 Client Demographics
**Business question:** Who is our primary customer, and how should that shape our marketing?

Female customers made up the overwhelming majority of our client base. This directly influenced our design choices, colour selection, and the tone of our Instagram content. Rather than trying to appeal to everyone, we leaned into this — selecting designs, colours, and fits that resonated with our core demographic.

#### 1.3 Clothing Colours
**Business question:** Which colours sell consistently, and which are too risky to stock?

Neutral and versatile colours (White, Black, Navy Blue, Forest Green, Sand) were the most consistent performers. Colours like Carolina Blue, Indigo Blue, and Light Blue also performed well. High-risk specialty colours (Gold, Kiwi Green, Military Green, Safety Pink) appeared only once each in the data — confirming they should be ordered only on request rather than held in inventory.

#### 1.4 Clothing Types
**Business question:** Where should we focus our product offering?

Crewnecks outsold every other product category with 105 units (51% of all sales), followed by hoodies at 69 units (34%) and t-shirts at 27 units (13%). This told us crewnecks were our core product. T-shirts, while the cheapest item, had the lowest volume and thinnest margins — we kept them in the catalogue but didn't prioritize them in restocking.

#### 1.5 Designs Sold
**Business question:** Which designs have proven demand and are worth restocking?

Nike Vintage Sunday was the clear standout with 27 units sold — nearly 4x the next most popular design (Moon Media Logo at 7 units). A small cluster of designs (Queen's Uni, Portugal Club, Nike Vintage Butterfly, Emergency Department) consistently generated repeat orders. The majority of designs sold exactly once, confirming that our catalogue was broad but thin. This analysis justified focusing restock budget on the top ~10 proven designs rather than constantly introducing new ones.

---

### 2. Financial Analysis

This section tracked the financial health of the business in real time — from individual order profitability to monthly breakeven tracking.

#### 2.1 Estimated Price Per Order (Scatter Plot)
**Business question:** Are we pricing our orders consistently, and are we charging enough?

The scatter plot mapped estimated order value across all transactions. It revealed that the average order hovered around $35–40 in the early months, and crept toward $50+ after our pricing adjustment. Outliers (large bulk orders like the 15-hoodie sorority order at $645) were clearly visible and confirmed that B2B/group orders were a meaningful revenue driver worth pursuing.

#### 2.2 Final Payment Per Order (Scatter Plot)
**Business question:** Is what customers actually pay matching what we expect?

Comparing final payment against estimated price revealed that most customers paid close to or slightly above the estimate — a sign of healthy customer trust. A few outliers paid significantly less (partial payments, discounts) which we could trace back to specific deals. This comparison also exposed cases where we undercharged, which informed future pricing tightening.

#### 2.3 Cost Categories
**Business question:** Where is our money going, and what does that tell us about how to price?

Inventory (raw clothing) was by far the largest expense category, followed by Equipment (the embroidery machine was a $1,243 upfront cost in January) and Materials (threads, stabilizers, needles). This breakdown initially supported a cost-plus pricing model. Once we understood the cost structure, we transitioned to value-based pricing — charging based on design complexity and customer perceived value rather than a fixed markup over cost.

#### 2.4 Revenue Over Time
**Business question:** Are sales growing, plateauing, or declining?

Revenue grew steadily from $0 in January (setup month) through a peak of $1,936 in June. The drop to $289 in July reflects the final orders fulfilled as the business was wound down — not a seasonal dip. The overall trend confirmed that the organic Instagram growth strategy was working consistently through the entire operating period.

#### 2.5 Profit / Loss Over Time
**Business question:** When do we break even, and are we actually building a profitable business?

January and February were deep in the red due to equipment and initial inventory costs. The business turned its first monthly profit in March (+$365) and broke even on a cumulative basis in April. From April through June, monthly profit was consistently positive and growing. The total net profit across the business lifetime was **$1,543.15**, confirming that the model was viable — we were profitable within 4 months of launch with zero external funding.

#### 2.6 Type of Expense
**Business question:** Is our spending mix healthy, and where can we cut?

Breaking expenses into Equipment, Inventory, Materials, Packaging, and Advertisement showed that inventory was dominating spend (as expected for a product business), and that advertisement cost was nearly zero — just $10 on a single Instagram promotion. This validated our bet on organic growth and word-of-mouth as the primary marketing channel.

---

### 3. Operational & Marketing

This section tracked customer behaviour and channel performance to improve operations and marketing efficiency.

#### 3.1 Delivery Preference
**Business question:** What delivery options do customers actually want, and which are worth offering?

The majority of customers chose free drop-off, followed by Canada Post shipping, with pick-up being the least popular. Delivery (paid courier) was rarely requested. This told us that offering free local drop-off was a genuine competitive advantage that drove conversions — customers valued the convenience. Canada Post volume was enough to justify keeping it as a standard option, but paid delivery was not worth building out further.

#### 3.2 Payment Preference
**Business question:** Should we invest in payment infrastructure (card processing, etc.)?

E-transfer dominated overwhelmingly over cash. This confirmed that keeping e-transfer as the primary payment method was the right call — there was no demand signal that justified the cost or complexity of card payment infrastructure for a business at our scale.

#### 3.3 Shared on Client's Instagram
**Business question:** Does the 10% discount-for-a-story promotion actually drive word-of-mouth?

A significant portion of customers took the Instagram sharing deal — posting our brand to their story in exchange for 10% off their next order. This was our primary marketing channel. The data confirmed two things: customers were incentivized to come back (repeat purchase driver) and we were getting genuine organic reach into new audiences through their networks. The cost of the discount was easily justified by the marketing exposure and the repeat purchase behaviour it created.

---

## Skills Demonstrated

- Business analytics & dashboard design (Google Sheets)
- Financial modelling — break-even analysis, cost categorization, profit tracking
- Demand forecasting & inventory strategy
- Marketing analytics — channel attribution, word-of-mouth measurement
- Pricing strategy — cost-plus to value-based transition
- Entrepreneurship & end-to-end business operations

---

## Tools

Google Sheets · Excel-compatible formulas · Pivot tables · Charts & data visualization

---

## Notes

All client names in the raw data are represented by first initial only. Financial figures reflect actual transactions from January–August 2021.
