# Venture Capital Investment Opportunity Analyzer (Tableau)

An interactive Tableau dashboard that helps Venture Capital funds identify the best investment opportunities from a pool of 1,000 startups based on data-driven financial criteria. This project demonstrates advanced Tableau skills including parameter controls, calculated fields, and interactive filtering for strategic decision-making.

---

## 📋 Business Problem

A Venture Capital Fund has been approached to review **1,000 potentially interesting startups** for investment. The Board of Directors needs a data-driven approach to identify which businesses represent the best investment opportunities.

### Investment Selection Criteria

The fund selects investments based on a combination of three key financial metrics (2015 data):

1. **High Revenue (2015)** – Companies generating strong sales
2. **Low Expenses (2015)** – Efficient cost management
3. **Top Growth (2015)** – Rapid revenue expansion

---

## 🎯 Business Objective

**Assist the Board in identifying which businesses represent the best investment opportunities** by creating an interactive dashboard that allows decision-makers to:

- Filter startups by revenue and expense thresholds
- Visualize qualifying companies (marked in red) vs. non-qualifying companies (marked in gray)
- Analyze growth trends by founding year
- Compare average employees across industries
- Evaluate the competitive landscape across industries

---

## 🔗 Live Dashboard

**View Interactive Dashboard:** [Tableau Public Link](https://public.tableau.com/app/profile/satyam.singh7169/viz/BestInvestmentOpportunities_16839540822980/Dashboard1)

## 📊 Dashboard Features & Components

### Interactive Parameters

#### 1. **Top Growth % (Adjustable)**
- **Type:** Integer Parameter
- **Default:** 20 (top #n)
- **Purpose:** Shows the top n companies  
- **Usage:** Allows users to adjust strictness of growth criteria

#### 2. **High Revenue Cutoff**
- **Type:** Currency Parameter
- **Default:** $8M
- **Range:** $1M - $20M+
- **Purpose:** Minimum revenue threshold for qualifying companies
- **Interactive Control:** Slider with manual input field

#### 3. **Low Expense Cutoff**
- **Type:** Currency Parameter  
- **Default:** $4M
- **Range:** $1M - $10M+
- **Purpose:** Maximum expense threshold for efficient operations
- **Interactive Control:** Slider with manual input field

#### 4. **In/Out of High Revenue Range Filter**
- **Type:** Boolean Filter
- **Options:** "In" (meets criteria) vs. "Out" (doesn't meet criteria)
- **Visual Indicator:** In = Red markers, Out = Gray markers

---

## 📈 Visualizations

### 1. **Main Scatter Plot: Revenue vs. Expenses (2015)**
**Chart Type:** Scatter plot with quadrant analysis

**Key Features:**
- **Color Coding:**
  - 🔴 Red dots: Companies meeting ALL investment criteria (High Revenue, Low Expenses, Top Growth)
  - ⚪ Gray dots: Companies NOT meeting criteria
- **Reference Lines:** 
  - Vertical line at $4M expense threshold
  - Horizontal line at $8M revenue threshold
- **Quadrant Division:** Creates four investment zones:
  - Top-Left (Target): High Revenue, Low Expenses ✅
  - Top-Right: High Revenue, High Expenses ⚠️
  - Bottom-Left: Low Revenue, Low Expenses
  - Bottom-Right: Low Revenue, High Expenses ❌

---

### 2. **Average Employees per Industry**
**Chart Type:** Horizontal bar chart

**Key Features:**
- Industries sorted by average employee count
- Color-coded by industry category
- Shows operational scale across sectors
- Industries included: Advertising, Business Products, Construction, Consumer Products, Education, Energy, Engineering, Environment, Financial Services, Food & Beverage, Government, Health, and more

**Business Insight:** Helps identify whether target companies have appropriate staffing levels for their industry

---

### 3. **Number of Companies Founded by Year**
**Chart Type:** Vertical bar chart

**Key Features:**
- X-axis: Year Founded (2009 & Before, 2010, 2011, 2012, 2013, 2014)
- Y-axis: Count of companies
- Color-coded by founding year cohort
- Shows distribution of startup maturity

**Business Insight:** Helps assess company maturity and risk profile (newer vs. more established startups)

---

## 🔍 Key Insights & Analysis Capabilities

### What This Dashboard Reveals:

1. **Investment Sweet Spot Identification**
   - Quickly identify companies in the top-left quadrant (high revenue, low expenses)
   - Red-marked companies meet all three investment criteria
   - Clear visual separation of qualified vs. non-qualified opportunities

2. **Cost Efficiency Analysis**
   - Companies below the expense threshold demonstrate lean operations
   - Comparison of revenue-to-expense ratios across the portfolio

3. **Industry Benchmarking**
   - Compare operational scale (employee count) by industry
   - Identify sectors with favorable unit economics

4. **Maturity Distribution**
   - Majority of startups founded 2009-2012 (more established)
   - Fewer 2013-2014 startups (earlier stage, higher risk)

---

## 🚀 How to Use This Dashboard

### For Investment Decision-Makers:

1. **Set Your Investment Criteria:**
   - Adjust the **High Revenue** slider to your minimum revenue threshold
   - Set the **Low Expense** slider to your maximum acceptable expense level
   - Modify **Top Growth %** to change growth selectivity (lower % = more selective)

2. **Identify Qualified Companies:**
   - Red dots in the scatter plot = companies meeting ALL criteria
   - Hover over red dots to see company details
   - Click on companies for detailed drill-down

3. **Analyze Industry Trends:**
   - Review average employees by industry to understand operational norms
   - Compare your target companies against industry averages

4. **Evaluate Company Maturity:**
   - Check the founding year distribution
   - Balance portfolio between established companies (2009-2012) and newer entrants

5. **Export Shortlist:**
   - Filter to "In" range only
   - Export qualifying companies for detailed due diligence

---
<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/Investment_portfolio_analytics_Tableau/blob/main/img1.png" /></a></p> 

## 🎓 Tableau Skills Demonstrated

### Advanced Features:
✅ **Parameter Controls** – User-adjustable filters for dynamic analysis  
✅ **Calculated Fields** – Complex IF/AND logic for investment qualification  
✅ **Reference Lines** – Visual thresholds on scatter plots  
✅ **Color Coding Logic** – Conditional formatting based on multiple criteria  
✅ **Percentile Calculations** – Top growth ranking  
✅ **Aggregations** – AVG, COUNT functions across dimensions  
✅ **Interactive Filters** – In/Out range selections  
✅ **Multi-Chart Dashboard** – Coordinated views for comprehensive analysis  
✅ **Scatter Plot Analysis** – Two-dimensional metric comparison  
✅ **Hover Tooltips** – Detailed on-demand information  
 

---

## 💡 Business Impact

### Problem Solved:
Instead of manually reviewing 1,000 startup profiles, the Board can now:
- Instantly identify qualified investment opportunities
- Adjust criteria dynamically based on fund strategy
- Compare startups objectively using consistent financial metrics
- Reduce screening time from weeks to minutes

### Potential Use Cases:
- **Venture Capital Firms** – Portfolio screening and selection
- **Angel Investors** – Early-stage opportunity evaluation
- **Private Equity** – Growth company identification
- **Accelerator Programs** – Cohort selection and ranking
- **M&A Teams** – Acquisition target identification

---

## 🔗 Live Dashboard

**View Interactive Dashboard:** [Tableau Public Link](https://public.tableau.com/app/profile/satyam.singh7169/viz/BestInvestmentOpportunities_16839540822980/Dashboard1)

---






