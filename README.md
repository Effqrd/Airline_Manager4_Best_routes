Welcome to this Airline Manager 4 tool used to determine the best routes to make for your airline.

On the ipnyb file, you will be able to extract the best routes for your airline, for a certain aircraft type, on the hubs you have and on the number of trips you want to do every days.

First you need csv files of the best routes for your configuration done by discord bot and PLACE THEM INSIDE THE SAME FOLDER AS THE IPYNB.

To do so, you can access to https://discord.gg/7CYCyfYWes, you will be inside the Airline Manager Discord Server, go to the #bot-spam channel and writes your commands :

$routes XXX aircraft[sfc] none Y 

Replace "XXX" by the ICAO Hub code, for example CDG for Paris Charles de Gaulle, HKG for Hong Kong, SYD for Sydney Intl and so on...

Replace "aircraft" by your aircraft, for example a388 for A380-800, you can find the code adapted to the type of aircraft you want to there : https://docs.google.com/spreadsheets/d/1xoEtXi4qibjyTHq05vh0frzWXLKXiAvXulAUB-zUW0M/edit?gid=0#gid=0

The "[sfc]" thing if to say to the bot that you have put the 3 upgrades on your plane, s for speed, f for fuel and c for C02 quotas.

The "none" is to not impose a time of a route so the bot will be able to find all the routes the aircraft is able to reach.

Replace "Y" by the number of trips you want to do per days, example 1 by default if you don't put anything, 2 if you want to depart your planes every 12 hours, 3 every 8 hours and so on...

Once you have put the command inside the #bot-spam channel and you have downloaded the csv files of every hubs you have for the aircraft you want to operate put them inside the same folder as the best_routes_extractor.ipynb file.

Open the Jupiter notebook, change, if needed, the parameters you want as the aircraft code, the number of trips per day and it will be sufficient.

Install the library needed to run the program and run it.

You now have a csv file with the best routes you can have with your hubs and your aircraft for the configuration you asked.
