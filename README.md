# nosql-challenge

Overview:
NoSQL_setup
Part 1: In jupyternotebook I read in and assigned the database and collection to variables “uk_food” and “establishments”, respectively. Part 2: I updated the database with new restaurant data provided in the challenge module. I updated 0 values in Rating Value to null, the lat and long types to Decimal, the Rating Value type to Int, and checked the types with find_one.
NoSWL_analysis
Part 3: I queried and counted documents based on Hygiene scores, Local Authority Name, and Rating Value, converting results to a pd.DataFrame.
Using stored data on restaurant “Penang Flavours,” I created a pipeline to query nearby establishments, filtering by Hygiene score and Rating Value, converting results to a pd.DataFrame.
I created another pipeline to count the establishments with a Hygiene score of 0, which I also displayed in a pd.DataFrame.
Resources-establishments.json
Original database


Technologies used:
Imported json database from command line using mongoimport: 
“mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json“
Jupyternotebook
Dependencies:
mongod/mongosh in command line
pymongo/MongoClient and json to read in database
pprint & pandas pd for visuals

Final project link: https://github.com/InsomniYak28/nosql-challenge
