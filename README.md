# Innomatics Research Labs – Advanced GenAI Internship Entrance Test

## 📌 Project Overview
This repository contains my submission for the **Innomatics Research Labs – Advanced GenAI Internship Entrance Test**.  
The task simulates a real-world data engineering and analysis workflow involving multiple data sources and formats.

All analysis was performed using **Python and Pandas in Google Colab**.

---

## 📂 Datasets Used
Three datasets were provided in different formats to represent real-world systems:

- **orders.csv** – Transactional order data  
- **users.json** – User master data (user details and membership type)  
- **restaurants.sql** – Restaurant master data (restaurant details, cuisine, ratings)

These datasets were merged into a single final dataset:

- **final_food_delivery_dataset.csv**

> This final dataset is the **only source of truth** for all questions and analysis.

---

## 🔗 Data Integration Process
The datasets were combined using **Left Joins** to ensure all order records were retained:

- `orders.user_id` → `users.user_id`
- `orders.restaurant_id` → `restaurants.restaurant_id`

---

## 📊 Analysis Performed
Using **Pandas**, the notebook answers:
- Fill-in-the-blank questions
- Numerical questions
- Multiple-choice questions (MCQs)

Key analysis areas include:
- Gold vs Regular membership impact
- City-wise and cuisine-wise revenue analysis
- Average Order Value (AOV)
- User spending behavior
- Restaurant performance by rating and cuisine
- Quarter-wise revenue trends

---

## 📁 Repository Structure
- `food_delivery_analysis.ipynb` – Colab Notebook containing the complete analysis (created using Google Colab)
- `final_food_delivery_dataset.csv` – Final merged dataset
- `orders.csv` – Raw orders data
- `users.json` – Raw user data
- `restaurants.sql` – Raw restaurant data
- `README.md` – Project documentation 

---

## 🛠 Tools & Technologies
- Python
- Pandas
- Google Colab

---

## ✅ Submission Notes
- All results are generated programmatically using Pandas  
- No hard-coded values are used  
- Outputs are visible and reproducible  
- Notebook is directly accessible via GitHub

---

## 👩‍💻 Author
**Varshini Anupolu**  
GitHub: https://github.com/AVarshini05
