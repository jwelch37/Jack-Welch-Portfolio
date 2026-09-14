# A4 – Benchmark a Parameter  

## Objective

Design an artifact that benchmarks a parameter for the Prusa Core One.  

**Parameter chosen:** Overhang angle test.  
I am using PETG, which according to research from (https://www.3dmag.com/3d-wikipedia/3d-printing-overhang-support-angles-materials/) PETG can handle an overhang angle of about 45-50 degrees, so I think it should begin to fail around there.  


## Design  

For my design I chose to create a shape that would provide a space for 8 different overhangs to test different angles with the goal to see how clean they printed without supports. 
I chose to design the angles of my overhangs to range from 30 degrees to 65 degrees, increasing in 5 degree increments. I wanted to see the difference in print quality from an angle that should print cleaning to one that would very likely print messily or sag. Originally I had the angles ranging much lower and with smaller increments and a max angle of 54 degrees, but I realized that this would would likely not be enough of an angle to properly test the capabilities of the printer.    

<img src="30deg.png" alt="Description" width="10%"> <img src="35deg.png" alt="Description" width="8%"> <img src="40deg.png" alt="Description" width="10%"> <img src="45deg.png" alt="Description" width="8%"> <img src="50deg.png" alt="Description" width="10%"> <img src="55deg.png" alt="Description" width="10%"> <img src="60deg.png" alt="Description" width="10%"> <img src="65deg.png" alt="Description" width="10%">  

The general shape is a sort of cross. This was pretty arbitrary, I just chose a shape that had enough outcrops to have 8 overhangs, I cut a hole in the center to cut back on time and material.  

<img src="model.png" alt="Description" width="40%">  

For the lengths of the overhang, I wanted them to be tall and deep enough so that any errors in the overhang would be visible and clear.  















