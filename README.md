Utilizes API to retrieve real estate data from Zillow, analyze it, transform it and place it on a Google Map in real time.

Situation: A real estate agent was interested in mapping "good deals" for their clients within a specific geographic region.  I worked with them to develop this program.

Program: The current program utilizes an API in order to retrieve real estate information from Zillow.com. The data is then analyzed and transformed in order to evaluate the relative affordability of each property. Specifically, the program calculates price/sqft for each property. Based on that calculation, the property is then categorized as "Expensive", "Reasonable" and "Affordable." Based on these labels, the properties are then color coded (red, yellow and green) respectively and placed on a live Google Map.

Outcome: The program generated a great deal of positive feedback for the agent and has become an important "value added" for their clients.


Notes: In order for this Notebook to work, you will need to get an API key from https://rapidapi.com/apimaker/api/zillow-com1/ and https://developers.google.com/maps/documentation/geocoding/get-api-key. The APIs should then be saved in a file named api_key.csv with headers API and KEY. The rapid api key should be named "rapid" and the Google key should be named "google." In addition, parameters are set for what I was looking for, but they can be easily changed in the notebook.
