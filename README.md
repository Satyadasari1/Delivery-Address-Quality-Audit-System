# 🧭 Delivery Address Quality Audit System

A realistic, beginner-friendly project designed to simulate the kind of address auditing work performed by Amazon’s Last Mile Analytics & Quality (LMAQ) team. This project demonstrates my ability to follow SOPs, identify data quality issues, and improve logistics accuracy using real-world tools and manual processes.

---

## 🔍 Project Objective

To analyze a set of delivery addresses, manually verify their accuracy using Google Maps, classify common issues (such as incorrect PIN codes or missing landmarks), and create a summary report to highlight data quality and provide actionable insights.

---

## 📁 Folder Structure

Delivery-Address-Audit-System/
├── address_data.csv # Sample delivery address dataset
├── audit_report.xlsx # Address audit results with classification and summary dashboard
├── screenshots/ # Screenshots of Google Maps verifications
│ └── sample_map_check.png
├── scripts/ # (Optional) Python scripts for data cleaning
│ └── address_cleaner.py
└── README.md # Project documentation (this file)

## 📊 Dataset Overview

The dataset contains sample delivery addresses with fields:
- `OrderID`
- `Customer Name`
- `Address`
- `City`
- `PINCode`
- `Landmark`

A total of 50–100 dummy addresses are verified manually through Google Maps for:
- Address completeness
- Correctness of PIN code and city
- Landmark clarity

---

## ✅ Audit Process

Each address is manually reviewed using Google Maps:

1. Copy the full address into Google Maps.
2. Check if the PIN code and city match the location.
3. Identify if the landmark is helpful and correct.
4. Tag each address as:
   - ✅ `Correct`
   - ⚠️ `Partially Incorrect`
   - ❌ `Invalid`

---

## 🧠 Error Types Identified

| Error Type           | Description                                  |
|----------------------|----------------------------------------------|
| Missing Landmark     | No clear location markers (e.g., 'Near ATM') |
| Wrong PIN Code       | PIN does not match actual area               |
| Ambiguous Address    | Multiple results or unclear instructions     |
| Incomplete Address   | Missing house/street/locality info           |

---

## 📈 Dashboard & Report

The results are recorded in an Excel dashboard (`audit_report.xlsx`) including:
- Total addresses audited
- Error percentage
- Bar chart of error types
- Suggested improvements (dropdown validation, PIN check, etc.)

---

## 💻 Tools Used

- **Google Sheets / Excel**: Data organization, tagging, dashboard
- **Google Maps**: Manual verification
- *(Optional)* **Python (Pandas)**: Data cleanup or address formatting
- **GitHub**: Version control and project showcasing

---

## 🎓 Skills Demonstrated

- SOP-based manual auditing
- Attention to detail
- Geolocation and mapping awareness
- Excel dashboard reporting
- Root cause analysis of errors
- Communication of process improvements

---

## 🧠 Skills Used

<p align="left">
  <img src="https://img.shields.io/badge/-Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/-Google%20Maps-4285F4?style=for-the-badge&logo=google-maps&logoColor=white" />
  <img src="https://img.shields.io/badge/-Manual%20Testing-F9A825?style=for-the-badge&logo=testing-library&logoColor=white" />
  <img src="https://img.shields.io/badge/-Data%20Cleaning-4CAF50?style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Process%20Improvement-FF5722?style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Attention%20to%20Detail-9C27B0?style=for-the-badge" />
</p>

---

## 📌 Future Improvements

- Integrate with Google Maps API for automatic geocoding (Python)
- Automate error detection using logic rules
- Extend dataset with 500+ entries

---

## 🧑‍💼 About Me

I'm currently preparing for a Quality Associate role at Amazon and created this project to demonstrate my operational thinking, detail orientation, and willingness to learn. My background includes certifications in customer support, communication, and digital collaboration.

---

## 📬 Contact

I'm currently preparing for a Quality Associate role at Amazon and created this project to demonstrate my operational thinking, detail orientation, and willingness to learn.  
🔗 [LinkedIn](https://linkedin.com/in/yourprofile)  
📁 [GitHub Profile](https://github.com/yourusername)
