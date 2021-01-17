# POV-Based-Displays
Persistence of Vision Based Displays Project

The purpose of this project is to design and to create a persistence of vision (POV) display. A POV display exploits this phenomena by spinning a one dimensional row of LED's through a two dimensional space at such a high frequency that a two dimensional display is visible. In our case, we created a circular display by spinning a column of LED's around a central motor shaft. The rotational speed of the LED's is fast enough such that the human eye perceives a two dimensional image.

The logic behind our project is very straightforward. Consider a 8x5 matrix as shown where each column represents
the LED array with led 1,2,3,4,5,6,7,8 connected at digital pins 2,3,4,5,6,7,8,9 of microcontroller respectively.

Suppose, we want to display the alphabet A. We will first select the column C1. Now, the first column is active, and we need to turn on the LEDs in the rows R2 through R8 of this column, which can be done by providing digital 1 to these pins using our microcontroller. Next, select the column C2 apply digital 1 to R1 and R5, and so on. Therefore, by rotating led array at a certain speed (> 800 rpm), and turning on the respective LEDs in each row of that column, the persistence of vision comes in to play, and we perceive the display image as still.

Mechanical Design...

 ![Image description](https://github.com/ShounakCy/POV-Based-Displays.git/blob/main/Picture6.png)

 ![Image description](https://github.com/ShounakCy/POV-Based-Displays/blob/main/Picture7.png)

See also [POV video presentation](https://www.facebook.com/robenky.svc/videos/1630431333874883/) 


