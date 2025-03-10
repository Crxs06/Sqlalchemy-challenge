# Sqlalchemy-challenge
Analyze climate data using Python, SQLAlchemy, Pandas, and Matplotlib, then develop a Flask API to serve the results. Data is stored in an SQLite database.
Part 1: Climate Data Analysis
* Connect to SQLite using SQLAlchemy.
* Reflect tables (station, measurement).
* Query precipitation data (last 12 months) & visualize.
* Analyze stations & find the most active (USC00519281).
* Retrieve & plot last year's temperature data.
Part 2: Flask API
Endpoints:
* / - Lists available routes.
* /api/v1.0/precipitation - Last year’s precipitation (JSON).
* /api/v1.0/stations - List of stations.
* /api/v1.0/tobs - Last year’s temperature observations for most active station.
* /api/v1.0/<start> & /api/v1.0/<start>/<end> - Min, avg, max temperatures for given date range.
Evaluation Criteria
* Jupyter Notebook (Database connection, queries, plots) - 42 pts
* Flask API (Routes, JSON responses) - 40 pts
* Code Quality (Formatting, efficiency) - 8 pts
* Deployment (GitHub repo, commits) - 6 pts
* Comments (Clear explanations) - 4 pts
Deployment
1. Clone repo & install dependencies (pip install -r requirements.txt).
2. Run Jupyter Notebook for analysis.
3. Start API: python app.py.
4. Access endpoints via browser or Postman.
This project covers database management, data analysis, and API development.
