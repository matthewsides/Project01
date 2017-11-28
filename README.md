![Alt text](https://github.com/matthewsides/Project01-TraceBall/blob/master/traceballprojectlogo.png?raw=true "Optional Title")

  Version 1.01
  28 November 2017
     

# Revision List

| Version     | Author          | Date                 | Comments                       |
|-------------|-----------------|----------------------|--------------------------------|
| 1.00        |  Matthew Sides  |              2017    | Initial Version                |
| 1.01        |  Matthew Sides  |              2017    |                                | 
|             |                 |                      |                                | 
|             |                 |                      |                                |
|             |                 |                      |                                |
|                                                                                       |                         


# Table Of Contents

[1] Introduction 

[2] Scope

[3] Type Conventions
     
[4]  Research

[5] References 

[5] Target System 

[6] Specification 

[7] High Level Description 

[8] Project User Stories



### [1] Introduction

This document specifies a design for the conceptual features and mechanics (gameplay) of a game with the provisional title “TraceBall” . It is based on elements found within a given brief specifying for a game based around a square following a mouse on screen.  

### [2] Scope

This documentation is intended to be read by programmers, artists and producers involved in the design implementation and testing of the HTML internet game "TraceBall".

### [3] Type Conventions

Things that have been discussed in a meeting are presented in this document with no asterisks.

Things that have not been offically agreed on but which are suggested by the author are presented with asterisks, like this (*),being marked as omitted until it has been agreed upon that it may be of use or implemented.

### [4] Research

This segment marks 

### [5] References

N/A


### [6] Target System
TraceBall will be produced for the following platforms: Windows all versions running on HTML 5 (Internet Browser), Chrome and Explorer, written in Java Script though the ID Notepad. This Documentation is primary concerned with the internet browsers chrome and explorer though maybe expanded and branch out to other browsers at a later date.

### [7] Specification 

### 4.1 High Level Description 

A non-playing character NPC (that is a character controlled by the computer) targets the users mouse position as the player moves across the screen, the game is over once the NPC touches the players mouse position 3 times. 


### User Stories

I would like to be able to the view the game within a browser. -  View in Browser  
I would like to be able to see and have the NPC model (square) follow me across a screen. - NPC follow me  
I would like to be able to end the game. - Initiate and End the Game 
I would like to be able to move across a screen. - Be able to move    
I would like to be able to get feedback on the amount of lives I have concurrent to whats happening on screen. - Amount of Lives (Feedback) 

### Project Back Log

| User Story  | Description                  | Points | Due Date | Mo | Tu | We | Th | Fr |
|-------------|------------------------------|--------|----------|----|----|----|----|----|
| 1           | View in Browser              | 2      |22 Sep    |    |    |    |    |    |
| 2           | NPC follow me                | 1      |22 Sep    |    |    |    |    |    |
| 3           | Initiate and End the Game    | 1      |22 Sep    |    |    |    |    |    |
| 4           | Be able to move              | 3      |22 Sep    |    |    |    |    |    |
| 5           | Amount of Lives (Feedback)   | 2      |22 Sep    |    |    |    |    |    |
| Total Points| 9                 |


### Algorithm - (Flowchart)

<img src="Project01/FlowChartP1.jpg" alt="Project1"
     title="Project1" />
     
### Process of implementation Algorithm

The HTML page was first developed, whilst a canvas was thereafter defined, then another square was defined within the canvas. Furthermore the mouse was is then required to be tracked on the screen to the canvas, whilst the cords of the square are also needed to be retrieved. The cords then need to be compared minus or adding onto the cords of the square if certain conditions are met, including a timer to ensure that the square movement is smooth and doesnt look like its teleporting around or about the page or screen. Inaddition the square and mouse then need to have a defined area or set cords or x and y with a conditional statement comparing them seeing whether the cords are eqaul or enroach on one another.Moreover adding at the end of the statement to minus lives, creating or defining a lives variable where if there is collision a life or numerical value is subtracted or taken away from the variable. While the code is held or indented within a loop where if certain conditions are met i.e: the user runs out of lives or the variable lives hits a certain defined numerical value the game ends.

### Description of IDE used and features it provided

The IDE ( Integrated Development Environment) used was notepad, though notepad is a questionable IDE as it has no redefining features and doesnt provide any comprehensive facilities except an area to write code and save the file in relation to the type of code written.

### Debugging process and debugging facilities in your chosen IDE

The IDE or notepad does not have any debugging facilities,but the debugging proccess has to be done manually either scrolling through code to locate and fix the problem or using preset code that is indented into the program and debugs the code, finding the problem for it to be solved (fixed).
