# climate-change-analysis
A project analyzing climate change using authentic datasets from NOAA and NASA.
Climate Change Analysis
A project analyzing climate change using authentic datasets from NOAA and NASA. This project aims to enhance understanding of climate change through data-driven activities and modeling.

Overview
This project contains Python-based analyses and visualizations to study various aspects of climate change. It includes four hands-on activities designed for students, researchers, and educators to explore climate trends, carbon emissions, and predictive modeling.

Activities
1. Exploring Global Temperature Trends
Objective: Analyze global temperature anomalies over time to identify climate patterns.
Dataset: NASA's GISTEMP global temperature anomaly data.
Output: Line charts showing annual and monthly temperature trends.
2. Visualizing Climate Trends with Heatmaps
Objective: Use heatmaps to visualize long-term temperature changes by year and season.
Dataset: Processed temperature anomaly data from NASA.
Output: Heatmaps highlighting seasonal variations and long-term warming trends.
3. Analyzing Carbon Emissions by Region
Objective: Compare global carbon emissions and examine disparities across regions.
Dataset: CO₂ emissions dataset from Our World in Data (OWID).
Output: Bar charts showing the top carbon-emitting countries/regions.
4. Modeling Future Climate Scenarios
Objective: Build a predictive model using historical CO₂ data to forecast future CO₂ concentration levels.
Dataset: NOAA's CO₂ monthly mean data.
Output: Linear regression projections of CO₂ levels up to 2100.
Key Features
Authentic datasets from:
NOAA Global Monitoring Laboratory
NASA GISTEMP
Comprehensive preprocessing to make datasets analysis-ready while preserving data integrity.
Step-by-step Python code with visual outputs for each activity.
Reproducible and well-documented workflow.
How to Use
Clone this repository:
bash
Copy
Edit
git clone git@github.com:Pongsophon/climate-change-analysis.git
cd climate-change-analysis
Install required Python libraries:
bash
Copy
Edit
pip install -r requirements.txt
Open and run the Climate_Change.ipynb notebook in Google Colab or Jupyter Notebook.
Repository Structure
bash
Copy
Edit
climate-change-analysis/
├── Climate_Change.ipynb         # Python code for all activities
├── README.md                    # Project documentation
├── Documentation.docx           # Detailed documentation of methods
├── Datasets/                    # Folder containing cleaned and raw datasets
│   ├── GLB.Ts+dSST.csv
│   ├── cleaned_co2_data.csv
│   ├── cleaned_co2_modeling_activity_4.csv
│   ├── cleaned_monthly_temperature_anomalies.csv
│   ├── cleaned_temperature_anomalies.csv
│   ├── co2_mm_mlo.csv
│   └── owid_co2_data.csv
Data Integrity
All datasets have been preprocessed to ensure they are ready for analysis. Preprocessing steps included:

Handling missing values
Aggregating or normalizing data where necessary
Documenting all changes in the Documentation.docx file
The preprocessing did not distort or modify the original data trends.

Contact
For questions or feedback, feel free to contact Pongsophon via GitHub.

