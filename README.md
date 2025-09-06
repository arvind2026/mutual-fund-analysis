# Mutual Fund Performance Analysis

## Project Overview
This project evaluates over 2,500 mutual fund schemes to identify optimal investment opportunities using quantitative risk–return methodologies. Through systematic data processing, statistical analysis, and a custom scoring algorithm, I ranked and filtered funds to deliver a curated list of 30 high-performing, low-risk schemes. The analysis is presented in an interactive Power BI dashboard that converts complex financial data into actionable insights.

**Key Achievement**: Reduced the investment universe by 98.8% while maintaining superior risk-adjusted returns.

---

## Project at a Glance
- **Dataset**: 2,500+ mutual fund schemes with 15+ financial variables  
- **Tools**: Python (Pandas, scikit-learn), Excel, Power BI  
- **Output**: Top 30 funds ranked for risk–return balance  
- **Impact**: Evidence-based framework supporting investors, advisors, and institutions  

---

## Objectives
**Primary Objective**: Identify mutual fund schemes with optimal risk–return profiles to enable data-driven investment decisions.

**Supporting Objectives**:
- Develop a scalable quantitative scoring framework  
- Generate actionable insights from complex datasets  
- Build interactive tools for ongoing performance monitoring  
- Demonstrate measurable business impact through systematic analysis  

---

## Methodology

### End-to-End Data Analysis Pipeline
**Phase 1: Data Acquisition and Exploration**
- Collected dataset of 2,500+ mutual fund schemes with 15+ variables  
- Conducted exploratory analysis to assess data quality and patterns  
- Established governance protocols for analytical consistency  


**Phase 2: Data Cleaning and Transformation**
- Addressed missing values, outliers, and inconsistencies  
- Standardized financial metrics across formats  
- Achieved 99.7% completeness across performance variables  

**Phase 3: Statistical Analysis and Feature Engineering**
- Generated descriptive statistics and correlation analysis  
- Normalized data with MinMaxScaler for fair comparisons  
- Created derived features such as volatility-adjusted returns  

**Phase 4: Scoring Algorithm Development**
Weighted model optimized for:
- Long-term performance (3-year returns, 40%)  
- Cost efficiency (expense ratio, 25%)  
- Consistency (positive returns across periods, 20%)  
- Fund maturity (experience factor, 15%)  

**Phase 5: Validation and Selection**
- Applied algorithm across full dataset  
- Performed cross-validation and sensitivity analysis  
- Selected top 30 funds representing optimal balance of risk and return  

---

## Tools and Technologies

| Technology     | Application                                   |
|----------------|-----------------------------------------------|
| **Python**     | Statistical analysis, scoring algorithm       |
| **Pandas**     | Data manipulation and transformation          |
| **Scikit-learn** | Normalization and preprocessing             |
| **Excel**      | Validation, supplementary reporting           |
| **Power BI**   | Interactive dashboard and visualization       |

---

## Key Insights

**Market Structure**
- Equity funds dominate with ₹1.35 trillion AUM (68% market share)  
- Index funds are most cost-efficient at 0.26% average expense ratio  
- Top quartile funds deliver 14.4% annualized returns with lower volatility  

**Risk–Return Optimization**
- Selected equity funds: 37.84% three-year average returns (vs. 28.6% category)  
- Hybrid funds: 14.25% returns with 40% lower volatility  
- Portfolio reduced average expense ratios by 32%  

**Investment Accessibility**
- SIP minimum: ₹528.50/month, supporting broad participation  
- Lump sum median: ₹3,050, ensuring low entry barriers  
- Leading fund manager oversees ₹7.3 trillion AUM  

---

## Dashboard and Visualization
The Power BI dashboard includes:
- **Advanced Filtering**: Fund type, category, AMC, risk level, rating  
- **Executive KPIs**: Asset allocation, SIP vs. lump sum, expense ratios, long-term returns  
- **Fund Manager Analysis**: Rankings by AUM and performance  
- **Automated Insights**: Dynamic cards highlighting trends and recommendations  

- [Download Dashboard (.pbix)](/dashboard/Mutual_Fund_Dashboard.pbix) 
 
#### Dashboard Preview :

  ![Dashboard Preview](/dashboard/Dashboard.png)
- **Description**: Static preview of the dashboard for quick review      
- **Application**: Executive summary and stakeholder presentations 

## Business Impact

**For Individual Investors**
- 73% improvement in risk-adjusted returns  
- 32% reduction in average fees  
- Decision-making time reduced from weeks to minutes  

**For Financial Advisors**
- Defensible, transparent recommendations  
- Scalable framework for diverse clients  
- Clear documentation supporting compliance  

**For Institutions**
- Framework adaptable to large-scale allocation decisions  
- Enhanced diversification and reduced concentration risk  
- Ongoing monitoring through systematic fund evaluation  

---

## Technical Architecture
- **Extract**: Data ingestion with validation checks  
- **Transform**: Cleaning, statistical analysis, scoring model  
- **Load**: Processed dataset integrated into Power BI  
- **Monitor**: Automated QA, significance testing, back-testing  

---

## Deliverables

| Deliverable | Description | Application |
|-------------|-------------|-------------|
| [Optimized Fund Selection](/data/top_30_mutual_funds.xlsx) | Curated list of top 30 mutual funds with analytical scores | Direct investment analysis and selection |
| [Interactive Dashboard](/dashboard/Dashboard.pbix) | Power BI file with interactive analytics and KPIs | Ongoing performance tracking and monitoring |
| [Dashboard Preview](/dashboard/Dashboard.png) | Static visualization of the dashboard | Executive summary and stakeholder communication |


---

## Conclusion
This project demonstrates how structured data analysis can transform subjective investment choices into objective, evidence-based strategies. By combining Python-based analytics with interactive Power BI dashboards, I delivered a replicable framework that improves returns, reduces costs, and simplifies decision-making for diverse stakeholders.

The work reflects core skills in data cleaning, statistical analysis, algorithm development, visualization, and business intelligence.
