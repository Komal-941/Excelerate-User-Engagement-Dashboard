
# 🚀 Platform Activity and Engagement Overview Dashboard  
**Analyzing User Participation on the Excelerate Platform using Power BI**  

---

## 📊 Overview  
This Power BI dashboard provides a comprehensive analysis of user activity and engagement on the Excelerate platform. 
It answers key business questions by examining user sign-ups, opportunity participation, geographic distribution, demographic insights, and scholarship impact.  

---

## 🎯 Key Performance Indicators (KPIs)  
- **18K Total Sign-Ups** on the platform  
- **20K Opportunity Sign-Ups** indicating high user engagement  
- **Top 10 Countries** and **Top US Cities** with the highest user registrations  
- **Most Popular Opportunities** for sign-up and completion  
- **Gender Distribution** showing platform diversity  
- **Student Status Analysis** identifying user education levels  
- **Most Gained Skills** reflecting platform's learning impact  
- **Total Scholarships Awarded** with detailed opportunity-wise breakdown  

---

## 🔍 Key Insights  
- **India** leads with the highest number of sign-ups, followed by **Nigeria** and **United States**.  
- **Data Visualization** is the most popular opportunity learners signed up for, with **5686** sign-ups.  
- **Saint Louis** and **Chicago** are the top US cities for platform engagement.  
- **Female** users dominate the platform with 60% participation.  
- **Graduates** form the largest segment of users at 46.5%.  

---

## 📊 Data Understanding  
### User Data:  
- **Contains:** User demographics, registration details, status description, and gender.  
- **Key Columns:** Profile ID, Country, Gender, Status Description, and Sign-Up Date.  
- **Purpose:** To analyze user participation, demographic distribution, and engagement trends.  

### Opportunity Data:  
- **Contains:** Information on opportunities users signed up for, completed, and scholarship details.  
- **Key Columns:** Profile ID, Opportunity Name, Sign-Up Status, Completion Status, and Scholarship Amount.  
- **Purpose:** To analyze opportunity popularity, completion rates, and scholarship distribution.  

---

## 🔄 Data Preprocessing  
1. **Data Cleaning**:  
   - Checked for missing values and duplicates.  
   - Standardized country names and removed inconsistencies in gender and status descriptions.  
   - Handled null values in the scholarship column by replacing them with zero.  

2. **Data Transformation**:  
   - Converted date columns to DateTime format for accurate time-based analysis.  
   - Created new columns for **Sign-Up Year**, **Sign-Up Month**, and **Completion Year** to analyze trends over time.  

3. **Data Validation**:  
   - Ensured data consistency by cross-verifying total sign-ups and opportunity sign-ups.  
   - Conducted exploratory data analysis (EDA) to understand data distribution and patterns.  

4. **Data Integration**:  
   - Merged User Data and Opportunity Data using **Profile ID** as the primary key.  
   - Established relationships in Power BI to enable cross-filtering and drill-through functionalities.  

---

## 📁 Datasets  
- **[User Data](https://drive.google.com/file/d/1Xe8PoIGpiPrUGAxlTBg03mn4YJxP4AB_/view)**: Contains user demographics, registration details, and status descriptions.  
- **[Opportunity Data](https://drive.google.com/file/d/1xLvsDSMTv7PrhKpXQao1yp5wEP4U91is/view)**: Includes opportunity sign-ups, completions, and scholarship details.  

---

## 🔗 Managing Relationships in Power BI  
- Established a **one-to-many relationship** between the datasets using the **Profile ID** key.  
- Ensured accurate data linkage to enable cross-filtering and drill-through functionalities.  
- This was crucial for analyzing user behavior across multiple opportunities.  

---

## 🔨 Crucial Steps Performed  
1. **Data Collection & Preparation**:  
   - Imported and preprocessed User Data and Opportunity Data in Power BI.  
   - Ensured consistency and accuracy through data cleaning and transformation.  

2. **Data Modeling & Calculations**:  
   - Created **Calculated Columns** for Date Conversion, Sign-Up Status, and Scholarship Calculations.  
   - Developed **Measures** for KPI calculations, such as Total Sign-Ups, Opportunity Sign-Ups, and Completion Rates.  

3. **Dashboard Design & Visualization**:  
   - Designed a wireframe to plan layout and visualizations.  
   - Used **KPI Cards** for key metrics and **Bar Charts**, **Tree Maps**, and **Pie Charts** for detailed analysis.  
   - Implemented interactive **Filters** for Country, Gender, Status Description, and Date Range.  

4. **Insight Generation & Storytelling**:  
   - Analyzed user participation trends and popular opportunities.  
   - Identified geographic and demographic patterns for strategic decision-making.  
   - Visual storytelling enhanced with dynamic titles and detailed tooltips.  

---

## 🛠️ Tools & Technologies Used  
- **Power BI** for Data Visualization and Dashboard Creation  
- **DAX (Data Analysis Expressions)** for custom calculations  
- **Excel** for initial data examination and preprocessing  


---

## 📝 Summary  
This project showcases my end-to-end Data Analysis and Visualization capabilities, from data understanding and preprocessing to insightful storytelling using Power BI. It highlights the platform's user engagement trends and provides actionable insights for strategic decision-making.  

Feel free to explore the dashboard and insights shared in this repository. Your feedback and suggestions are welcome!  

---

## 📫 Connect  
- **LinkedIn**: [Komal S. Shelar](http://www.linkedin.com/in/komal-s-shelar)  
- **GitHub**: [https://github.com/Komal-941]  
