The Simulator is not written by me (Baris Üctas).
It is written by Ahmad Reza Ceraghi from the Heinrich-Heine-Universität and all credits for it belongs to him.
My written code is in the directories: solution and scenario.


Bachelor Thesis is: Central and Decentral Algorithms for the formation of Swarms

HOW TO USE:
In the Config.ini File are a few options that you can change.
The relevant ones are the 
- amount of robots(particles): p_amount
- dyanmic scenario: dynamic
- which scenario to load up: scenario
- which solutiontype to load (central or decentral): solution



HOW TO INSTALL
For Linux:

-unzip the source code:

    unzip swarm-sim.zip


-install the following python packages:

    1. sudo apt-get install python3.6 python3-pip 

    2. sudo pip3 install numpy

    3. sudo pip3 install pandas

    4. sudo pip3 install pyglet

- install Gnuplot:

    sudo apt-get install gnuplot-x11

- go to the main folder of the SNS-Folder and start it with:

    python3.6 run.py


For development the IDE Pycharm is recommended:

https://www.jetbrains.com/help/pycharm/install-and-set-up-pycharm.html


For Windows:
- unzip souce code
- install python3.6
- install pycharm
- run pycharm
- open swarm-sim as a project
- Open File->Settings-"Project-Interpreter"
- Chose python3.6 as an interpreter
- Chose the plus sign and install:
    1. pip3
    2. numpy
    3. pandas
    4. pyglet
- press Okey
- wait that everything is installed
- chose Run->run.py
    - If it gives an error that it cannot find the interpretetor
       Open Run->"Edit Configuration" Chose the python3.6 as an interpretetor
