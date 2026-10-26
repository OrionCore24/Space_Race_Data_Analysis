# 🚀 Space Missions Analysis

An exploratory data analysis (EDA) project that investigates historical space missions using Python. This project explores launch trends, mission success rates, launch costs, and the competition between the United States and the Soviet Union during the Cold War.

## 📌 Project Overview

The project uses historical space mission data scraped from [Next Spaceflight](https://nextspaceflight.com/launches/past/?page=1). Using Python and data visualization libraries, the dataset is cleaned, analyzed, and visualized to uncover patterns in the history of space exploration.

The analysis covers space missions from the beginning of the Space Race in 1957 and explores trends across different organizations, countries, and time periods.

## 🎯 Objectives

- Explore historical space mission data.
- Clean and prepare the dataset for analysis.
- Identify organizations with the highest number of launches.
- Compare active and retired rocket statuses.
- Analyze mission success and failure rates.
- Investigate launch costs across organizations and years.
- Visualize launch activity and failures by country.
- Explore the historical space race between the USA and the USSR.

## 🛠️ Tools & Technologies

- **Python** — Data analysis and manipulation.
- **Pandas** — Data cleaning, transformation, and aggregation.
- **NumPy** — Numerical operations.
- **Plotly Express** — Interactive data visualizations.
- **Matplotlib** — Data visualization.
- **Seaborn** — Statistical data visualization tools.
- **ISO 3166** — Country name and country code handling.

## 📊 Analysis & Visualizations

### 1. Data Exploration and Cleaning
- Inspect dataset dimensions and column names.
- Identify missing values and duplicate records.
- Remove unnecessary index columns.
- Convert launch prices into numeric values.
- Remove duplicate records after cleaning.

### 2. Launch Activity by Organization
- Compare the total number of launches across organizations.
- Identify organizations with the most launches.
- Explore how launch activity has changed over time.

### 3. Rocket and Mission Status
- Compare active and retired rockets.
- Visualize the distribution of mission statuses.
- Examine successful launches alongside failures, partial failures, and prelaunch failures.

### 4. Launch Costs
- Explore the distribution of launch prices.
- Compare total launch expenditure by organization.
- Analyze average spending per launch.
- Investigate changes in average launch prices over time.

*Launch prices are analyzed in USD millions, and records without known prices are excluded from price-based calculations.*

### 5. Geographic Analysis
- Visualize launch counts by country using choropleth maps.
- Compare the number of unsuccessful missions across countries.
- Explore the relationship between countries, organizations, and mission statuses using a sunburst chart.

### 6. Launch Trends Over Time
- Analyze annual launch counts.
- Explore monthly launch activity and rolling averages.
- Identify the months with the highest launch activity.
- Compare launch activity across the top 10 organizations.

### 7. The Cold War Space Race
- Compare launch activity between the USA and USSR through 1991.
- Analyze year-by-year launch counts and mission failures.
- Examine failure rates over time.
- Compare cumulative launch leadership, including successful launches, through 2020.

## 📁 Project Structure

```text
Space_Missions_Analysis/
│
├── Space_Missions_Analysis.ipynb
├── mission_launches.csv
├── requirements.txt
├── .gitignore
└── README.md
```

*The structure above is a recommendation. The notebook and dataset filenames may differ in your actual repository.*

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with your GitHub username and repository name.

### 2. Navigate to the Project Directory

```bash
cd YOUR-REPOSITORY
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 4. Install Dependencies

Create a `requirements.txt` file containing:

```text
numpy
pandas
plotly
matplotlib
seaborn
iso3166
jupyter
```

Then install the packages:

```bash
pip install -r requirements.txt
```

### 5. Prepare the Dataset

Place `mission_launches.csv` in the project directory.

Update the CSV file path in the notebook if necessary. The original notebook uses a local Windows file path, so it must be changed to a path that works on your computer.

For example:

```python
df_data = pd.read_csv("mission_launches.csv")
```

### 6. Run the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `Space_Missions_Analysis.ipynb` and run the cells sequentially.

## 📈 Expected Outcomes

This project aims to provide insights into:

- Which organizations have conducted the most space missions.
- How launch activity has evolved throughout history.
- How mission success and failure rates vary over time.
- How launch costs differ across organizations.
- Which countries have contributed most to space exploration.
- How the USA and USSR competed during the Cold War Space Race.

## 📚 Data Source

- [Next Spaceflight — Past Launches](https://nextspaceflight.com/launches/past/)

The dataset contains historical space mission information. The analysis depends on the records and fields available in the supplied CSV file.

## 👤 Author

**Your Name**

Aspiring Data Analyst | Python & Data Analytics

---

This project is part of my learning journey in data analytics, exploratory data analysis, and data visualization using Python.