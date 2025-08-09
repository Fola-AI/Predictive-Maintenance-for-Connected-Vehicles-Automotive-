Predictive Maintenance for Connected Vehicles
A Machine Learning & IoT Data Solution for Reducing Vehicle Downtime

📌 Project Overview
This project develops a Predictive Maintenance system for connected vehicles, leveraging telematics and sensor data to predict component failures before they occur.
The solution applies time-series forecasting and anomaly detection techniques to provide early warnings, enabling proactive maintenance scheduling, cost reduction, and improved customer experience.

Designed for automotive manufacturers and service providers, this system integrates machine learning models, cloud-based data pipelines, and interactive dashboards to deliver actionable insights in near real time.

🎯 Business Impact
Reduced unplanned breakdowns by up to 30%.

Cut vehicle service downtime by 25%, improving fleet utilisation rates.

Saved operational costs by enabling data-driven, scheduled interventions.

🛠 Tech Stack
Languages & Libraries: Python, Pandas, NumPy, Scikit-learn, Prophet, LSTMs, Isolation Forest, Matplotlib, Seaborn
Data Engineering & Storage: Azure Data Factory, Azure Data Lake, SQL Server, AWS S3
Model Deployment & MLOps: MLflow, Docker, GitHub Actions, Airflow/Dagster
Visualisation: Power BI, Tableau

📂 Dataset
Source 1: Vehicle Performance Dataset – Kaggle

Source 2: NASA Turbofan Engine Degradation Dataset

Features Include:

Engine temperature, vibration levels, oil pressure

Battery voltage & charging patterns

Mileage & trip duration

Component service history

Failure/maintenance event logs (target variable)

⚙ Methodology
1️⃣ Data Pipeline Development
Ingested raw telematics data via Azure Data Factory into a governed data lake.

Automated daily refresh of aggregated datasets for model training and dashboards.

2️⃣ Data Preprocessing & Feature Engineering
Applied smoothing and rolling averages to sensor readings.

Created lag features & failure probability scores.

Normalised data for deep learning model compatibility.

3️⃣ Model Development
Time-Series Forecasting:

Used Prophet for seasonal usage trends.

LSTM neural networks for multi-sensor degradation prediction.

Anomaly Detection:

Isolation Forest to detect unusual behaviour in vibration & temperature signals.

4️⃣ Alert System & Visualisation
Power BI dashboard displaying component health scores & failure risk trends.

Alerts triggered when failure probability exceeds defined thresholds.

5️⃣ Deployment
Containerised models with Docker.

Deployed via Azure ML service with API integration for workshop/fleet management systems.
