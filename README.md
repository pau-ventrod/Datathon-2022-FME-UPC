# Datathon FME 2022 Resolution

This is our resolution for the Datathon that took part in the UPC the 12th and 13th of November 2022.\
The resulution was proposed by our team: Functionarios. 

## Members:
	- Èric Sánchez ()
	- Alejandro Donaire ()
	- Pau Ventura (pau.ventura.rodriguez@gmail.com)

This year the competition aimed to solve a Supply Chain problem where each product followed the path: Port -> Logistic Hub -> Local Distribution center.
This chain was sometimes delayed due to some unknown facts.\
The goal then was to try to give reasons why the products were delayed, provide solutions in order to reduce the ammount of delayed orders, and lastly build a model to predict which orders may be delayed.

To solve these problems, a large ammount of data was given, splitted into different datasets.\


One of our features included predicting the path that a truck had to follow in order to reach a Hub/Distribution center, in order to know the Countries that drove in, and using a Traffic Jam database to try and better predict the delays on transport.
Credits to healeycodes (https://github.com/healeycodes/country-borders) for its code on finding country borders.

Our solution ended on 2nd place in the Kaggle leaderboard, with 83.617% ROC AUC score, out of 27 teams.