# 🛒 E-commerce Customer Segmentation (K-Means Clustering)

This project is a web-based customer segmentation application built using **Flask** and **Machine Learning (K-Means Clustering)**.

It segments e-commerce customers based on their purchasing behavior to help businesses understand customer patterns and design targeted marketing strategies.

The application analyzes customer attributes such as **Annual Income**, **Spending Score**, and **Shopping Frequency** to group customers into meaningful segments like **High Spenders**, **Budget Shoppers**, and **Standard Customers**.

## 📂 Project Structure


ecommerce-customer-segmentation-kmeans-flask/
│
├── app.py                           # Main Flask application
├── requirements.txt                 # Python dependencies
├── runtime.txt                      # Python version (3.10.13)
│
├── realistic_customers.csv          # Input dataset
├── sample_customers.csv             # Sample test data
├── clustered_customers_labeled.csv  # Output data with cluster labels
│
├── static/                          # CSS, JS, images
├── templates/                       # HTML templates
└── README.md                        # Project documentation 


## 🛠️ Tech Stack
Backend: Flask (Python)

## Machine Learning: Scikit-learn (K-Means Clustering)

## Data Processing: Pandas, NumPy

## Visualization: Matplotlib, Seaborn

## Frontend: HTML, CSS (Bootstrap)

## 🚀 Installation & Setup
Python Version Required: 3.10.13

## Using Conda is recommended to avoid dependency conflicts.

1️⃣ Clone the Repository
Bash
git clone <your-repo-url>
cd ecommerce-customer-segmentation-kmeans-flask

2️⃣ Create Conda Environment
Bash
conda create -n customer-segmentation python=3.10.13 -y
conda activate customer-segmentation

3️⃣ Install Dependencies
Bash
pip install -r requirements.txt

4️⃣ Run the Application
Bash
python app.py

5️⃣ Access the Web App
Open your browser and go to: http://127.0.0.1:5000

## 📊 How It Works
Data Ingestion: Customer data is loaded from realistic_customers.csv.

Preprocessing: Data is cleaned, transformed, and standardized.

Clustering: The K-Means algorithm segments customers using:

Annual Income (k$)

Spending Score (1–100)

Shopping Frequency

Labeling: Each cluster is assigned a human-readable label (e.g., Gold Customers, Budget Customers).

Visualization: The Flask web app displays the segmented data in a dashboard-style table.

## 🐛 Troubleshooting
Python version mismatch: Ensure the correct environment is activated:

## Bash
conda activate customer-segmentation
Table shows \n characters: Use df.to_html() in your code instead of rendering raw text lines.

Dependency installation issues on Windows: Prefer using conda install <package-name> instead of pip when build errors occur.

## 📜 License
This project is open-source and available under the MIT License.

## 👤 Author
Nishant Rakhecha Data Analytics | Machine Learning | Business Intelligence

GitHub Profile
https://github.com/rakhechanishant
