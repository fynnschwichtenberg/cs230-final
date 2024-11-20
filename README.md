# cs230final 
Name: Fynn Schwichtenberg
CS230: Section 6 

## Description

This program will help people determine how convinent it is to go to and from the airport to their airbnb.
People often choose airbnbs based on how conventient it is to get to and from.
In this project I will use the Boston Airbnb Data (https://ourairports.com/data/) and the New England Airport data from (https://insideairbnb.com/)
to generate a map using Stream lits map package and then Marker Cluster to cluster air bnb’s with similar proximities to selected airports.
Users will be able to select an airport in the new england area and then see what Airbnbs have the best convenience score calculated based on how
far away they are from the airport. Depending on the range they fall in,
a different color will be attributed to the dot representing the one or many Air bnbs and how close they are.


[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://convenienceairbnbboston.streamlit.app/)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```
