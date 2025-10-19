## Used in:  
SoonTM 

## Summery:  
Cube in a cage with flying blocks as the lane

## How to install:  
Main (suggeted):    
- Go download the script here: https://github.com/MadChase/ChromaPlus-Importer/tree/main  
- Follow all the steps in the Github page and download the script from releases  
- Put everything in One folder (env.dat, ExpertPlusStandard.dat, and ChromaPlus-Importer-1.0.0.py) and run the script via VSCode
  
NOTE - This env specific NEEDS Noodle to work (ie, needs both chroma and noodle in the map)   

Alternate:    
This is for people who want to do it without the chorma importer (still needs VSCode).    
- Open up the your diff in VSCode and search for the word "customData" using ctrl+f.
(If missing it go into Chromapper and click the pickaxe tool in the map menu screen for a diff, then type something into the blank space that pops up. Then go back to VSCode ctrl+f for whatever you typed in and use the "customData" that that was in)    
- Copy all text in the "customData" of the env.dat file into the diff's "customData".    
- Go into Chromapper and change the env to the env this envomrnt uses and save the diff and then you should be good to go.      
Note - make sure to switch the env to the one listed in the main steps


## How to Use:  
Note - This env specifically NEEEDS noodle to work properly    

If you plan on using cm for chroma ids i HIGHLY suggest getting the ExtendedLightIDs plugin found here: https://github.com/MoistSac/ChroMapper-ExtendedLightIDs which allows you to see the added light ids using alt+p.  

- Left+Right rotation lasers: small lasers coming off of the top (not affected by rotation events) and are LightID: 11-17 respectively    
- Back Lasers is the fill lights from under and are LightID: 150-153    
- Everything else is on Big Ring Neons:    
- The Big Cube in the middle is LightID:101    
- The lasers around the area are LightID:2001-2010.    
- Tracks: You can mess with them though they should be working as intended. Too many to list so just look in your .dat file if you want to mess with them   


![Alt text](PIC.png)




