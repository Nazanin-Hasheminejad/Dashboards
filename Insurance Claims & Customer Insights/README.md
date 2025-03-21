# 📌 Insurance Claims & Customer Insights Dashboard

## 📌 Dashboard Preview
Here is a snapshot of the **interactive Power BI dashboard**:

![Image](https://github.com/user-attachments/assets/1c0ae594-fd75-44e7-bed0-efb36218c458)
---
## 📌 Project Overview  
This **Power BI dashboard** was developed as a self-assigned project using the **Healthcare Insurance dataset** from **Kaggle**. The dashboard provides an **interactive and data-driven analysis** of:
- **Key influencers of high claim amounts** – Identifying factors that significantly impact insurance claims.
- **Customer segmentation** – Understanding **which customer groups** are more likely to have high claims.
- **Demographic insights** – Analyzing the characteristics of **insurance customers** to help improve business strategies.

Although this dataset focuses on **healthcare insurance**, the same analytical approach can be applied to **any insurance dataset** to gain similar insights.

---

## 📌 About the Dataset  
The dataset contains various **customer attributes** related to insurance claims, including:

| **Column Name**  | **Description** |
|-----------------|----------------|
| **Age**         | The insured person's age. |
| **Sex**         | Gender (male or female). |
| **BMI**         | Body Mass Index – A measure of body fat based on height and weight. |
| **Children**    | Number of dependents covered under the insurance. |
| **Smoker**      | Indicates whether the insured is a smoker (Yes/No). |
| **Region**      | The geographic area of the insured customer. |
| **Charges**     | The total medical insurance cost incurred by the insured. |

### **Enhancements & Additional Data Transformations**
To enhance the analysis, several new **columns and measures** were created:
- **Age Group**: Categorized into **Teenager, Young Adult, Adult, and Senior**.
- **BMI Group**: Segmented into **Underweight, Healthy, Overweight, and Obesity**.
- **Claim Category**: Divided into **0-20K, 20K-40K, and >40K** claim ranges.
- **Smoker Percentage**: A calculated measure to determine the proportion of smokers within different groups.
- **Claim Demographics Field**: Created to analyze claim amounts across different variables.

---

## 📌 Key Sections & Functionalities

### **1. Key Drivers of High Insurance Claims**
- Identifies the most significant **factors influencing high claim amounts**.
- Shows the **correlation between smoking, BMI, and other key variables**.

### **2. Customer Demographics Analysis**
- Provides insights into **age, region, BMI categories, and smoking habits**.
- Helps understand **which customer groups** are more likely to file high claims.

---

## 📌 Impact & Business Value 
- **Insurance Companies**: Identify high-risk customers and adjust policies accordingly. 
- **Data Analysts**: Learn how **key influencers impact claim amounts** using Power BI.  
- **Business Decision Makers**: Use insights to **optimize insurance pricing and risk assessment**.
---
## 📌 How to Use This Project  
1. **Download the Power BI file (`.pbix`)** from the repository.  
2. Download the dataset from https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance
2. Open it using **Microsoft Power BI Desktop**.  
3. Explore the **interactive visuals, filters, and Q&A section** for insights.  
4. Modify the **DAX formulas or Power Query** to suit additional data sources if needed.  
