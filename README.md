Tracking Maternal Health Progress Toward SDG 3.1: A Global Data Analysis
->Problem Statement
Challenge:
The Sustainable Development Goal (SDG) 3.1 aims to reduce the global maternal mortality ratio (MMR) to less than 70 per 100,000 live births by 2030. Progress must be monitored using real country-wise data on:

->Maternal mortality ratio (MMR)

->Antenatal care coverage

->Births attended by skilled health personnel

->Health indicators and healthcare expenditures

Efforts to improve maternal health vary across regions and income groups, so it is important to analyze patterns and factors influencing MMR globally.

Dataset Used
->Source: SDG National Indicator Framework (Government of India)

->Link: Sustainable Development Goals National Indicator Framework (Version 3.1, 2021)

->Format: CSV

Technology and Tools
->IBM Cloud Lite (Mandatory)

->IBM Watson Studio (Jupyter Notebooks)

->Python (pandas, matplotlib, seaborn for data analysis and visualization)

Project Workflow
1. Set Up Environment
->Sign up at IBM Cloud

->Enable Watson Studio

->Create a new "Project" in Watson Studio (choose free Lite tier)

2. Upload Dataset
->Download required maternal health indicators CSV from the provided portal

->Go to "Assets" tab in your Watson Studio project and upload the CSV as a “Data Asset”

3. Data Analysis in Notebook
->Launch a new Jupyter Notebook in the project

->Code Sample:

python
import pandas as pd
data = pd.read_csv('/project_data/data_asset/your_file.csv')
data.head()
Explore and clean the data: filter for relevant columns (MMR, antenatal care, skilled attendance, etc.)

4. Visualization & Insights
->Trends: Plot changes in MMR over time and across regions/countries/states

->Comparisons: How do indicators like antenatal care relate to MMR?

->Disparities: Identify gaps between regions, urban/rural, income levels

5. Reporting
->Summarize your findings:

->Current progress toward SDG 3.1 targets

->Areas showing improvement

->Regions/groups needing urgent attention

->Factors most associated with better maternal outcomes

->Export your notebook and visualizations as a PDF or project archive

Project Structure (Example)
text
maternal-health-sdg3.1/
│
├── data/
│   └── maternal_health_data.csv
│
├── notebooks/
│   └── sdg3_1_analysis.ipynb
│
├── output/
│   └── charts_and_figures/
│
└── README.md
Notes
->Important: Use IBM Cloud Lite and Watson Studio as per the challenge requirement.

->Tip: Keep your code well-commented and your analysis easy to understand.

->Use clear graphs to help explain your findings.

Credits
->Problem Statement & Challenge: Edunet Foundation, SDG Academia

->Dataset: Government of India, SDG Portal, WHO (if needed)

->Cloud Platform: IBM Cloud Lite

