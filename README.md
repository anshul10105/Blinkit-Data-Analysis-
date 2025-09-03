## Project Overview

**This project focuses on Exploratory Data Analysis (EDA) of Blinkit’s sales dataset. The objective is to identify factors that influence sales performance, understand customer preferences, and derive actionable business insights. The analysis includes data cleaning, visualization, trend analysis, and business conclusions to help Blinkit optimize product strategies, outlet expansion, and pricing.**

 ### Dataset Description

The dataset used in this analysis includes the following key features:

 1. **Item Identifier** – Unique code for each product

 2. **Item Type** – Category of product (Food, Drinks, Household, etc.)

 3. **Item Fat Content** – Nutrition level (Low Fat, Regular, High Fat)

 4. **Item Weight** – Weight of each product

 5. **Item MRP** – Maximum Retail Price

 6. **Outlet Identifier** – Unique ID of the store

 7.**Outlet Establishment Year** – The year when the outlet was opened

 8.**Outlet Location Type** – City Tier (Tier 1, Tier 2, Tier 3)

 9. **Outlet Size** – Small, Medium, Large

 10. **Outlet Type** – Grocery Store / Supermarket (types 1, 2, 3)
 
 11. **Item Visibility** – % of shelf space given to the product

 12. **Item Outlet Sales** – Sales value of the product (target variable)
 
 13. **Rating**

### Exploratory Data Analysis (EDA)
1. **Data Cleaning**

Handled missing values in Item Weight and Outlet Size.

Standardized inconsistent categories in Item Fat Content (LF → Low Fat, reg → Regular).

Treated outliers in Item Visibility and extreme values in Item MRP.

2. **Univariate Analysis**

**Item Fat Content**:

Majority of products are either Low Fat or Regular.

Few products fall into High Fat.

**Item Type**:

Food items dominate sales, especially Snack Foods, Dairy, and Fruits/Vegetables.

**Item MRP**:

Distribution shows 3 clusters (low, medium, high price ranges).

**Outlet Establishment Year**:

Most outlets were established between 1985–2009, with older outlets showing stable sales.

3. **Bivariate Analysis**

**Item Fat Content vs Sales**:

Regular Fat items generate more revenue overall.

Low Fat items are more popular in Tier 1 cities.

**Item Type vs Sales**:

Snack Foods, Dairy, and Soft Drinks perform the best.

**Outlet Type vs Sales**:

Supermarkets (especially Type 3) significantly outperform grocery stores.

**Outlet Location Type vs Sales**:

Tier 3 cities contribute the most to sales compared to Tier 1 and Tier 2.

### Visualizations

  **Bar Charts**: Item Type vs Sales, Fat Content vs Sales.

  **Line Plot**s: Outlet Establishment Year vs Average Sales.

  **Heatmap**: Correlation among numerical features.


### Key Insights

#### Fat Content

Regular Fat products dominate sales volume.

Low Fat items are growing in Tier 1 (urban) outlets → rising health trend.

#### Item Category

Snack Foods, Dairy, and Beverages are the most profitable categories.

Non-food categories (Household, Hard Drinks) contribute less.

#### Outlet Performance

Supermarket Type 3 and larger outlets drive higher sales.

Tier 3 cities outperform Tier 1 & 2 in terms of revenue.

#### Pricing

Higher MRP products contribute strongly to revenue, showing potential for premium product strategies.

### Business Implications

Inventory Planning: Stock more of Snack Foods, Dairy, and Beverages.

Marketing: Promote Low Fat items in Tier 1 cities to capture health-conscious consumers.

Expansion: Focus outlet growth in Tier 3 cities, as they show stronger sales trends.

Pricing Strategy: Introduce premium pricing in top categories while maintaining affordability in mid-range products.

Outlet Optimization: Invest more in Supermarket Type 3 models for higher revenue.

### Conclusion

The Blinkit analysis shows that Fat Content, Item Category, MRP, and Outlet Characteristics are the most important drivers of sales.

Regular Fat items dominate but Low Fat has untapped growth in urban markets.

Tier 3 outlets and larger supermarkets are revenue leaders.

High-MRP products contribute disproportionately to overall sales.
  With these insights, Blinkit can refine its pricing, product positioning, and outlet expansion strategies to maximize sales and market growth.
