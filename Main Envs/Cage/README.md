## Used in:  
https://beatsaver.com/maps/41287 

## Summery:  
Cube in a cage with flying blocks as the lane

## How to install:  
Go into the info.dat file and find where is says: ("_environmentName":) and make that say: ("_environmentName": "KDAEnvironment",)  
Go download the script here: https://github.com/MadChase/ChromaPlus-Importer/tree/main  
Follow all the steps in the Github page and download the script from releases  
Put the everything in One folder (env.dat, ExpertPlusStandard.dat, and ChromaPlus-Importer-1.0.0.py) and run the script via VSCode   
NOTE: This env specific NEEDS Noodle to work (ie, needs both chroma and noodle in the map)   

Alternate:
This is for people who want to do it without the chorma importer (still needs VSCode).    
Open up the diffyour diff in VSCode and search for the word "customData" using ctrl+f.   
(If missing or having multiple go into Chromapper and click the pickaxe tool, then type something into the blank space. then ctrl+f for whatever you typed in and use the "customData" that that was in)    
Copy all text in the "customData" of the env.dat file into the diff's "customData" and you should then be good to go with using it in cm.    
Note - make sure to switch the env to the one listed in the main steps

## How to Use:  
If you plan on using cm for chroma ids i HIGHLY suggest getting the ExtendedLightIDs plugin found here: https://github.com/MoistSac/ChroMapper-ExtendedLightIDs which allows you to see the added light ids using alt+p.   
Everything is on Big Ring Neons: 
The Big Cube in the middle is LightID:101  
The fill lights from the lane are LightID:1001-1003 plus other fill lights for LightID:150-153  
The lasers around the area are LightID:2001-2010.  
Tracks: You can mess with them though they should be working as intended. Too many to list so just look in you .dat file if you want to mess with them   


![Alt text](PIC.png)
