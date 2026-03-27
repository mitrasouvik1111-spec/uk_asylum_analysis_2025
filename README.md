# UK Asylum System Data Analysis (2010–2025)

## 📌 Project Overview
This project processes raw, publicly available OpenDocument Spreadsheets (`.ods`) published by the UK Home Office to analyze the reality of the UK asylum pipeline. Moving beyond political rhetoric, this analysis uses Python to visualize volume trends, identify demographic shifts, track route-of-entry behaviors, and assess judicial appeal outcomes.

## 🛠️ Tools & Technologies Used
* **Python 3.x**
* **Pandas:** Used for complex data extraction, standardizing headers, and handling merged metadata rows.
* **Matplotlib:** Generated dual-axis tracking of the processing backlog and operational support costs.
* **Plotly:** Engineered an interactive Sankey Diagram mapping the legal pipeline of asylum appeals.

## 📊 Key Findings
1. **The Processing Gap:** While applications surged post-2021, a significant processing bottleneck occurred, drastically increasing the logistical requirement for Section 95 government support and emergency accommodation.
2. **The Justice Funnel:** Judicial review serves as a major check on the system. Data from the most recently completed full year shows that over **52%** of initial Home Office refusals that go to court are successfully overturned by a judge.

## 🚀 How to Run Locally
1. Clone the repository: `git clone https://github.com/[Your-Username]/uk-asylum-analysis.git`
2. Ensure you have the required libraries installed: `pip install pandas numpy matplotlib plotly odfpy`
3. Open the `.ipynb` notebook in Jupyter or Google Colab and execute the cells. (Ensure the `.ods` file remains in the root directory).
