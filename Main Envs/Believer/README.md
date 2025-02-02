## Used in:
https://beatsaver.com/maps/3a526

## Summery:
Environment based on the song Believer and has a lot of lighttable geometry.

## How to install:
Mian (suggeted):     
Go into the info.dat file and find where is says: ("_environmentName":) and make that say: ("_environmentName": "DragonsEnvironment",)  
Go download the script here: https://github.com/MadChase/ChromaPlus-Importer/tree/main  
Follow all the steps in the Guthub page and download the script from releases  
Put the eveything in One folder (env.dat, ExpertPlusStandard.dat, and ChromaPlus-Importer-1.0.0.py) and run the script via VSCode   
NOTE: This env specific NEEDS Noodle to work (ie, needs both chroma and noodle in the map)   

Alternert:
This is the easy way for people who don't know how chroma coding works. First go into a map in cm, click on the pickaxe button on the bottom. Then add one thing to the list (don't have to put anything in the text box). Then change the environment to BTS.
Then hit the open folder button on the bottom left. Open up the diff you just added the pickaxe stuff to and find (use ctrl+f to search for the word) to find where it says "environment". Copy all text in the .dat file called env.dat here and paste it over both the "environment" and the [ ] and what is in it. You should then be good to go with using it in cm. 

## How to Use:
If you plan on using cm for chroma ids i HIGHLY suggest getting the ExtendedLightIDs plugin found here: https://github.com/MoistSac/ChroMapper-ExtendedLightIDs which allows you to see the added light ids using alt+p. 
Back Lasers: no light id is needed, it is just a filler light that eliminates the main area.
Inner Ring: Needs light ids. 101-103 are the big lasers (101 middle, 102 left, 103 right) 104-106 is the 3 sides for the pyramid (104 middle, 105 right, 106 left) 107-109 is the 3 balls (107 left, 108 middle, 109 right) and 110 is the floor for the whole env (can be VERY bright so be carefull)
Left and Right Lasers: uses light ids 1,7,13,19,22,25 in that order from close to far 

Tracks: has tracks on the balls so you can move them which are "track": "Ballleft", "track": "Ballmid", and "track": "Ballright", respectively 


![Alt text](PIC.png)
