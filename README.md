📊 Sales Analysis with Pandas and Matplotlib

This project aims to perform an exploratory and statistical analysis of a sales dataset using Python, Pandas, and Matplotlib.
You can access the complete notebook here:
👉 Exercise 3 – Sales Dataset: (add your Colab link or keep the current one)

📝 Project Description

The project consists of loading, cleaning, and analyzing a sales database.
The steps include data cleaning, consistency verification, grouping operations, statistical calculations, and graphical visualization.

🚀 Technologies Used

*  Python

*  Pandas

*  Matplotlib

*  Google Colab

*  Excel (data source)

🔍 Analysis Steps

1️⃣ Data Collection

The data was imported from an Excel file directly into the notebook.

2️⃣ Dataset Understanding

Several checks were performed on the dataset, such as:

*  Existence of null values

*  Duplicate detection

*  Data types of each column

*  Total row count

3️⃣ Data Cleaning

Null values were removed using dropna()

No duplicates were found

The cleaned results were stored in a new DataFrame named df_clean

4️⃣ Performed Analyses

4.1 🥇 Best-Selling Product

*  Grouped by product using groupby

*  Summed total quantities sold

*  Identified the top-selling product using idxmax()

*  Retrieved the sold quantity with loc

4.2 👤 Top Purchasing Customer

*  Same logic as product analysis

*  Grouped by customer and summed the purchased quantities

4.3 💰 Average Ticket

*  Grouped by product

*  Summed total revenue

*  Divided by total quantity sold to calculate the Average Ticket

4.4 📈 Monthly Sales Chart

*  Created using Matplotlib

*  Plotted total sales per month vs date
<br>
<img width="1292" height="703" alt="image" src="https://github.com/user-attachments/assets/39347803-f121-489b-914d-6c3135f93a00" />
<br>
<br>
<br>

▶️ How to Run the Project

Clone the repository:

*  git clone 

*  Open the notebook in Google Colab or locally.

*  Make sure you have the required libraries installed:

*  pip install pandas matplotlib

*  Import the Excel sales dataset and run the cells.

📌 Final Considerations

This project demonstrates essential skills in:
✔ Data cleaning
✔ Pandas manipulation
✔ Exploratory data analysis
✔ Data visualization
✔ Commercial metrics calculation

If you want to expand the project (dashboard, machine learning, SQL integration, etc.), I’d be happy to help!
