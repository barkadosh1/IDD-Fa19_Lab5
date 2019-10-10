# Jack In The Box

*A lab report by Bar Kadosh* 

## Laser Cutting

For the laser cutting, I used the provided template as a starting point. Since I wanted my jack in the box to have an animal theme, I also wanted to add etching to my box. To do this, I added images of animals to the different faces of my box. When actually using the laser cut, I made sure to provide the different paramaters for cutting mode and etching mode. I also chose to use a larger scale for my cuts for no particular reason other than thinking it would look better.

## 3D Printing/Creating Jack

For the 3D printing, I also started with the template provited for the servo mount. I used Cura to add the stl file for the servo mount to the program and then adjusted the different printing settings (material, whether to add support or not, thickness of layers, etc.). These decisions are specific to the object being printed and I used my best judgment to print in a way that reduced time and material while still maintaining structural integrity. I then printed the servo mount successfully. 

I also made use of 3D printing for creating the jack. Initially, I designed a simple face/character to use for the jack on the CAD software provided. However, I then decided that I wanted to keep going with my animal theme and that I could find much more impressive designs online. Therefore, I found an already created obj file of a bear's face and printed it following the same method I used when printing the servo mount (except I added a support this time). STL/OBJ files for both my original jack design and the bear can be found below.  

## Electronics

The electronics were fairly simple -- I simply connected the servo and a button to my circuit so that when the switch is pressed, the servo will rotate to open the hinged door. I also then downloaded and reviewed the code/program for opening the jack in the box.

## Putting It All Together

When putting it all together, the following process was followed. I first attached two sides to the bottom piece and securely glued all 3 together. I then added another side and glued it to the bottom and adjacent sides. For the last side, I first carved out a hole so that the servo's wires could flow out and drilled two holes for the servo mount to connect to. I then attached the fourth side and glued it on. 

At this point, I screwed the servo into the server mount and attached the cardboard piece to the servo mount that would help open the top side when rotated. I attached the servo mount to the side with the holes I drilled for the mount, connected the proper wiring, and then made sure that my servo was rotating when the button was pressed. I also updated the code so that the open position was 70 degrees instead of 110, as my servo's initial position was already a bit rotated past 0 degrees (0 degrees being parallel to the the bottom of the box).

I then glued my bear "jack" to the top face of the box and attached the top face of the box through the hinge mechanism so that it could  open or close and made sure it did indeed open and close when I pressed the button. Lastly, I wanted to customize it so that the box stays open until "night time" when the animals have to go to sleep and stop "roaring". Therefore, I added a photo sensor to my circuit. I also altered the code so that once the button is pressed and let go of, if the light measure is higher than a certain value, the box will remain open. Only when the light level falls below a certain level will the box close and then can only be opened again by pressing the button.

## Final Deliverables

[My Jack Design STL](https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/JackMan.stl)

[Bear Design OBJ](https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/bear.OBJ)

[Jack in the Box Code](https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/motor.ino)

[Jack in the Box Video](https://youtu.be/3AtJwbNAvXA)

Additional photos of my box faces with etches, 3D printed bear jack, interior arranagment, and overall arrangement can be found below.

<img src="https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/IMG_9634.jpeg">

<img src="https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/IMG_9635.jpeg">

<img src="https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/IMG_9636.jpeg">

<img src="https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/IMG_9637.jpeg">

<img src="https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/IMG_9638.jpeg">

<img src="https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/IMG_9639.jpeg">

<img src="https://github.com/barkadosh1/IDD-Fa19_Lab5/blob/master/IMG_9641.jpeg">
