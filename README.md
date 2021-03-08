# sqlalchemy-challenge

# SQLALCHEMY SURFS UP: Project

   # Background
      * Data Analysis through SQLAlchemy and by creating a flask

   ## Technologies used:
      * Flask
      * NumPy
      * SQLalchemy
      * Pandas
      * Matplotlib
      * Datetime
      
   ## Step 1:
    For the Precipitation analysis
      *  Worked on building a query using the latest year data, to get the date, prcp values. 
      *  After the analysis, I plotted a diagram using dataframe plot method.
      *  Lastly, also displayed a precipitation data summary statistics.

    For the Station analysis:
      * I worked on building a query to find the amount of stations, in a descending order.
      * Also, I found out which was the most active station.
      * Then, I looked at the most active station during the lastest year and created a histogram to showcase it's temperature observation datas 


   ## Step 2:
    
    Hawaii Climate App

      * Built a Flask API.

    Routes:
      * (/) - Home or starting page
      * (/api/v1.0/precipitation) - Created a query from latest precipitation datas. And, then, I outputed all the data in a JSONified dictionary form
      * (/api/v1.0/stations) - Then, I listed the names of stations. 
      * (/api/v1.0/tobs) - Furthermore, I looked at the most active station in the latest year and made a query for temperature observations,date. I returned all the data in a JSONified dictionary form
      * (/api/v1.0/<start>)I made a query for the starting date and outputed the max, min and average temperature. I outputed all the data in a JSONified dictionary form
      * (/api/v1.0/<start>/<end>) I made a query for the starting /ending date range, that showed the max, min and average temperature. I outputed all the data in a JSONified dictionary form.


   ## Inspiration
      Rutgers Bootcamp
