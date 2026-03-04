# Traffic Accident Data Analysis using Python and SQL

This project analyzes road traffic accident data in Great Britain to identify patterns related to accident frequency, severity, and contributing factors.

The goal of the study is to explore accident trends across time, location, and vehicle type using data analytics, machine learning, and network analysis techniques.

---

## Project Overview

Road traffic accidents are a major public safety concern. Data-driven analysis can help identify risk factors and inform better road safety policies.

This project uses accident data to analyze:

- Temporal accident patterns
- Motorcycle accident trends
- Pedestrian accident risk
- Accident severity factors
- Regional accident clusters
- Time-series accident forecasting

The results provide insights that can help improve traffic safety and resource allocation.

---

## Dataset

Dataset used:

UK Road Traffic Accident Data (2020)

The dataset contains information about:

- Accident locations
- Vehicle types
- Casualty information
- Weather conditions
- Road characteristics
- Accident severity

Multiple database tables were merged for analysis.

---

## Data Processing

Data was extracted from a **SQLite database** and processed using Python.

Key steps included:

- Database connection and SQL querying
- Data cleaning and preprocessing
- Table merging
- Feature extraction

---

## Analysis Tasks

The project performs several analytical tasks.

### 1. Accident Frequency Analysis

Identifies the most common accident times.

Findings:
- Highest accident frequency during **rush hours**
- Peaks around **8–9 AM** and **5–6 PM**

---

### 2. Motorcycle Accident Analysis

Motorcycle accidents were analyzed by engine capacity.

Categories examined:

- Under 125cc
- 125cc–500cc
- Above 500cc

Patterns show increased accident rates during evening and weekend periods.

---

### 3. Pedestrian Accident Analysis

Pedestrian accident patterns were analyzed based on:

- Time of day
- Day of week
- Light conditions

Peak pedestrian accidents occur during commuting hours.

---

### 4. Accident Severity Analysis

Association rule mining was used to analyze factors related to severe accidents.

Key factors:

- Poor weather conditions
- High-speed zones
- Night-time driving

---

### 5. Geographic Clustering

Clustering techniques were applied to identify accident hotspots in **Kingston upon Hull**.

These clusters highlight areas with higher accident density.

---

### 6. Time-Series Forecasting

Machine learning models were used to predict future accident counts.

Models used:

- Linear Regression
- K-Nearest Neighbors (KNN)

Forecasting helps identify potential future accident trends.

---

### 7. Social Network Analysis

A network graph was constructed to analyze relationships between:

- Vehicles
- Casualties
- Accident events

Community detection algorithms were applied:

- Louvain algorithm
- Girvan-Newman algorithm

These techniques helped identify patterns within accident networks.

---

## Technologies Used

- Python
- SQL (SQLite)
- Pandas
- NumPy
- Scikit-learn
- NetworkX
- Matplotlib

---

## Project Structure

## Key Insights

- Accidents are most common during **rush hour traffic**
- Severe accidents correlate strongly with **weather conditions**
- Urban areas show higher accident density
- Machine learning models can help forecast accident trends

---

## Future Work

Future improvements could include:

- Using larger multi-year datasets
- Applying deep learning forecasting models
- Integrating GIS-based spatial analysis
- Developing real-time accident prediction systems
