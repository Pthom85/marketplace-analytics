Advanced Two-Sided Marketplace Analytics
This project demonstrates a comprehensive analytics approach for a two-sided marketplace (e.g., Rover, Airbnb, Uber) using synthetic booking, owner, and sitter data. It covers end-to-end analytics: exploratory analysis, advanced segmentation, machine learning, A/B testing, and business dashboarding with Python (Jupyter) and Tableau.
________________________________________
Project Objective
•	Analyze marketplace health (supply/demand, balance, trends)
•	Perform operational quality assessments (response time, cancellations)
•	Segment user behaviors (power users, churn, cohorts)
•	Run experiments (A/B testing, feature adoption)
•	Model marketplace dynamics (price elasticity, lead time)
•	Evaluate trust, safety, and efficiency
•	Visualize all insights in actionable dashboards
________________________________________
Project Structure
├── README.md
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_marketplace_health.ipynb
│   ├── 03_operational_quality.ipynb
│   ├── 04_segmentation_clustering.ipynb
│   ├── 05_ab_testing.ipynb
│   ├── 06_marketplace_dynamics.ipynb
│   ├── 07_trust_safety.ipynb
│   ├── 08_efficiency_optimization.ipynb
│   ├── 09_network_effects.ipynb
│   └── 10_custom_analytics.ipynb
├── data/
│   ├── bookings.csv
│   ├── owners.csv
│   └── sitters.csv
├── tableau/
│   ├── Marketplace_Health.twbx
│   ├── Operational_Quality.twbx
│   ├── Segmentation.twbx
│   ├── AB_Testing.twbx
│   └── All_Dashboards.pdf
├── images/
│   └── dashboard_screenshots/
├── requirements.txt
└── LICENSE
________________________________________
How to Use This Project
1.	Clone the repository
2.	Open notebooks/ and follow each notebook step by step
3.	Explore Tableau dashboards in tableau/ (open with Tableau Public/Desktop or view screenshots in images/)
4.	Reproduce or extend analyses with your own data
________________________________________
Tech Stack
•	Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, TextBlob, Statsmodels)
•	Jupyter Notebook
•	Tableau (visual analytics)
•	Synthetic CSV data (easily replace with real data)
________________________________________
Project Steps & Documentation
1. Data Preparation
•	Load and clean synthetic data (owners, sitters, bookings)
•	Feature engineering: response times, booking lead time, churn flags, etc.
2. Marketplace Health & Balance
•	Sitter-to-owner ratio trends
•	Listing fill rates
•	Geographic supply/demand heatmaps
3. Operational Quality
•	Sitter response time distribution
•	Cancellation reasons analysis
4. Behavioral Segmentation & Churn
•	Power user identification
•	Churn prediction (ML: RandomForest)
•	Cohort & lifecycle analysis
5. Product Usage & Experimentation
•	Feature adoption tracking
•	A/B Test analysis (t-tests, visualization)
6. Marketplace Dynamics
•	Price elasticity (logistic regression)
•	Time to first booking
7. Trust & Safety
•	Incident/event rate trends
•	Review sentiment analysis (TextBlob)
8. Efficiency & Optimization
•	Idle inventory identification
•	Booking lead time insights
9. Network Effects
•	Referral impact (network analysis)
•	Booking clusters (KMeans, geospatial)
10. Out-of-the-Box Analytics
•	Dynamic pricing simulation
•	Matching efficiency (request-to-confirmation)
•	User journey funnel/drop-off mapping
________________________________________
Tableau Dashboards
•	Dashboards are included as .twbx (Tableau packaged workbooks) in the tableau/ folder.
•	Also included: screenshots of dashboards (images/dashboard_screenshots/) and a PDF overview.
•	Each dashboard covers a key analytics theme (Marketplace Health, Segmentation, Operational Quality, etc.).
________________________________________
Reproducibility & Customization
•	All code is in clean, stepwise Jupyter notebooks.
•	Replace data/ with your own or real marketplace data for direct business application.
•	Tableau dashboards accept the same CSV data for plug-and-play analysis.
________________________________________
Contact
For questions, suggestions, or collaboration, open an issue or contact - Praveen Thomas / thomas.praveen86@gmail.com
