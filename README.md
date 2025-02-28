# Supply Chain Analysis

## Project Overview
Supply Chain Analysis involves evaluating different components of a supply chain to optimize efficiency, reduce costs, and improve overall business operations. This analysis is based on a dataset from a Fashion and Beauty startup focusing on makeup product supply chains.

## Dataset Overview
The dataset includes the following features:
- Product Type
- Stock Keeping Unit (SKU)
- Price
- Availability
- Number of Products Sold
- Revenue Generated
- Customer Demographics
- Stock Levels
- Lead Times
- Order Quantities
- Shipping Times
- Shipping Carriers
- Shipping Costs
- Supplier Name
- Location
- Lead Time
- Production Volumes
- Manufacturing Lead Time
- Manufacturing Costs
- Inspection Results
- Defect Rates
- Transportation Modes
- Routes
- Costs

---
## Data Cleaning Process
- Changed data types where necessary.
- Rounded off numeric values for clarity.
- Ensured consistency in categorical labels.

## Insights and Recommendations
Some of the insights generated from the dataset include: 

### 1. Revenue Insights and Trends

![dashboard 1](https://github.com/OlanikeCJ/Supply_Chain_Analysis/blob/main/Images%20-%20Supplychain/dashboard.png?raw=true)

#### **Revenue Performance Across SKU**
> - SKU 51 had the highest total revenue ($9,866), while SKU 98 had the lowest ($8,526).
  
- **Implication:** The business should assess why SKU 51 performs well. It could be due to better demand, marketing, or pricing. SKU 98's performance should also be investigated for improvements.

#### **Revenue Contribution by Shipping Carriers**
> - Highest revenue contributor: Carrier B ($250k)
> - Lowest revenue contributor: Carrier A ($143k)
  
- **Recommendation:** Carrier B appears to be more effective in revenue generation. If associated costs are reasonable, Carrier B should be prioritized for key shipments.

#### **Revenue and Sales by Product Type**
> - **Highest revenue & % sales:** Skincare ($241,628, 41.83%)
> - **Lowest revenue & % sales:** Cosmetics ($161,521, 27.96%)
  
- **Implication:** Skincare dominates sales, so investing more in marketing and product expansion strategies within this category is advisable.

#### **Average Price vs. Products Sold Across Categories**

> - **Most Sold Product Type:** Skincare (20,731 units, Avg. Price = $47.26)
> - **Least Sold Product Type:** Cosmetics (11,757 units, Total Price = $57.36)
  
- **Implication:** Skincare has the highest sales volume, which may be driven by its lower average price. The company should assess whether increasing the price slightly could optimize revenue without significantly reducing sales, and for cosmetics with the lowest sales volume, the company could consider reducing the prices of some of the products to increase patronage.

---

### 2. Logistics and Transportation Insights
![dashboard 2](https://github.com/OlanikeCJ/Supply_Chain_Analysis/blob/main/Images%20-%20Supplychain/dashboard%202.png?raw=true)

#### **Average Defect Rate by Product Type & Transportation Mode** 

> - **Haircare:** Highest defect rate by sea (3.64%), lowest by land (1.96%).
> - **Skincare:** Highest defect rate by road (2.99%), lowest by air (1.69%).
> - **Cosmetics:** Lowest defect rate by air (0.4%), highest by road (2.70%).
  
- **Recommendation:** Air transport is most reliable for low defect rates. Road transport should be optimized or reduced for skincare and cosmetics.

#### **Shipping Cost by Carrier**
> - **Highest Shipping Cost:** Carrier B (42.7%, $236.90)
> - **Lowest Shipping Cost:** Carrier A (28.03%, $155.54)
  
- **Implication:** While Carrier B contributes the most revenue, its costs should be analyzed for optimization.

#### **Cost Breakdown by Transportation Mode**

> - **Road:** $16k
> - **Rail:** $15.2k
> - **Air:** $14k
> - **Sea:** $7.1k
  
- **Recommendation:** Since sea transport is the cheapest but has a higher defect rate, the business should consider a balance between cost efficiency and product quality.

#### **Added Slicers:**

> - **Location Slicer** – Enables filtering insights based on different locations.
> - **Supplier Name Slicer** – Allows deeper analysis of lead time and production volume by supplier.

---
## Calculations

Click to view DAX expressions used for these insights.


## General Logistics Recommendations 
1. **Optimize Supplier Selection** – Consider Supplier 1 for urgent orders due to its shorter lead times.
2. **Cost Management** – Reduce procurement from Supplier 4 for cost-sensitive products due to its high manufacturing cost.
3. **Production Planning** – Increase collaboration with Supplier 4 for high-demand products given its high production capacity.
4. **Location-Based Strategy** – Use location-based filtering to identify regional supplier efficiencies and optimize supply chain logistics.


---

## Conclusion
This analysis provides robust insights into supply chain efficiency, revenue optimization, and logistics decision-making. By implementing the recommendations, the business can improve profitability, reduce costs, and enhance product quality across distribution channels.

