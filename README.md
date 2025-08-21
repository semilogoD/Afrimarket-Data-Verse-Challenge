# Afrimarket-Data-Verse-Challenge

## 🚀 Project Overview
AfriMarket, a leading Jumia-style e-commerce platform operating across Nigeria and Ghana, faced declining customer satisfaction despite record-breaking traffic. 

As a Data Intelligence Officer, I conducted comprehensive marketplace data analysis to identify fraudulent patterns, assess seller reliability, and develop actionable trust-building strategies.

## 🎯 Key Objectives
•	Fraud Detection: Identify suspicious seller activities and fake review patterns

•	Risk Assessment: Analyze delivery delays, complaint patterns, and return rates

•	Trust Framework: Develop data-driven seller accountability measures

•	Business Intelligence: Create actionable insights to improve customer retention

## 📊 Dataset & Methodology
### Data Sources
•	Seller performance metrics

•	Customer transaction records

•	Delivery and logistics data

•	Customer reviews and ratings

•	Return and complaint records

## 🛠️ Tools & Technologies

Microsoft Excel -	Data exploration & visualization	Pivot tables, conditional formatting, statistical functions

Power Query	- Data transformation	ETL processes, data cleaning, automated workflows

Power Pivot	- Data modeling	Relationships, DAX measures, large dataset management

Excel Charts - Dashboard creation	Stacked charts, trend analysis, KPI dashboards

## 🔍 Key Findings

1. Seller Performance Analysis
   
- Top Sellers (low delivery delays): IDs 4, 18, 40

- Bottom Sellers (poor reliability): IDs 10, 19, 6

![](https://github.com/semilogoD/Afrimarket-Data-Verse-Challenge/blob/main/Top%20Performing%20sellers.PNG)
![](https://github.com/semilogoD/Afrimarket-Data-Verse-Challenge/blob/main/Underperforming%20sellers.PNG)

2. Product Category Insights
   
Highest Complaint Categories: 

- 📱 Electronics  

- 🧸 Toys  

- 🏥 Health

![](https://github.com/semilogoD/Afrimarket-Data-Verse-Challenge/blob/main/category%20performance%20analysis.PNG)

High Return Rate Categories:

- 🏠 Home & Living 

- 🛒 Groceries  

3. Geographic Performance

- Highest Delays: Southwest Region & Volta Region

![](https://github.com/semilogoD/Afrimarket-Data-Verse-Challenge/blob/main/regional%20delivery%20perfromance.PNG)

4. Fraud Detection Results
   
  Suspicious Review Patterns

- Seller IDs with 5-star ratings + high returns: 50, 20, 21

- Indicator: Potential fake positive reviews masking poor service

![](https://github.com/semilogoD/Afrimarket-Data-Verse-Challenge/blob/main/review%20fraud%205%20star%20rating%20with%20high%20returns.PNG)

## 🗠 Dashboard
![](https://github.com/semilogoD/Afrimarket-Data-Verse-Challenge/blob/main/Jumia%20Jitters%20Dashboard.PNG)

## 🤖 Predictive Model Development

### Risk Scoring Algorithm:

Risk Score = (Delay Flag × 0.4) + (Complaint Flag × 0.4) + (Price Flag × 0.2)

Feature Engineering

- Delay Flag: 1 if delivery > 5 days, 0 otherwise

- Price Flag: 1 if price > ₦256 (average), 0 otherwise

- Complaint Flag: Binary indicator for complaint presence

- IF(Risk Score > 0.6, "Likely Return", "No Return")

## 📋 Strategic Recommendations
### 🚨 Immediate Actions

1.	Seller Sanctions: Suspend high-risk sellers (IDs: 25, 19, 36, 33, 39)
  
2.	Category Regulation: Implement stricter controls for Home & Living and Groceries
   
3.	Regional Focus: Address logistics bottlenecks in the Southwest and Volta Regions

## ⚡ Operational Improvements
•	Delivery Standards: Penalize shipments exceeding a 5-day delivery window

•	Logistics Audit: Comprehensive review of high-delay product categories

•	Incentive Program: Reduced commissions and badges for consistent performers

•	Real-time Tracking: Mandatory order status updates from all sellers

•	Volume Controls: Limit orders for sellers with ongoing logistics issues

## 🛡️ Customer Trust Policy Framework
### Shipping Standards
•	Mandatory Timeline: All products shipped within 48 hours of order confirmation

•	Performance Monitoring: Continuous tracking of seller compliance metrics

### Quality Assurance
•	Audit System: Regular reviews for sellers with high complaint rates

•	Suspension Protocol: Clear escalation path for non-compliant sellers

•	Feedback Integration: Customer reviews directly influence seller ratings and visibility

## 📈 Expected Business Impact
### Customer Experience
•	Reduced Delays: Target 30% improvement in delivery times

•	Quality Assurance: Enhanced product reliability across categories

•	Trust Rebuilding: Transparent seller performance metrics

### Platform Performance
•	Fraud Reduction: Systematic identification of suspicious activities

•	Seller Accountability: Data-driven performance management

•	Market Position: Strengthened competitive advantage in West African e-commerce

## 🔮 Future Enhancements
•	Machine Learning Integration: Advanced fraud detection algorithms

•	Real-time Analytics: Live seller performance monitoring

•	Customer Sentiment Analysis: Review text mining for deeper insights

•	Automated Reporting: Scheduled performance dashboards



