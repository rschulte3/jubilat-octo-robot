# X-Team 64 Flight Tracker

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.
Schedule a large number of passenger flights to a variety of 
destinations including seating arrangements on each flight. 

Describe at a high level a program that could solve that problem.
Store flight info via a directed graph and passenger info via a 
hash table. 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
Flight Tracker


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
Produce a passenger's ticket:
     Name: Rick
     Flight #: 1
     Seat #: 55
     Class: Economy
     Start: Madison
     Desination: New York
     Customer ID: xxxxx
Produce the passengers on each flight. 
     Name:     Seat:
     Rick      1
     Jim       2
     Bob       3
     Aamanda   4
     .
     .
     .
     
Produce the starting point and destination of each flight. 
     Flight:     Start:     Destination:
     1           Madison    Los Angeles
     2           Chicago    New York
     3           Atlanta    Boston
     .
     .
     .

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
     Passenger Name for producing a passenger's ticket. example: "Rick"  
     Flight number for producing passengers on a flight or the start/destination of a flight: "1"
     

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
Schedule a flight: A box to put in the passenger's ID with a menu listing the flights available.
Check-in page: A bo to put in the passenger's ID. Below that will be an output of their most recent ticet info.
This includes name, flight number, seat number, start, destination.
Customer History page: A box to put in the passenger's ID. An output below that would be a list of all the ticket
info of all their flights (flight #'s, seat #'s, start points, destinations).  
Flight Lookup: A box for flight number with an output below that of the start point, the destination, and the list
of passsengers. 
Travel Search: Two boxes one for a destination and one for a start point. An output below that would be the series
of flights needed to get to that destination. Or states that the destination is not reachable from the start point. 

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
Customer: stores the ID number and a list of Passenger objects. Can store other info about the customer that 
won't change from his/her flight to flight (contact info).
Passenger: stores the seat number, the flight number, the passengerID, the start point, and the destination. 
Passenger inherits from Customer.
City: that stores its name and ID
Airline: main class that stores the graph and the hashtable. It also stores a list of cities.





## Edit and Submit this file and any figures referenced by this document.

