# 🏥 Hospital Management System — Power BI Dashboard

An interactive Power BI dashboard analyzing 10,000 hospital patient records — covering patient demographics, doctor/department workload, billing, insurance, and disease trends — built to give hospital administrators a quick, visual view of operations and revenue.

## 📊 Overview

The dashboard is built on a single fact table (`Hospital_Management_10k_Records`) sourced from a CSV file via Power Query, containing 10,000 rows and 35 columns spanning patient info, admission/discharge details, treatment, billing, and feedback.

## 📄 Report Pages

| Page | Description |
|------|-------------|
| **Home** | Landing page with navigation button into the main dashboard |
| **Hospital Management System** | Main analytics dashboard with KPI cards, charts, and filters |

## 📈 Key Visuals

**KPI Cards**
- Total Patients
- Average Age
- Total Doctors
- Total Bill Amount
- Amount Paid
- Amount Pending

**Charts**
- **Doctor by Specialization** (Column Chart) — doctor count across specializations
- **Total Bill Amount by Payment Mode** (Donut Chart) — revenue split across UPI, Card, Cash, Insurance
- **Disease by Patients** (Line Chart) — patient count trend across diagnosed diseases
- **State by Amount Pending / Received / Total** (Ribbon Chart) — billing breakdown by state

**Slicers (Filters)**
- Doctor Name
- State
- City
- Disease
- Registration Date

## 🗂️ Data Fields

The underlying table includes: Patient ID, Name, Age, Gender, Contact & Address, Registration Date, Doctor ID/Name/Specialization/Department, Consultation Fee, Admission/Discharge Dates, Room Type/Number/Bed, Admission Reason, Diagnosis, Treatment Given, Surgery details, Follow-Up Date, Total Bill Amount, Amount Paid, Pending Amount, Payment Mode, Billing Date, Insurance Provider, Feedback Rating, and Disease.

## 🛠️ Tools Used

- **Power BI Desktop** — data modeling, DAX, visualization
- **Power Query** — data import and transformation from CSV

## 🚀 How to Use

1. Clone/download this repository
2. Open `Hospital_Managment_System.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Use the slicers (Doctor, State, City, Disease, Registration Date) to filter the dashboard
4. Navigate between the Home and Dashboard pages using the in-report navigation button

## 📌 Notes

- All patient data in this project is synthetic/sample data generated for demonstration purposes only.
- No real patient information is used.

## 📬 Contact

Feel free to reach out for feedback or collaboration.
