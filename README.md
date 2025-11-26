Movie Data Analysis Dashboard 🎬
- An interactive dashboard that explores ratings across genres
- Built using Flask, Pandas, and Numpy

**How to Run the Project**
- This project uses Flask as a backend web server
- Opening index.html directly in the browser will not work because Flask is used to serve the data API's
1. If needed install the needed things:
pip install flask pandas numpy
2. Run the flask server
python (or python3) MovieExplorer.py
3. Open the site
Once the server starts, click on the http link. The dashboard will load with charts and tables

**Why Flask?**
The dashboard requires Flask to load data from movies.csv and provide API endpoints
