# 🚖 Ola Cabs Data Analysis – Power BI Dashboard

## 📊 Project Overview

This Power BI project explores ride booking data from Ola Cabs to extract actionable business insights. It covers various aspects like ride volumes, booking statuses, cancellations, customer satisfaction, payment methods, and more.

The dashboard provides stakeholders with a clear view of trends and operational efficiency, helping in data-driven decision-making.


## 🗂️ Dataset Highlights

The dataset used in this project contains the following key fields:

- `Booking_ID`
- `Booking_Status`
- `Booking_Value`
- `Canceled_Rides_by_Customer`
- `Canceled_Rides_by_Driver`
- `Customer_Rating`
- `Ride_Distance`
- `Incomplete_Rides` & `Incomplete_Rides_Reason`
- `Payment_Method`
- `Pickup_Location` & `Drop_Location`
- `Date` and `Time`



## 📌 Key Features & Metrics

### ✔️ KPIs Used:
- **Total Bookings**
- **Cancelled Bookings**
- **Cancelled Booking %**
- **Average Customer Rating**
- **Total Booking Value**
- **Ride Distance Trends**

### 🧠 DAX Measures:

DAX
Cancelled Booking % = 
DIVIDE(
    CALCULATE(COUNTROWS('July'), 'July'[Booking_Status] = "Cancelled"),
    COUNTROWS('July'),
    0
)


## 📈 Dashboard Insights

- Identify peak and off-peak booking periods
- Analyze reasons behind ride cancellations (by driver or customer)
- Understand customer satisfaction via ratings
- Observe ride distance and payment method patterns
- Filter by date, payment mode, and booking status


## 🛠️ Tools Used

- **Microsoft Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query (ETL & Data Cleaning)**
- **Data Modeling**

## 🚀 How to Use

1. Clone the repository:
  
   git clone https://github.com/Rupesh-kharat/ola-cabs-powerbi-dashboard.git
   
2. Open `Ola Project.pbix` in **Power BI Desktop**
3. Interact with the visuals using built-in filters and slicers


## 📚 Learning Outcomes

- Developed custom DAX measures for key business metrics
- Designed interactive, user-friendly Power BI dashboards
- Explored trends in booking behavior and ride cancellations
- Presented business insights through clean, visual storytelling


## 📩 Contact

Have feedback or want to collaborate? Reach out:

- 📧 Email:rupeshkharat17@gmail.com
- 💼 [LinkedIn]https://www.linkedin.com/in/rupesh-kharat/
- 🌐 [github]https://github.com/Rupesh-kharat


