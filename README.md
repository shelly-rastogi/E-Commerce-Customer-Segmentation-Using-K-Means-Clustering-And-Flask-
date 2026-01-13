# E-Commerce Customer Segmentation using K-Means Clustering and Flask

## 📌 Project Overview
This project focuses on segmenting e-commerce customers using **K-Means clustering**, a popular unsupervised machine learning algorithm.  
Customer segmentation helps businesses understand purchasing behavior, improve marketing strategies, and increase customer retention.

The trained model is deployed using **Flask**, allowing users to interact with the segmentation system through a web interface.

---

## 🎯 Objectives
- Analyze customer purchase behavior
- Group customers into meaningful segments using K-Means clustering
- Visualize customer segments
- Deploy the machine learning model using Flask
- Provide an easy-to-use web interface for predictions

---

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Machine Learning:** K-Means Clustering (Scikit-learn)  
- **Web Framework:** Flask  
- **Data Handling:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Frontend:** HTML, CSS  
- **Deployment:** Flask Local Server  

---

## 📂 Project Structure
ecommerce-customer-segmentation/
│
├── static/
│   └── css/
│       └── style.css
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── model/
│   └── kmeans_model.pkl
│
├── dataset/
│   └── ecommerce_customers.csv
│
├── app.py
├── train_model.py
├── requirements.txt
└── README.md

---

## 📊 Dataset Description
The dataset contains customer-related attributes such as:
- Customer ID
- Annual Income
- Spending Score
- Purchase Frequency
- Total Amount Spent

These features are used to cluster customers into different segments.

---

## ⚙️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ecommerce-customer-segmentation.git



Navigate to the project directory:
cd ecommerce-customer-segmentation



Install required dependencies:
pip install -r requirements.txt




▶️ How to Run the Project


Train the K-Means model:
python train_model.py



Start the Flask application:
python app.py



Open your browser and go to:
http://127.0.0.1:5000/




📈 Model Description


Algorithm: K-Means Clustering


Number of Clusters: Determined using the Elbow Method


Distance Metric: Euclidean Distance


The model groups customers into clusters such as:


High-value customers


Medium-value customers


Low-value customers



🌐 Web Application Features


User-friendly input form


Real-time customer segment prediction


Cluster visualization


Lightweight and fast Flask backend



🚀 Future Enhancements


Use advanced clustering algorithms (DBSCAN, Hierarchical Clustering)


Add user authentication


Deploy on cloud platforms (AWS, Heroku)


Integrate real-time customer data


Improve UI with React or Bootstrap



📚 References


Scikit-learn Documentation


Flask Official Documentation


Machine Learning by Tom Mitchell


Kaggle E-Commerce Datasets




