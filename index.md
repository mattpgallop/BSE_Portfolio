# 3-Joint Robotic Arm with Claw
My project is a robotic arm that can pivot at three different points, and it has a claw that can grab things. The arm is controlled by two joysticks which are connected to the Arduino in the base of the arm, which then sends information to the servos that cause the arm to move.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Matthew Gallop | Chatham High School | Applied Physics | Incoming Senior

![Headstone Image](https://cdn-a.william-reed.com/var/wrbm_gb_food_pharma/storage/images/9/2/8/5/235829-6-eng-GB/Feed-Test-SIC-Feed-20142_news_large.jpg)
  
# Final Milestone
[PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT} [PLACEHOLDER TEXT}

![Final Milestone](https://cdn-a.william-reed.com/var/wrbm_gb_food_pharma/storage/images/9/2/8/5/235829-6-eng-GB/Feed-Test-SIC-Feed-20142_news_large.jpg)

# Second Milestone
For my second milestone, I built the arm of the robot with the Arduino and the servos installed. I found the instructions for my kit online and then located all the pieces I needed. The build started with creating the base of the arm with the Arduino inside and the first servo acting as the joint that allows the arm to turn left and right. I then built the main section of the arm and the next two joints; the joints were created using two servos that allow the arm to bend vertically at two different points. The final part of the arm was the claw, and it was a little more complicated as it used gears and a servo so the claw could pinch together, but I eventually got it to work. Creating the arm was actually pretty easy as I just had to follow the schematics. However, it did take me longer than I anticipated because some of the images on the instructions were hard to understand. I also couldn't find a few pieces, so I had to improvise with some parts of the build.

![Third Milestone](https://cdn-a.william-reed.com/var/wrbm_gb_food_pharma/storage/images/9/2/8/5/235829-6-eng-GB/Feed-Test-SIC-Feed-20142_news_large.jpg)
# First Milestone
  
My first milestone was setting up the servos in my kit to an Arduino and then controlling them. First, I had to download the Arduino software to my computer, plug in my Arduino, and then connect the correct ports on my Arduino to the servo (ground, 5V, and a digital pin). I then had to figure out how to get the servo to move, so I used the internet to find out how to write some very basic code. When I got the servo to move, I noticed I could only turn it off by unplugging it from my computer, so I quickly realized my next step was figuring out how to use a button to turn it on and off. This part took me a while, and I had to go through a lot of trial and error to get it to work the way I wanted it to. After I got the button to work, I quickly moved on to control the servo with a joystick; I used two analog pins on my Arduino to map one servo to the x-axis and another servo to the y-axis. I then wrote some code for the Arduino to detect whenever the joystick went past a certain range, and if it did, it would send a signal to one of the servos to move. At first, the code I wrote was very clunky, and I wasn't able to move the servos how I wanted; however, by changing the amount the servo moved and the time in between the rotations, I was able to fix this.

[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1628084634/video_to_markdown/images/youtube--TIL9YxUkU94-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=TIL9YxUkU94&pp=sAQA "First Milestone"){:target="_blank" rel="noopener"}

![Code](https://github.com/mattpgallop/MatthewGallop_BSE_Portfolio/raw/gh-pages/Screen%20Shot%202021-08-06%20at%209.16.02%20AM.png)
