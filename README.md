# Customer-Segmentation-KMeans
Customer segmentation using K-Means clustering based on annual income and spending score. 

# Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** on a dataset of mall customers to identify different customer segments based on annual income and spending behavior. It helps businesses understand their customers and improve marketing strategies.

---

## 📁 Dataset

**Mall_Customers.csv**  
Contains 200 entries with the following features:
- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## 🎯 Objective

To use **unsupervised learning** to segment customers into distinct groups based on their annual income and spending score. These insights can be used to:
- Identify high-value customers
- Personalize marketing campaigns
- Improve customer satisfaction

---

## 🧰 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧪 Workflow

1. **Data Preprocessing**
   - Loaded and inspected dataset
   - Selected relevant features (Annual Income, Spending Score)
   - Checked for missing values

2. **Exploratory Data Analysis**
   - Histograms, scatter plots
   - Elbow Method to determine the optimal number of clusters

3. **Modeling**
   - Applied K-Means clustering with `k=5`
   - Visualized customer segments in a 2D scatter plot

---

## 📈 Results

The **Elbow Method** suggested an optimal `k=5` for K-Means clustering. Based on the scatter plot (Annual Income vs. Spending Score), the customers were segmented into the following 5 clusters:

### 🔍 Cluster Interpretations

- 🔴 **Cluster 1 – Red (Top-Left):**  
  - **Low Income, High Spending**
  - Likely impulsive buyers or loyal customers with low income
  - May respond well to loyalty rewards

- 🟢 **Cluster 2 – Green (Middle-Left):**  
  - **Average Income, Average Spending**
  - Balanced and stable customers
  - Moderate profitability and risk

- 🔵 **Cluster 3 – Blue (Bottom-Right):**  
  - **High Income, Low Spending**
  - Conservative or value-conscious customers
  - Could be converted with better offers or engagement

- 🟡 **Cluster 4 – Yellow (Top-Right):**  
  - **High Income, High Spending**
  - Ideal target segment – premium customers
  - Very profitable and should be prioritized for marketing

- 🟣 **Cluster 5 – Purple (Bottom-Left):**  
  - **Low Income, Low Spending**
  - Least profitable segment
  - Possibly casual or one-time visitors

> 📊 The clustering helps businesses identify and prioritize segments for targeted strategies.


---

## 🙋‍♂️ Author

**Moh Ahamad**  
🎓 M.Sc. AI & ML @ Jamia Millia Islamia  
📧 [work.ahamad925@gmail.com](mailto:work.ahamad925@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/moh-ahamad1ai)


---

⭐ *If you found this helpful, consider giving the repo a star!*

