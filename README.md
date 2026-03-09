# 📱 PhonePe Pulse Data Analysis

A comprehensive data analysis project on PhonePe's digital payment platform covering **300,000 transactions** across **107,658 users** and 6 service categories — built using **Power BI** and **Python**.

---

## 📁 Project Files

> The dataset and Power BI dashboard files are large in size and hosted on Google Drive.

🔗 **[Click here to access all project files](https://drive.google.com/drive/folders/1f7p5rurfyUB7ncjG7CdoRLyxIRh5LxX_?usp=sharing)**

Files included:
- `Phonepe-Final-Dataset.xlsx` — Raw dataset with 6 sheets
- `PhonePe.pbix` — Interactive Power BI Dashboard

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy) | Data loading, cleaning & aggregation |
| Matplotlib & Seaborn | Data visualization (10 charts) |
| Power BI | Interactive 5-page dashboard |
| Microsoft Excel | Source dataset |
| Jupyter Notebook | EDA development environment |

---

## 📊 Dataset Overview

| Table | Rows | Description |
|-------|------|-------------|
| All_Users | 107,658 | User demographics and join dates |
| All_Transactions | 300,000 | Platform-wide transaction records |
| Recharge_Bills | 50,000 | Mobile, DTH, Electricity, Cable TV |
| Money_Transfer | 150,000 | UPI, QR Code, Mobile, Self transfers |
| Loans | 50,000 | Auto, Gold, Mutual Fund, Credit Score |
| Insurance | 50,000 | Health, Car, Bike, Term Life |

---

## 🔍 Key Findings

- ✅ **96% transaction success rate** across 300,000 transactions
- 🏆 **Loans** is the top revenue service with **$2.5B** total loan amount
- 🏦 **Auto Loan** is the most popular loan type
- 📱 **Electricity Bill** is the highest revenue recharge category
- 💸 **UPI ID** is the most used money transfer method
- ⚠️ Failure reasons: Wrong PIN, Insufficient Amount, Server Error
- 👤 Average user age: **39 years** (range: 18–60)

---

## 📈 Python EDA — Visualizations Generated

1. User Distribution by Age Group
2. Monthly User Signups Trend
3. Revenue by Service Category
4. Payment Status Breakdown (Pie Chart)
5. Revenue by Recharge & Bill Type
6. Money Transfer Type Distribution
7. Average Loan Amount by Loan Type
8. Loan Amount Distribution (Histogram)
9. Total Premium by Insurance Type
10. Monthly Revenue Trend — All Services Combined

---

## 💡 Power BI Dashboard Pages

1. **Home** — Overall KPIs and platform summary
2. **Insurance** — Premium analysis by type and trend
3. **Loans** — Loan amount breakdown and type comparison
4. **Money Transfer** — Transfer methods and volume
5. **Recharges & Bills** — Category-wise revenue split

---

## 🚀 How to Run the Python EDA

1. Clone this repository
```bash
git clone https://github.com/skshmdudeja/PhonePe-Data-Analysis.git
cd PhonePe-Data-Analysis
```

2. Install required libraries
```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

3. Download the dataset from the [Google Drive link](https://drive.google.com/drive/folders/1f7p5rurfyUB7ncjG7CdoRLyxIRh5LxX_?usp=sharing) and place it in the project folder

4. Run the notebook
```bash
jupyter notebook PhonePe_EDA.ipynb
```

---

## 👤 Author

**Saksham Dudeja**
- 📧 sdudeja60@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/saksham-dudeja/)
- 🐙 [GitHub](https://github.com/skshmdudeja)
