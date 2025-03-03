# HNG-Internship-Tasks
My HNG internship projects and reports 

# Task 1: Data Cleaning, Preparation, and Title Optimization

## 📝 Project Overview
For Task 1, I worked on cleaning and optimizing a marketing dataset containing **3,847 rows and 6 columns**. The goal was to ensure data consistency, improve readability, and create concise, SEO-friendly product titles for better marketing performance.  

## 📊 Key Steps in Data Cleaning

### 1. Duplicate Removal
- **217 exact duplicates** removed.  
- **88 additional duplicates** identified using `PRODUCTID` as a unique identifier.  
- Final dataset size: **3,541 unique rows**.  

### **2. Handling Missing Values**  
- **DESCRIPTION**: 1,896 missing values filled using `BULLET_POINTS`.  
- **BULLET_POINTS**: 1,363 missing values handled similarly.  
- If both were missing, `short_title` was used as a fallback.  

### **3. Standardizing Column Names**  
| Original Name | Updated Name |  
|--------------|-------------|  
| PRODUCTID | product_id |  
| TITLE | short_title |  
| BULLET_POINTS | bullet_points |  
| DESCRIPTION | description |  
| PRODUCTTYPEID | product_type_id |  
| productlength | product_length |  

### **4. Standardizing Product Length Format**  
- Ensured consistent **two-decimal-place rounding** using Excel’s `ROUND()` function.  

#### **5. Short Product Title Optimization**  
- Used **Copy.ai SEO Title Generator** and **ChatGPT** to create concise, SEO-friendly titles.  
- **Examples:**  
  - **Before:** "ArtzFolio Tulip Flowers Blackout Curtain for Door, Window & Room Eyelets & Tie Back"  
    **After:** "ArtzFolio Midnight Tulip Blackout Curtain"  
  - **Before:** "PRIKNIK Horn Red Electric Air Horn Compressor Dual-Tone Super Loud Sound 12V for Car, Truck, Bike"  
    **After:** "PRIKNIK Thunderblast Dual-Tone Air Horn"  

### **🛠️ Tools & Technologies Used**  
- **Microsoft Excel** – Data cleaning and transformation  
- **Copy.ai SEO Title Generato** – to create concise, SEO-friendly titles  
- **ChatGPT** – to create concise, SEO-friendly titles


### **📁 Project Files**  
| File Name | Description |  
|-----------|------------|  
| [Cleaned_Dataset.xlsx](https://docs.google.com/spreadsheets/d/1GebEyS7ycjKmy_U9SEwVGHYSx31R88qlhnow3kT6Ilk/edit?usp=drive_link) | Final cleaned dataset |  
| [Data_Cleaning_Report.pdf](https://drive.google.com/file/d/1GaF3OVghkpxNFYDLz-rAScltNNDJf6qT/view?usp=drive_link) | Summary of cleaning process |  
  


### **📌 Next Steps**  
- Further refine product title optimization techniques.  
- Implement machine learning for automated data cleaning.  




### **📢 Connect with Me**  
💼 [LinkedIn](https://www.linkedin.com/in/tafri-annie/) | 🐦 [Twitter](https://x.com/TechyTafri) 
