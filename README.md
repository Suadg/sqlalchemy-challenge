# sqlalchemy-challenge

sqlalchemy1

# Objective

Part 1: Analyze and Explore the Climate Data
- perform a thorough climate analysis and data exploration of Honolulu, Hawaii, in preparation for a holiday vacation. Using Python, SQLAlchemy, Pandas, and Matplotlib
    - connect to SQLite database using SQLAlchemy [create_engine()]
    -reflect tables into classes using automap_base() and using Measurement and Station
    -create and close Alchemy session to link python to database
    - conduct a Precipitation Analysis, query the last 12 months of data, load the results into Pandas dataframe and visualize the data by plotting charts

# Part 2: Design Your Climate App
- develop a Flask API based on the findings and queries from the initial analysis
    - Present a homepage that lists all available API routes
    - Offer an endpoint (/api/v1.0/precipitation) to retrieve and return the last 12 months of precipitation data in JSON format
    - Provide a route (/api/v1.0/stations) to return a JSON list of all weather stations in the dataset
    - Create an endpoint (/api/v1.0/tobs) to query and return a JSON list of temperature observations for the most active station over the previous year.
    - Implement routes (/api/v1.0/<start> and /api/v1.0/<start>/<end>) to return JSON lists of temperature statistics for specified start and/or end date ranges


