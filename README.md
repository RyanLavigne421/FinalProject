# How To Use
Car Data Visualizer

Breif: This is a program that takes input of a CSV file from the COBB Accessport which was a datalog of me driving my car. it will then take this file parse through it and then take that very hard to read data and put it in a graph so it is much easier to see what is happening. 

Example Command: main -o test.csv

Key: there is only 2 arguments that are needed to be passed in. The first is using (dash) you can chose from the 10 following options
- o = Oil Tempature
- r = RPMs
- b = Boost
- t = Transmission Tempature
- f = Fuel Pressure
- m = Intake Manifold Temp
- q = Req Torque
- a = Air/Fuel Ratio
- c = Coolant Tempatures
- i = Ignition Timing

- If not option is selected it will throw error saying no arguements and the exit.

Note: The X-axis is always going to stay the same because for easy reability I made it so that ever the option they choose is always over time. 

# Libraries Used

- I used pbPlot as a library to make the graphs

# During Project Process
Final Project for CSI-230

- Made the main frame for the project 
- having a hard time finding a good graph library
- Added test.csv file to be able to get it on my VM and to test with real data
- Adding checks for arguments
- Added graph_utils.cpp & graph_utils.h to be able to parse through the CSV file
- started to add arguments in  and starting to link them to the CSV processing
- Added 2 arguments to call (RPM & Boost for now) I hope to add more when I get the graph going. Trying to size it back for now till I get it working flawlessly then I will add more
- Added pbPlots which is a c++ library that makes making graphs easy
- I had issues havign processCSV in the other graph_utils.cpp so I brought it back over to the main.cpp file and also put the PrintVector function into the graph_utils.
- Updated all nessecery files
- Figured out a way to condense my code by half
- Program makes a graph like supposed to
- Decided that 32 options was too much so I only implememted 10 of the most important ones to have\
- Works flawlessly
- Cleaning Code up and checking over requirements
- I watched the video back like 6 times and tried for about an hour to get the shared object lib to work but it has failed so instead of wasting time I moved on and will take the points on it. I kept getting a error. here is a screen shot https://docs.google.com/document/d/1JMttmGoSrf97W4w9KVs2Bu5TBHP6xWiwwDsdCYJLpss/edit?usp=sharing

