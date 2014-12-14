Manufacturing devices for the first time has been a definite learning experience.  From designing circuits and laying out PCBs, optimizing the antenna, prototyping the enclosure and cutting the injection molds, getting FCC certification, then ramping up to a full scale run in quantity.

It hasn't always been smooth, if at all.  Not every step was in the right order, and to add to the challenges we pivoted from a consumer product to a hacker device somewhere in the middle.

Probably the worst moment was when the excitement of our first production run of fully populated boards turned in to utter disappointment as we realized the boards were 1.2mm thick vs the 1mm specified.  High quality scrap as the boards would not fit our aluminum injection molded enclosures.  The molds were too expensive to redo.  So we were stuck.

Luckily, the PCB assembly house was rather accommodating in the end after many emails back and forth.   They agreed to do another run with the correct specs, and we would buy the fully functioning scrap at the cost of materials.

Not a bad compromise, but what to do with hundreds of boards with no enclosure?  A basic dev kit was the first thing that came to mind and a few clicks on the Mouser web site and we had a bunch of AAA battery boxes with leads to solder on to the board.  Not pretty, but functional if just developing and testing apps on your desktop.

However, the following weekend I was having brunch around my apt in the east village.  Afterwards I stopped by Cubo, a custom toy design store that prints in 3D, to say hi to Victor.  After describing our latest predicament, Victor had the idea of making a Star Trek communicator like enclosure design that hackers could print up at home.  This would definitely bling up the dev kit for DF1... but then the epiphany.

Our device is an accelerometer, which when at rest, can pick up the gravitational force of the earth straight down the Z axis.  If the board is tilted, then the force along the Z axis decreases, and increases along the X and/or Y axis.  Basic trigonometry can give the inclination of the device.

This can mean only one thing... A Bluetooth Low Energy Joystick! In a 3D printable enclosure.  This was the coolest idea yet, maybe even cool than our DF1 device in the first place.  I left Cubo rather excited, and Victor got to work on making a Joystick design.

With in a week or two Cubo came up with a highly stylized retro Joystick that was simple to print up and assemble with our too thick boards and off-the-shelf battery box.

Then JB at Device Factory got to work on the firmware.  As it turns out, a Joystick is a defined profile for a Bluetooth Human Input Device (HID) and can be directly coded in the DF1 firmware. Although, the latest Bluetooth Low Energy protocol is currently limited in direct OS support to Windows 8.  No worries... the rest of the world will eventually catch up and see the light in supporting Joysticks.

Mistakes do happen.  We learned a lot through the process.  Keeping good relationships with our partners allowed us to recover well and keep moving forward.  However, the unexpected path can be the most rewarding.  Now would anyone like a Joystick!?
