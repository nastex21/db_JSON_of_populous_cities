# map_json
This is json database of metro cities around the world that have more than 1,000,000 people. 

My source for this is this pdf file: http://www.demographia.com/db-worldua.pdf.

What I did to rip out the data is that I used Tabula to select the tables and grab the data. Tabula gives you the option to spit out a json
file but in my experience, the json file was just a bunch of gibberish while the csv file was actually usable. Then I converted the csv
file to a usable json file. Unfortunately it had a bunch of special characters probably due to the conversion so I had to clean that up. 
After that, the cities were formatted with their metro names (for example: Los Angeles-Riverside) so I cleaned all that up too and 
left the cities names by themselves (for example: Los Angeles).
