# Advance Cricket Simulation Program
It is a python notebook which simultes a cricket tournamnet involving various teams, field, umpire, commentator and match. 
# Program Overview
The program consist of following classes:
* Player : It represents a player of a team with attributes like name, bowling, batting, fielding, running and experience.
* Team : It represents different cricket teams with methods such as caption selection, send next player, choose bowler and deciding batting order.
* Field : It represents the field conditions through attributes such as size, fan ratio, pitch conditions and home advantage.
* Umpire : It is responsible for predicting the outcomes of a ball and handling the score by chuncking probabilities of all the players. It makes decisions such as LBWs, catches, no-ball and wide-ball to keep track of scores, wickets and over.
* Commentator : It provides commentory for each and every ball and over.
* Match : It simulates cricket match by using object instances of classes like Team, Field, Umpire with methods such as start the match, play innings and end the match.
