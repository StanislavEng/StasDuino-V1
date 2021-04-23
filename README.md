# StasDuino-V1
A simple PCB project of an Arduino Clone. This was a "project" I chose to do to learn some of the steps required in PCB design.
This encompassed looking up components, using datasheets to create footprints, creating the schematics and laying them on the actual (software) PCB.

This project was done in Autodesk Eagle because I had it installed from earlier and is probably useful to learn anyway. 

For V1, the main components such as the ATMega, the serial converter and some resistors and MOSFETs were made by me.  
The rest of the parts I grabbed from libraries because I wanted to get into the real meat of the task. 

The schematic, at least in regards to wiring up the components related to the ATMega, were done by referring to the datasheet and the  
Atmel "Hardware Design Considerations" paper. The rest I looked at the official Arduino schematic to get some (better practices) understanding  
of how they did it and a bit of why. 

The real time crunch, apparently, was creating the actual layout on the PCB. Laying out the pieces in a way that allowed for better tracing was  
actually a painful but interesting learning experience. As a result, I also created "3" revisions to try to improve the layout. 

## Rev 1:
My original board design, learning to create traces and place down parts and as a result does not have the best of tracing. 
![image](https://user-images.githubusercontent.com/39227553/115812344-1492dd80-a3a6-11eb-9447-a9670939146e.png)

## Rev 2: 
Looking at what the autotrace creates and seeing what is *maybe* possible, best practice wise, as in what kind of designs (regardig traces) is allowed.
![image](https://user-images.githubusercontent.com/39227553/115812376-1f4d7280-a3a6-11eb-8ca5-696fdbb5071b.png)

## Rev 3: 
Recreating traces and changing some part orientation to create a overall better designed board. Not sure if actually better but I felt more proud.
![image](https://user-images.githubusercontent.com/39227553/115812414-32604280-a3a6-11eb-9069-fff8fd9c545f.png)
