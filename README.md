#  Customer Segmentation using K-Means

This repository contains my second machine learning project as an intern at **Elevvo Pathways**.  
The goal of this project is to **segment mall customers into distinct groups** based on their characteristics, helping businesses understand customer behavior and design better marketing strategies.  

---

##  Project Overview
- **Objective**: Identify groups of customers with similar shopping patterns.  
- **Dataset**: [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/shwetabh123/mall-customers)  
- **Approach**: Apply **unsupervised learning (K-Means clustering)** to group customers without predefined labels.  

---

##  Steps & Methodology
1. **Data Exploration**  
   - Visualized customer income and spending patterns.  
   - Identified possible relationships between features.  

2. **Data Preprocessing**  
   - Applied **feature scaling** for better clustering accuracy.  

3. **Modeling**  
   - Used **K-Means clustering** to form groups.  
   - Determined the **optimal number of clusters** using the **Elbow Method**.  

4. **Visualization**  
   - 2D and 3D plots to illustrate customer segments.  
   - Clear interpretation of each cluster’s characteristics.  

---

##  Results
- Customers were segmented into **distinct groups** (e.g., high-income high-spending, low-income low-spending).  
- Visualizations revealed clear differences between clusters.  
- The insights can help businesses:  
  - Identify target customers.  
  - Design personalized marketing campaigns.  
  - Improve customer experience.  

*(Visual examples are included inside the notebook.)*  

---

##  Tools & Libraries
- Python  
- Pandas  
- Matplotlib  
- Plotly  
- Scikit-learn  

---

##  How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
   cd customer-segmentation

2. Install dependencies:
   pip install -r requirements.txt

3. Open the Jupyter Notebook:
   jupyter notebook Customer\ Segmentation.ipynb

## Repository Structure
├── Customer Segmentation.ipynb   # Main notebook
├── README.md                     # Project documentation
└── requirements.txt              # Dependencies

## Key Takeaways
This project demonstrates how unsupervised learning can uncover hidden patterns in customer behavior.
It’s not just about algorithms—it’s about turning raw data into actionable insights.
