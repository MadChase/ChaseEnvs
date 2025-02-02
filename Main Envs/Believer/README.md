## Used in:
https://beatsaver.com/maps/3a526

## Summery:
Environment based on the song Believer and has a lot of lighttable geometry.

## How to install:
Main (suggeted):     
Go into the info.dat file and find where is says: ("_environmentName":) and make that say: ("_environmentName": "DragonsEnvironment",)  
Go download the script here: https://github.com/MadChase/ChromaPlus-Importer/tree/main  
Follow all the steps in the Github page and download the script from releases  
Put everything in One folder (env.dat, ExpertPlusStandard.dat, and ChromaPlus-Importer-1.0.0.py) and run the script via VSCode  
Go into Chromapper and save the diff and then you should be good to go.

Alternate:    
This is for people who want to do it without the chorma importer (still needs VSCode).    
Open up the your diff in VSCode and search for the word "customData" using ctrl+f.   
(If missing or having multiple go into Chromapper and click the pickaxe tool in the map menu screen for a diff, then type something into the blank space that pops up. Then go back to VSCode ctrl+f for whatever you typed in and use the "customData" that that was in)    
Copy all text in the "customData" of the env.dat file into the diff's "customData".    
Go into Chromapper and save the diff and then you should be good to go.      
Note - make sure to switch the env to the one listed in the main steps



## How to Use:
If you plan on using cm for chroma ids i HIGHLY suggest getting the ExtendedLightIDs plugin found here: https://github.com/MoistSac/ChroMapper-ExtendedLightIDs which allows you to see the added light ids using alt+p.    

Back Lasers: no light id is needed, it is just a filler light that eliminates the main area.   
Inner Ring: Needs light ids. 101-103 are the big lasers (101 middle, 102 left, 103 right) 104-106 is the 3 sides for the pyramid (104 middle, 105 right, 106 left) 107-109 is the 3 balls (107 left, 108 middle, 109 right) and 110 is the floor for the whole env (can be VERY bright so be carefull)    
Left and Right Lasers: uses light ids 1,7,13,19,22,25 in that order from close to far    

Tracks: has tracks on the balls so you can move them which are "track": "Ballleft", "track": "Ballmid", and "track": "Ballright", respectively 


![Alt text](PIC.png)
