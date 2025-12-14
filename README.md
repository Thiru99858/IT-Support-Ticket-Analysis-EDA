# IT Support Ticket Analysis – EDA 📊

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on IT support ticket data to identify patterns in ticket volume, issue categories, priority levels, resolution time, agent performance, and customer satisfaction.  
The analysis uses **Python, Pandas, Matplotlib, and Seaborn** to convert raw ticket data into meaningful operational insights.

---

## 🎯 Objectives
- Analyze monthly ticket trends  
- Identify the most frequent ticket categories  
- Understand priority-wise ticket distribution  
- Measure average resolution time by priority and agent  
- Study the relationship between resolution time and customer ratings  
- Quantify correlations using a heatmap  

---

## 🗂 Dataset Description
The dataset includes the following fields:

- `Ticket_ID` – Unique ticket identifier  
- `Created_Date` – Ticket creation date  
- `Resolved_Date` – Ticket resolution date  
- `Category` – Type of issue (Login Issue, Payment Issue, etc.)  
- `Priority` – Ticket urgency (High, Medium, Low)  
- `Agent` – Support agent handling the ticket  
- `Resolution_Time_Hours` – Time taken to resolve the ticket  
- `Customer_Rating` – Customer satisfaction score (1–5)  

---

## 📊 Analysis & Visualizations

### 1️⃣ Monthly Ticket Trend
- Line plot showing number of tickets created per month  
- Helps understand ticket inflow patterns over time  

### 2️⃣ Ticket Category Analysis
- Count plot to identify the most common issue categories  
- Highlights areas requiring system or process improvements  

### 3️⃣ Priority-wise Ticket Distribution
- Count plot showing ticket distribution across priority levels  
- Indicates workload distribution by urgency  

### 4️⃣ Average Resolution Time by Priority
- Bar plot comparing average resolution time for each priority level  
- Helps evaluate SLA performance  

### 5️⃣ Agent Performance Analysis
- Bar plot showing average resolution time per support agent  
- Identifies high-performing and improvement areas  

### 6️⃣ Resolution Time vs Customer Rating
- Scatter plot revealing a negative relationship between resolution time and customer satisfaction  

### 7️⃣ Correlation Heatmap
- Heatmap quantifying the relationship between resolution time and customer ratings  
- Confirms faster resolutions lead to higher satisfaction  

---

## 🔍 Key Insights
- Ticket volume is evenly distributed across priority levels  
- Certain issue categories generate more tickets than others  
- High-priority tickets tend to have longer resolution times  
- Agent performance varies in average resolution speed  
- Faster ticket resolution strongly correlates with higher customer ratings  

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🚀 How to Run the Project
1. Clone the repository  
2. Open the Jupyter Notebook  
3. Run all cells sequentially  

---

## 👤 Author
**B. Thirupal (Thiru)**  
Junior Data Analyst  
Skilled in Python, SQL, Power BI, and Data Visualization  

---

## ⭐ Final Note
This project demonstrates practical EDA skills and the ability to derive actionable business insights from operational data using visualization techniques.

Feel free to explore, fork, or provide feedback!
