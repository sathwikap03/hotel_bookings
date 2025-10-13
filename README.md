# 🏨 Hotel Booking Data Analysis

## 📋 Overview
This project focuses on analyzing hotel booking data to understand customer behavior, cancellation trends, and factors influencing hotel demand.  
The analysis was performed in **Python using Google Colab**, and the cleaned dataset (hotel_booking_data.csv) is included in this repository.

## 📂 Dataset
- **File:** _hotel_booking_data.csv
- **Source:** Hotel Booking Demand Dataset (open dataset)
- **Description:**  
  Contains detailed hotel reservation records, including:
  - Booking details (hotel type, arrival date, duration)  
  - Guest information (adults, children, babies)  
  - Reservation status (canceled or not)  
  - Market segment, distribution channel, country, and deposit type  
  - Customer stay and booking preferences  

## 🧰 Tools & Libraries Used
- Python 🐍  
- Google Colab  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

## 📊 Project Workflow
1. **Data Cleaning**
   - Removed missing and duplicate records  
   - Standardized column formats and data types  
   - Handled null values in fields like country and children

2. **Exploratory Data Analysis (EDA)**
   - Booking trends across different months and hotel types  
   - Analysis of cancellation rates and customer types  
   - Relationship between lead time, price, and cancellations  
   - Visualization of top market segments and booking channels  

3. **Key Insights**
   - **City Hotels** have higher bookings but also higher cancellation rates than **Resort Hotels**.  
   - Bookings with **longer lead times** are more likely to be canceled.  
   - **Online travel agents** dominate the distribution channels.  
   - **Portugal** contributes the most guests among all countries.

## ⚙️ How to Run
1. Open a new notebook in **Google Colab**.  
2. Uploadhotel_booking_data.csv to your Colab environment.  
3. Run all analysis cells step-by-step to reproduce visualizations and insights.

## 🚀 Future Improvements
- Build predictive models to forecast cancellations.  
- Create interactive dashboards using **Streamlit** or **Power BI**.  
- Cluster customer segments for personalized recommendations.

## 🧾 Results Summary
The analysis provides valuable insights for hotel managers and marketers to reduce cancellations, improve pricing strategies, and optimize guest experiences.

## 👩‍💻 Author
**Pudota Sathwika**  
📘 [GitHub Profile](https://github.com/sathwikap03)

