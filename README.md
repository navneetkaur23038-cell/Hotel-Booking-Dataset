# Hotel-Booking-Dataset
End-to-end Exploratory Data Analysis of a hotel booking dataset using Python, Pandas, Matplotlib, and Seaborn, covering data cleaning, outlier detection, statistical analysis, visualization, business insights, and management recommendations. 

# 🏨 Hotel Booking Data Analysis — EDA

## 📌 Project Overview

This project performs a complete **Exploratory Data Analysis (EDA)** on a large hotel booking dataset using Python. The analysis follows an end-to-end data science workflow, starting with data understanding and quality assessment and progressing through data cleaning, preprocessing, statistical analysis, visualization, and business recommendations.

The goal is to identify important patterns related to **hotel bookings, cancellations, customer behavior, pricing, lead time, market segments, revenue, and hotel performance**.

---

## 🎯 Objectives

* Understand the structure and characteristics of the dataset
* Identify and handle missing values
* Detect and remove duplicate records
* Identify incorrect data types and inconsistent categorical values
* Detect potential outliers using the IQR method
* Perform descriptive statistical analysis
* Conduct univariate and bivariate analysis
* Perform group-wise analysis
* Analyze correlations between numerical variables
* Create meaningful visualizations
* Extract actionable business insights
* Provide practical recommendations for hotel management

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook / Google Colab**
* **ReportLab** – Executive report generation

---

## 📊 Analysis Workflow

### 1. Data Loading & Understanding

* Imported the hotel booking dataset
* Examined dataset dimensions
* Inspected columns and data types
* Reviewed descriptive statistics

### 2. Data Quality Assessment

* Checked missing values
* Identified duplicate records
* Checked duplicate Booking IDs
* Investigated inconsistent categorical values
* Validated date fields
* Checked numerical ranges

### 3. Data Cleaning & Preprocessing

* Removed duplicate records
* Standardized categorical values
* Handled missing values
* Converted date columns to datetime
* Created missing-value categories for identifier fields
* Validated satisfaction scores
* Flagged logically inconsistent dates

### 4. Feature Engineering

Additional analytical features were created, including:

* Booking Year
* Booking Month
* Arrival Year
* Arrival Month
* Arrival Weekday
* Party Size
* Revenue per Night
* Lead-Time Bands
* Stay-Type Categories

### 5. Exploratory Data Analysis

The project includes:

* Univariate analysis
* Bivariate analysis
* Group-wise analysis
* Revenue analysis
* Cancellation analysis
* Hotel-type comparison
* Market-segment analysis
* Destination analysis
* Pricing analysis
* Correlation analysis

---

## 📈 Visualizations

The analysis uses **Matplotlib and Seaborn** to create visualizations such as:

* Histograms
* Bar charts
* Count plots
* Scatter plots
* Line charts
* Box plots
* Correlation heatmaps
* Revenue distribution charts
* Cancellation-rate comparisons

---

## 🔍 Key Business Insights

### 1. High Cancellation Risk

The dataset shows a very high overall cancellation rate, making cancellation management one of the most important commercial priorities.

### 2. Deposit Policy and Cancellation

Bookings associated with non-refundable deposit arrangements show particularly high cancellation behavior, indicating that payment and commitment policies require further investigation.

### 3. Lead Time Matters

Long-lead bookings are considerably more cancellation-prone than bookings made closer to the arrival date.

### 4. Resort Hotels Generate Stronger Booking Value

Resort properties demonstrate stronger booking economics through higher ADR and longer average stays.

### 5. Online Travel Agencies Are Important but Risky

Online TA represents a major revenue-generating market segment but also requires careful management of cancellation policies, inventory, and payment guarantees.

---

## 💡 Management Recommendations

1. Implement a **cancellation-risk scoring system** to identify high-risk bookings.
2. Introduce stronger commitment mechanisms for high-risk long-lead reservations.
3. Review **Online TA cancellation policies, commissions, and payment guarantees**.
4. Optimize pricing and inventory for high-value resort properties.
5. Monitor destinations using a combination of **bookings, ADR, revenue, and cancellation rate**.
6. Develop extended-stay packages and upselling strategies to increase booking value.
7. Improve data-quality controls for booking IDs, dates, categories, and customer-related fields.

---

## 📂 Project Structure

```text
Hotel-Booking-EDA/
│
├── Hotel_Booking_Executive_EDA.ipynb
├── hotel_booking_cleaned.csv
├── Hotel_Booking_Executive_EDA_Report.pdf
├── README.md
└── visualizations/
    ├── revenue_by_hotel.png
    ├── cancellation_by_deposit.png
    ├── cancellation_by_lead_time.png
    ├── revenue_by_segment.png
    ├── revenue_by_location.png
    ├── revenue_distribution.png
    ├── adr_vs_nights.png
    ├── correlation_heatmap.png
    └── monthly_revenue.png
```

---

## 🚀 How to Run

### Google Colab

1. Open the `.ipynb` file in Google Colab.
2. Upload the original hotel booking CSV dataset.
3. Update the dataset path if required.
4. Run the notebook cells sequentially.
5. Review the analysis, visualizations, insights, and recommendations.

### Jupyter Notebook

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Then start Jupyter:

```bash
jupyter notebook
```

Open:

```text
Hotel_Booking_Executive_EDA.ipynb
```

and run the cells.

---

## 📌 Dataset

The project uses a hotel booking dataset containing information about:

* Hotel type
* Booking and arrival dates
* Lead time
* Stay duration
* Customer details
* Market segment
* Distribution channel
* Deposit type
* ADR
* Special requests
* Satisfaction score
* Cancellation status
* Estimated revenue

---

## 📊 Project Outcome

This project demonstrates practical skills in:

**Data Cleaning → Data Preprocessing → Exploratory Data Analysis → Data Visualization → Statistical Analysis → Business Insights → Decision Making**

It can serve as a portfolio project demonstrating **Python, Pandas, data visualization, EDA, and business analytics skills**.

---

If you found this project useful, consider ⭐ starring the repository!
