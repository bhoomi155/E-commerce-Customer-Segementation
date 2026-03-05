# 📊 E-Commerce Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project is a web-based **Customer Segmentation System** that analyzes customer data and groups customers into meaningful clusters using the **K-Means Clustering algorithm**. The application helps businesses understand customer behavior and make better marketing decisions using data analysis.

The system allows users to upload a dataset in **CSV format**, processes the data, performs clustering, and visualizes the results through different analytical charts.

---

# 📸 Project Screenshots

## 🏠 Homepage (index.html)

<p align="center">
  <img src="screenshots/index_page.png" width="800">
</p>

---

## 📊 Results Page (result.html)

### Customer Segmentation Dashboard

<p align="center">
  <img src="screenshots/result_page_1.png" width="800">
</p>

### Cluster Analysis & Visualization

<p align="center">
  <img src="screenshots/result_page_2.png" width="800">
</p>

---

# 🚀 Features

- Upload customer dataset (CSV file)
- Automatic data preprocessing
- Customer segmentation using K-Means algorithm
- Elbow Method visualization
- Cluster visualization using Pair Plot
- PCA (Principal Component Analysis) 2D & 3D visualization
- Customer distribution charts (Pie Chart & Bar Chart)
- Download clustered dataset with labels
- Simple and interactive web interface

---

# 🧠 Customer Segments Generated

The model divides customers into four groups:

- **Budget Shoppers** – Customers who prefer low-cost purchases  
- **High Spenders** – Customers with high spending behavior  
- **Occasional Buyers** – Customers who purchase rarely  
- **Loyal Customers** – Customers who frequently buy products  

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|--------|
| Python | Programming Language |
| Flask | Web Framework |
| Pandas | Data Processing |
| Scikit-learn | Machine Learning |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Tailwind CSS | Frontend Styling |

---

# 📂 Project Structure

```
Customer-Segmentation/
│
├── app.py
├── templates/
│   ├── index.html
│   └── result.html
│
├── static/
│   └── uploads/
│
├── dataset/
│   └── customers.csv
│
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/customer-segmentation.git
cd customer-segmentation
```

---

## 2️⃣ Install required libraries

```bash
pip install flask pandas matplotlib seaborn scikit-learn
```

---

## 3️⃣ Run the application

```bash
python app.py
```

---

## 4️⃣ Open the browser

```
http://127.0.0.1:5000/
```

---

# 📈 Output Visualizations

The system generates the following visualizations:

- **Elbow Method Plot** – Helps determine optimal number of clusters
- **Cluster Pair Plot** – Shows relationships between variables
- **PCA 2D Visualization** – Cluster separation in 2D
- **PCA 3D Visualization** – Cluster distribution in 3D
- **Customer Distribution Pie Chart**
- **Customer Count Bar Chart**

---

# 📥 Output File

After processing the dataset, the system generates a downloadable file:

```
clustered_customers_labeled.csv
```

This file includes:

- Original dataset
- Cluster number
- Customer segment label

---

# 📊 Machine Learning Workflow

1. Upload dataset  
2. Extract numerical features  
3. Standardize the data  
4. Apply K-Means clustering  
5. Evaluate clusters using Silhouette Score  
6. Visualize clusters using PCA and statistical plots  
7. Export labeled dataset  

---

# 🎯 Applications

This project can be used in:

- E-commerce customer analysis  
- Targeted marketing  
- Business intelligence systems  
- Customer behavior analysis  

---

# 👩‍💻 Author

**Bhoomi Singh**

Computer Science Student  
Interested in Data Science, AI, and Machine Learning  

---

# ⭐ Future Improvements

- Automatic cluster number selection  
- Interactive dashboard  
- Cloud deployment  
- Real-time analytics  
- Advanced visualizations using Plotly
