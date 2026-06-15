<!-- @format -->

# American Store Sales Analysis

Comprehensive Power BI analysis and visualization of American superstore sales data covering 2019 transactions.

## Datasets

### SuperStore_Sales_Dataset.csv / SuperStore_Sales_Dataset.xlsx

**Location**: `American Store/` folder

**Content**: Contains sales transactions from an American superstore covering 2019 data.

**Key Fields**:

- **Transaction**: Row ID, Order ID, Order Date, Ship Date, Ship Mode, Payment Mode
- **Customer**: Customer ID, Customer Name, Segment (Corporate/Consumer)
- **Location**: Country, State, City, Region
- **Product**: Product ID, Category, Sub-Category, Product Name
- **Metrics**: Sales, Quantity, Profit, Returns

**Data Characteristics**:

- Product Categories: Furniture, Technology, Office Supplies
- Ship Modes: Standard Class, First Class, etc.
- Payment Methods: Online, Cards, COD
- Contains error values (#N/A) in Returns column

### SuperMarket Analysis.csv

**Location**: `Super Market Sales/` folder

**Content**: Retail supermarket transaction data with customer satisfaction ratings.

**Key Fields**:

- **Transaction**: Invoice ID, Date, Time, Branch, City
- **Customer**: Customer Type (Member/Normal), Gender
- **Product**: Product Line (Health & beauty, Electronics, Home & lifestyle, Sports & travel, Food & beverages, Fashion accessories)
- **Sales**: Unit Price, Quantity, Tax (5%), Sales Amount, COGS
- **Performance**: Gross Margin Percentage, Gross Income, Customer Rating
- **Payment**: Payment Method (Ewallet, Cash, Credit Card)

**Data Characteristics**:

- Branches: Alex, Giza (likely different store locations)
- Cities: Yangon, Naypyitaw
- Includes customer ratings (0-10 scale)
- Complete tax and profitability calculations included

## Files

- `American Super Store.pbix` - Power BI dashboard for American store analysis
- `SuperStore_Sales_Dataset.xlsx` - Excel format of superstore sales data
- `images/` - Contains reference images and visualizations

## Getting Started

1. Open the Power BI files (`.pbix`) in Power BI Desktop
2. Review the datasets (`.csv` and `.xlsx`) for data structure
3. Check individual project READMEs for specific analysis details

---

_Last updated: 2026-06-16_
