# Landing Page A/B Test Analysis  

## 📌 Project Background  
E-commerce platforms continuously experiment with landing page designs to optimize user engagement and conversion.  
This project evaluates whether a **new landing page flow** improves user behavior and business outcomes compared to the existing design.  

## 🔍 Overview  
- Dataset: **500,000 user records over 30 days**  
- Method: Randomly assigned users into **control** (old flow) and **treatment** (new flow) groups  
- Built a **four-metric evaluation framework**:  
  1. **User Funnel** – bounce rate & add-to-cart conversion rate  
  2. **Business Value** – number of items added to cart  
  3. **User Experience** – time to first add-to-cart  

Applied **Z-test** and **Mann-Whitney U test** to assess statistical significance.  

## 📊 Results  
- **+10.6%** add-to-cart conversion rate  
- **−20%** time to first add-to-cart  
- **+12.8%** bounce rate  
- No significant change in number of items added  

➡️ Interpretation: The new landing page **increased conversion efficiency** but also **raised bounce rate**, indicating a **mixed overall impact**.  


## 🛠 Tech Stack  
- **Python**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Statistical Testing**: Scipy, Statsmodels  

## 🚀 Key Takeaway  
The new landing page flow **accelerated conversion** but also introduced **higher drop-offs**.  
Findings highlight the trade-offs between **user efficiency** and **retention**, providing insights for further design iteration.  
