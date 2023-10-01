# HackYeah2023

This is the presented Demo for the Hack Yeah 2023 event.

We wanted to demonstrate the effectiveness of giving people their own data back, to empower them in the fight against pandemics.

A little about the code:

We implemented different classes for Cities, People, People who use the app and a recommendation system which would be based on the app in real life. These classes are ```City```, ```Person```, ```AppUSer```, ```RecommendationSystem``` respectively. The main class is ```Simulation``` which runs the simulation.

We wanted to visualize the effects of travel control based on the app data. We made a very simple simulation. People live in a city but they can travel with a given probability. People in cities with the disease present can get infected. There is also a patient zero who starts the pandemic. People who use the app do not travel to cities with too high of an infectation rate. On the visualization below this dangerous zone is defined as 5% of the population of the city.

We can see an iteration counter on the visualization below. The left side is the simulation with uninformed people, the right side is the simulation with people who use the app and don't travel to cities with too high if an infection rate. The big black circles are the cities with their name above them. Each city has differently colored people so we can follow the traveling. Infected people are highlighted with red color. In each iteration every person can travel/stay home and can get infected if there is an infected person in the city they are currently in.

![](https://github.com/szocsmik/HackYeah2023/blob/main/movie.gif)
