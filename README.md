# first-led-chaser
This project is meant to be an introduction to KiCad, as I have never fully, independently made a schematic before :(  Let's hope I can make this successfully!

## How to Use It
An LED Chaser is basically those glowing, flashy arcade signs that have a series of LEDs (not necessarily a series circuit, mind you) that light up in a particular order, whether it be every other LED that switches or the blinking LED follows a circular pattern.
It's purely for flashiness and style, and it looks cool!  For a project like mine, it can even show team spirit.  (Read more too see what team I'm making this LED Chaser for).

## Story and Why I Made This
First step of making the PCB is making the schematics.  In order to create a schematic, I used KiCad's schematic tool, and I placed a couple of components down, until I realized I needed to pull some components and their footprints (a footprint is what represents the component in the PCB editor) from a database called "Ultra Librarian" by Texas Instruments (they sponsor quite a lot of robotics teams).  After getting the needed schematics, I wired them together with the green copper lines, and learned how to use labels and global labels (global labels are the labels in the arrow shapes).
<img width="833" height="563" alt="Screenshot 2026-04-21 225134" src="https://github.com/user-attachments/assets/2dc073df-4e60-471a-8b12-7f3a06a3d637" />

When switching over to the PCB editor for the second part of my project, I had to assign footprints to every one of the schematics: this is where Ultra Librarian helped me out in finding some footprints thatthe KiCad default library doesn't naturally have.
<img width="1255" height="706" alt="Screenshot 2026-04-21 220703" src="https://github.com/user-attachments/assets/19ae1d23-0d11-4f17-af9f-ec58d98d19a7" />

after hunting down all the footprints, I made the PCB board's shape.  This LED chaser I made is in the shape of my FRC Robotics Team's (1771) logo, and wiring it all together with the front and back coppers, with the help of vias, wasn't too daunting of a task the more I connected components.
It kinda felt like a game, connecting all of them together :)
<img width="1824" height="1046" alt="Screenshot 2026-04-22 221644" src="https://github.com/user-attachments/assets/f78e950e-774e-4b0f-b04b-4cb42b4ebd73" />

Anyways, here's the final 3D result!
<img width="1068" height="602" alt="image" src="https://github.com/user-attachments/assets/ba01d023-78cc-465c-b9bf-4c20b442bae3" />

I'm debating on whether to make a case for it: I decided against it.

## BOM (my version)
0.01 uF Capacitors: [link](https://www.amazon.com/Cermant-Ceramic-Capacitor-Electronic-Components/dp/B09XV2CZJZ/ref=sr_1_3?sr=8-3)
1 uF Capacitors (and many more capacitors): [link](https://www.amazon.com/200PCS-Electrolytic-Capacitor-Kit-Electronics/dp/B0FH1R7N94/ref=sr_1_4?sr=8-4)
Connectors: [link](https://www.amazon.com/Glarks-Connector-Assortment-Stackable-Breakaway/dp/B07CWSXY7P)
4017BE: [link](https://www.amazon.com/Texas-Instruments-CD4017BE-Counter-Decoded/dp/B00GAGD10Y)
NE555N Clock: [link](https://www.amazon.com/ALLECIN-NE555-NE555P-Timer-NE555N/dp/B0CBKFMWDP)
T93YA: [link](https://www.digikey.com/en/products/detail/vishay-sfernice/T93YA103KT20/1587711)
In total, this project cost me about **$30** to make (yikes...)

## End Result
Fortunately, I got help from a friend when his dad agreed to lend me his solder and soldering iron.
When I initially soldered the PCB, [the blinking was really fast](https://drive.google.com/file/d/1CZGWTpNvm0oBers0KX6bNRDRQLqv2583/view?usp=sharing), even when I set the potentiometer to its "highest resistance" mode, which is stupposed to slow down the blinking rate.
After asking AI for help, I decided to replace the capacitor (which was originally 1uF) with a 10uF capacitor.
<img width="779" height="732" alt="image" src="https://github.com/user-attachments/assets/439833a5-f19a-4fda-a4db-95cdbe036d77" />
This solution worked, and after a few close burns, and the blinker works: a video of it blinking can be found [here](https://drive.google.com/file/d/13T7uWkx8QOqEzrhQr9J85-se3VObvKnz/view?usp=sharing) (the capacitor laying near the PCB was the 1uF capacitor that I removed).
Despite the blinker being a bit finicky at times, I learned a lot from this experience, and I'm still proud of the result.
<img width="2880" height="2160" alt="IMG_8237" src="https://github.com/user-attachments/assets/ba109837-4e09-4adf-ab22-0624610d925f" />
