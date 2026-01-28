# 🏨 Hotel Booking Demand - Exploratory Data Analysis (EDA)
### Data-Driven Insights into Guest Behavior (Python | Pandas | Seaborn)

## 📌 Introduction
In the hotel industry, understanding customer behavior is a key factor for success. Booking cancellations directly impact revenue management and room occupancy planning. This project performs a deep dive into a hotel booking dataset to uncover the patterns and factors that influence a guest's decision to stay or cancel.

## 🎯 Project Objectives
* **Exploration:** Analyze the differences between City Hotels and Resort Hotels.
* **Analysis:** Identify key variables (Lead Time, Deposit Type, Special Requests) that correlate with cancellations.
* **Feature Engineering:** Create new metrics like `total_stay` and `is_local` to gain deeper behavioral insights.
* **Actionable Insights:** Provide data-driven recommendations for hotel management to optimize booking stability.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

## 📊 Dataset Overview
* **Size:** Approximately 119,000 booking records.
* **Features:** 32 variables including customer demographics, length of stay, and booking channels.
* **Preprocessing:** Data has been cleaned, missing values handled, and new features engineered for better analysis.

---

## 💡 Key Insights & Conclusion

### ⏳ Lead Time Sensitivity
There is a clear positive correlation (~0.29) between **lead time** and cancellations. The earlier a guest books, the higher the risk of them canceling. Management should consider stricter policies for long-term bookings.

### 🎯 Commitment Signals
* **Parking:** Guests who request a parking space have a **nearly 0% cancellation rate**.
* **Special Requests:** As the number of special requests increases, the cancellation rate decreases. Engaged customers are more likely to arrive.

### 🌍 Local vs. International Market
Local guests show different cancellation patterns than international tourists. This insight allows for region-specific marketing and cancellation strategies.

### 💰 Pricing & Deposits (The Deposit Paradox)
* **ADR (Average Daily Rate):** Higher ADR is slightly more common in canceled bookings, suggesting price sensitivity.
* **Non-Refund Paradox:** 'Non-Refund' deposit types showed a high cancellation rate in this specific dataset, indicating these bookings might belong to higher-risk segments.

---

## 📂 Project Structure
* 📄 `Hotel_Booking_Demand_EDA.ipynb`: Python notebook containing data cleaning, visualization, and analysis.
* 📄 `hotel_bookings.csv`: The raw dataset used for analysis.
* 🖼️ `visuals/`: Saved charts and plots (Correlation heatmaps, distribution plots).

---

## 📜 License
This project is licensed under the **MIT License** — feel free to fork, star, and use it in your portfolio!
