# Jack in the Box

*A lab report by Bar Kadosh* 

## Laser Cutting

For the laser cutting, I used the provided template as a starting point. Since I wanted my jack in the box to have an animal theme, I also wanted to add etching to my box. To do this, I added in images of animals to the different faces of my box. When actually using the later cut, I made sure to provide the different paramaters for cutting mode and etching mode. I also chose to use a larger scale for my cuts for no particular reason other than thinking it would look better.

## 3D Printing/Creating Jack

For the 3D printing, I also started with the template provited for the servo mount. I used Cura to add the stl file for the servo mount to the program and then adjusted the different printing settings (material, whether to add support or not, thickness of layers, etc.). These decisions are specific to the object being printed and I used my best judgment to print in a way that reduced time and material while still maintaining structural integrity. I then printed the servo mount successfully. 

I also made use of 3D printing for creating the jack. Initially, I designed a simple face/character to use for the jack on the CAD software provided. However, I then decided that I wanted to keep going with my animal theme and that I could find much more impressive designs online. Therefore, I found an already created stl file of a bear's face and printed it in the same way I printed the servo mount. Stl files for both my original jack design and the bear can be foun below.  

## Electronics

The electronics were fairly simple -- I simply connected the servo and a button to my circuit so that when the switch is pressed, the servo will rotate to open the hinged door. I also then downloaded and reviewed the code/program for opening the jack in the box.

## Putting it All Together

When putting it all together, the following process was followed. I first attached two sides to the bottom piece and securely glued all 3 together. I then added another side and glued it to the bottom and adjacent sides. For the last side, I first carved out a hole so that the servo's wires could flow out and drilled two holes for the servo mount to connect to. I then attached the fourth side and glued it on. 

At this point, I screwed the servo into the server mount and attached the cardboard piece to the servo mount that would help open the top side when rotated. I attached the servo mount to side with the holes I drilled for the mount, then connected the proper wiring, and then made sure that my servo was rotating when the button was pressed. I also updated the code so that the open position was 70 degrees instead of 110, as my servo's initial position was already a bit rotated past 0 degrees (0 degrees being parallel to the the bottom of the box).

I then glued by bear "jack" to the top face of the box, and attached the top face of the box through the hinge mechanism so that it could be open or closed and made sure it did indeed open and close when I pressed the button. Lastly, I wanted it to customize it so that the box stays open until "night time" when the animals would have to go to sleep and stop "roaring". Therefore I added a photo sensor to my circuit. I also altered the code so that once the button was pressed and let go of, if the light measure was higher than a certain value, the box would remain open. Only when the light level fell below a certain level would the box close and then could only be opened again by pressing the button.

## Final Deliverables

[My Jack Design STL](https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/JackMan.stl)

[Bear Design OBJ](https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/bear.OBJ)

[Jack in the Box Code](https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/motor.ino)

[Jack in the Box Video](https://youtu.be/3AtJwbNAvXA)

Additional photos of my box faces with etches, 3D printed bear jack, interior arranagment, and overall arrangement can be found below.

<img src="https://github.com/barkadosh1/IDD-Fa19-Lab3/blob/master/Screen%20Shot%202019-09-27%20at%2010.53.34%20PM.png">
