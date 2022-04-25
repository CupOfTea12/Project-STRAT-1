# Project-STRAT-1
HAB project (high altitude balloon) of 3 smart kiddos who show interest in cosmonautics, satellites and astronomy.
This repo includes DataSimulator (dashboard) made for STRAT-1 , custom PCB's and the main code that runs in the HAB.
Hope that these resources will help somebody later with building their own HAB project

# DataSimulator (HAB Dashboard)
Includes:
-real time data graphs and packet decoding
-graph & decoded data download in excel/word document
-Realtime Map (works only if you are transmitting GPS data in the packets on your HAB )
-Creating more HAB profiles (you can create more than 1 HAB profiles in the dashboard)
-Data summary ( from whole HAB mission)

# STRAT-1
STRAT-1 is a basic high altitude balloon sond in shape of cube (we call it ,, the cubesat test"). The structure is 3D printed, PCB's are custom made for the size and pinouts. There's a hierarchy simillar to the real cubesats:
 - PowerBoard: the place where the batteries connects to the solar panels (also the on/off switch is implemented there aswell)
 - OBC (On-Board Computer): the heart of the HAB
 - SensorBoard: PCB with all the sensor modules
 - Communication Board: GPS & data transmitting (433Mhz)
