# Week 1 Report - Week of 08/31/2023
## Technology Design Foundations  


### Intro & summary

This week, I explored Rhino and Grasshopper to make a little change on the existing phone stand design. I also laser cutted the tweaked version of the phone stand.
The progress photos from this week are shown below!     





### Progress description

I first measured my phone's dimension (with my phone case on), since my case is a pretty standard one, it doesn't require much changing in width and thickness.
So my tweaked design's dimensions are:

width: 76mm  
length: 165mm  
thickness: 11mm  



  
Then I input all those data into the Grasshopper file

![Grasshopperphonedimension](weekly-reports/phonedimension.png)

After baking and export the file into AI, I just followed the instructions to change the color and path thickness in AI. Then for laser cutting, I picked 1/4" plywood as material since it's cheap (🫢) and five people shared one board!


Here's how it looks!

![phonestand](weekly-reports/frontview.jpg)
![phonestand](weekly-reports/backview.jpg)


### Reflection

This is my first time using Grasshopper and even I used Rhino (a little bit) before, the whole process seems quite overwhelming to me 🫨
The flow map in Grasshopper is massive and I only got to explore the few parameters that I am sure of.

However, I do believe this procedural model can be really powerful when we are trying to model a CAD in the context of many external factors. Instead of tweaking the specific dimensions manually in the CAD, this method helps a lot to save time for iterations under different scenarios. Moreover, its 'adaptive' function and Rhino's way of showing everything together definitely makes the connection of every factors more visually intuitive to understand.


Some of my considerations:

1. What other contextual observations would be useful to capture?  

  

It can be the distance and angle between the center of the screen to the focus point of the user's view. Also maybe the estimated using time since longer using time may cause posture change of user. It can also relates to the height of the user's chair (or the height extending from the table depending on user's height)


2. What other evaluations of results would be useful to provide as feedback?  


It can be subjective like how fatigue the user feels after using the setup.

3. Are there points in the process where you think AI…
   Could be used to assist? & Could be trained on input and output?  


   
   AI can definitely be combined with this process to make the iterative progress more smart. A direct feedback loop can be set up and AI can iterate within the range till it hits the 'sweet spot' range set up by the user. It can be further trained to suggest a more reasonable input and therefore generate a more accurate output.
   
   

   
   
   




         





</br>
</br>


***  

    

# Week 2 Report - Week of 09/07/2023

## Intro & summary

This week, I mainly focused on getting to know Rhino (and enjoyed the Labour Day weekend😁!). I watched some tutorials on Rhino on basic funcstions, and managed to design something (a hair dryer holder) with it.    


## Progress description  

### About Rhino  

Although I've done CAD before, but the logic of CADing in Solidworks and OnShape is a lot different than the one Rhino uses. So I took some time and firstly watched some tutorials to get to know Rhino.   
</br>

<img width="1401" alt="Screenshot 2023-09-07 at 1 47 45 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/1e62e835-323d-4971-94ea-2bd2a4501e24">  

</br>

<img width="1474" alt="Screenshot 2023-09-07 at 1 51 18 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/08869cb2-50ea-4afb-a236-37d80d15647a">        


</br>
</br>


I firsly went through some basic tutorial videos on both Rhino's websites and YouTube, then tried to make something myself without following the tutorial (will be explained in the next section!).   
</br>


After getting to know Rhino a little, I realise that instead of making a 2D sketch than extrude it, Rhino uses points to make lines, lines to make planes, and planes to make volume. I guess this logic gives Rhino more freedom when designing complicated shapes with many curves. Because based on my previous experiences with Solidworks/OnShape, it is ok to do regular shape modelling, but quite difficult and inconvinient to do fancy curvy shapes. I hope in the future when comes to designing something really curvy and complicated in shape, I can explore those fancy features in Rhino!  


</br>
</br>

### About the hair dryer holder  

Since I want to do something completely myself, my plan is to make something new (but simple so it's managable) through Rhino and 3D print it out later. What comes into my mind is a hair dryer holder since I kinda need it and don't wanna spend about 20 bucks on Amazon just to buy a simple holder...🤷🏻‍♀️   

Let me explain the idea a bit more: It is a simple hair dryer holder that simply sticks to the wall in my bathroom and can hold my hair dryer so it does't stay on the table sink anymore. I did some market research on Amazon first and found out most ones are like this:  

<img width="862" alt="Screenshot 2023-09-07 at 2 04 34 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/63cf7110-a9a3-43aa-8a79-fa4b4b4e2d7a">  
</br>

But what I have in my mind is just something that sticks out in the middle so can utilise the hollow middle space of the dyson hair dryer! So I CADed it out using Rhino and here's how it looks:


<img width="1512" alt="Screenshot 2023-09-07 at 2 06 22 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/df82fe7c-7597-4619-bcd4-c863421cf52c"> 
</br>

I basically want the back to be big so I can stick enough 3M strips to make it strong enough to attach to the wall (rented apartment can't destroy the wall😢), then I want the sticking out cylinder part to be similar diameter with the hollow part of the hair dryer so it can fit nicely and hang on it.   
</br>
  
    
<img width="981" alt="Screenshot 2023-09-07 at 2 13 02 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/ee0a7888-0e6e-4ad1-824c-6611bfbb52db">  
</br>


It's a simple design but I do get to explore some basics like Gumball, how to dimension exactly, how to snap points to the places I want, and how to extrude and fillet edges etc. To me it's a helpful exploration!  


Then I downloaded an existing CAD model of dyson hair dryer and assembled it with my design to see whether it fit:  

<img width="474" alt="Screenshot 2023-09-07 at 2 10 05 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/ae2ee560-f0c6-4d85-9cf4-6fb2867a0ad1">


It looks quite nice to me! So I export it as stl file and sliced it with Cura to get the GCode  

<img width="1512" alt="Screenshot 2023-09-07 at 2 16 57 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/29a0f6b0-cb8c-4ba8-963c-d9dd9b32b9fd">  
</br>
</br>

It's now ready to print. I am going to print it out tmrw and will post finished results here~
</br>
</br>


</br>
</br>
</br>
</br>

# Week 3 Report - Week of 09/14/2023

## Intro & summary

This week, I finalised Project 1 by making a new phone holder! It is a completely new design targeting to fix the problems with the previous one. And I also made a video about this 👉 [Adorey TDF Project 1](https://youtu.be/E8s9kIxx-nU) 



## Progress description

The problem with the previous one is that it can block part of your screen due to the holding rack, and the angle of your phone is completely fixed:
<img width="1006" alt="1" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/2f2419b7-316b-4395-a496-32287ac079b5">


#### To make it adjustable
I started my idea of making the angle adjustable. I think this function can be really important to me as I use my phone in various situations: I may look at it while standing up, or record myself doing something so the screen (also the camera) needs to face me. To make the angle adjustable, I began to explore the possible mechanisms, and a simple slot cam mechanism caught my interest: it’s simple enough so I can CAD it with Grasshopper (this is the key, grasshopper is too difficult for me 🥲), and it can be achieved easily with laser cutting! 

The slot cam looks something like this  
![1 5](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/651185d8-babc-4d4b-93b2-b6daa02795ad)

The slot will follow the curvature of the cam, so I can apply this to constrain the range of angles I want. I then first started CADing the rack with slot cam in it, it looks like this:

![2](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/75fc6132-cf8a-4f3e-aabe-bede2a1a80fa)

and the connector part for the slot cam
![3](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/d896c7c7-bf93-445e-b622-90f53095649d)


I made the curvature of the slot match the range of motion I want. It can go from 52 degrees to 93 degrees. I also positioned the location of the slot where the lowest position won’t clash with the racks.

<img width="1066" alt="3 5" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/31e09582-27b5-46b2-bfa0-9b82fb2be563">


#### Less screen blocking
After making the angle adjustable, I need to solve the problem of the “racks” blocking part of the screen while holding to it. Since the angle can be perpendicular, or even the phone can face down, you would need both hinges to hold tight the phone.   
![4](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/2b461dd7-8848-47b9-a280-1e376adb7c64)  
<img width="875" alt="5" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/4e28935e-66af-4438-bc64-8929b535cce8">



But with the hinges, it will definitely block part of the screen, and the attachment and detachment of the phone will be less straightforward. 😨

So one of my phone accessories caught my mind: MagSafe! I can use the built-in magnet of iPhone to make it strongly attaches to the holder, capable of hanging at any angle.

![6](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/a0bd4c79-901b-419d-93ed-e2cf0ed2bd6b)


and can even let it rotate from landscape view to portrait view!

![7](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/19926281-5aee-4bad-ba34-48cfc3f0aeee)



So in order to attach the MagSafe accessory, I engraved the top board to leave a space for sticking it:
![8](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/415f669a-5a31-4d09-bbfd-6c9662e50ae2)


#### So the overall phone holder looks like this:

<img width="601" alt="9" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/7bf3bc5a-8683-48d4-97a3-c05ac64c9f38">


## Challenges
The challenges I encountered were mainly with Grasshopper. Because I am completely new to this, it took me a while to get on the right track. (really long🤕) There are four different pieces in total, each with a relatively complicated geometry. 
![10](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/31640424-f7fc-4b06-8649-391f042a3f4a)



  
I made it by doing individual geometry sketches and then extruding it in Grasshopper. I made each part individually and then joined them together.

![11](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/65e948b2-7957-41d5-9903-58e602cfee0d)


For example, this is the geometry of one part (the bottom base)


There was also a small issue I had when trying to laser cut: the actual thickness of the plywood was less than it said, making the gap I left for insertion too wide. It is supposed to be 1/4 inch which is 6.35mm, but it was only 5.35mm (annoying🫠). So I had to modify the ai. file at the last minute, and the dimensions are still a bit off. I glued the insertion part just to make them less flimsy. 


## Conclusion
It was a good attempt to try everything with grasshopper. Also it was really fun to play with the mechanical mechanisms. I think this phone holder can be a really useful item in my daily life now hehe☺️ For more detailed description of the project, it will be in the PDF file later!


</br>


</br>
</br>
</br>
</br>

# Week 4 Report - Week of 09/21/2023

## Intro & summary

This week, we finished the previous computational design project and started with the microcontroller ecosystem project! I also finally printed the hair dryer holder from week 2😛.  



## Progress description

Since the project is still at beginning, I just followed the tutorial to set up the photon 2 microcontroller. I also explored some exisitng projects online to get some inspiration for the potential project. 

And for the printed hair dryer holder! Here it is:

![IMG_5456](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/574575e0-656f-434d-983c-258c26a46bcc)
![IMG_5455](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/dd470ad7-9740-4168-9f66-efca210380f9)
![IMG_5454](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/316aed91-70c3-49bd-bafe-387662ba9f38)


It worked very nicely! And the big base provides bigger surface for my Command stripes to work nicely~



</br>


</br>
</br>
</br>
</br>


# Week 5 Report - Week of 09/28/2023
# Intro & Summary
This week, we did an idea-generation session on Monday, and when I was selecting the potential projects I may work on, I did some research on the feasibility of the projects and what are the potential methods to achieve it.  

# Progress description
The first choice of mine is the flower that opens up and closes down to help people meditate. The idea was proposed by my group, and the rough idea in my mind was to make a physical mechanical flower that mimics the Breathe app user interface in Apple Watch:  

![result-6](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/80bebd47-e5ca-46aa-84b1-fda97b448095)



A potential physical mechanism can be something like this:

![Telling+the+time+02](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/feb93ac6-face-4db1-a833-88a6a0d0eac2)


It is a design of a dynamic clock, but it uses a stepper motor to drive the ‘flower’ mechanism open and close and make it sync with the actual time in settings.

My idea can be similar to this, but instead of syncing with time, it can be the pace of meditation breathing and a separate device that vibrates and can be worn by users to guide the meditation session. A speaker can even be added to play soothing music and guide the meditation session better.


The second idea I chose is the wind chime. Since the project is more art-oriented to me, it doesn’t have a specific input yet that will cause the wind chime to play. Some factors in my mind would be: 

1. humidity sensor - so that when the air is wet it will play specific tunes to match the mood
2. LDR - so when sunlight is at different intensities it will play specific tunes to match the mood
3. or a remote keyboard as TUI for users to input their wanted tunes!

Something that may look like this: [Arduino Controlled Wind Chimes](https://www.instructables.com/Arduino-Controlled-Wind-Chimes/)   

![hqdefault](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/ce649f23-fac6-43ee-9c7c-bc56b66e409f)


The thrid choice I picked is the smart lock system. The concept is really useful and the first thing that come to my mind is switchbot door lock!

![c646ed8c-d770-4515-a530-41bca0e14b0d __CR0,0,2400,1800_PT0_SX600_V1___ png](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/9d831065-f9b4-41be-879f-85ebe9e4a40e)


I’ve been using it for a while and it’s really useful! It’s a mechanism that fits universally to a door lock and turns by certain degrees to lock it. So according to user settings, it can do self-locking, and unlocked easily by phone apps. 

We can achieve this by Photon by designing a door-lock fit mechanism and attach it to a stepper motor, and make the input trigger by a remote control: like a button for users to push, or even a NFC chip that works when the phone gets closer to the sticker!


</br>


</br>
</br>
</br>
</br>


# Week 6 Report - Week of 10/05/2023
# Intro & Summary
This week we worked further through our idea! Including both ideation and technical solutions!  
The detailed project specification is right here: https://docs.google.com/document/d/1IRLeagtgZijVZ8jcxHtoBIZcy9kE9jKGmdVBJSnqfk4/edit#heading=h.nm9ytp95gaks
and the Figma file showing the ideation process is there: https://www.figma.com/file/QtvoujYCLwyQF9pJV33fz6/Ideation?type=whiteboard&node-id=5%3A36&t=583Ur4PRHsifJNPF-1



</br>


</br>
</br>
</br>
</br>


# Week 7&8 Report - Week from 10/05 to 10/19/2023
# Intro & Summary
During the two weeks, we spent a lot of time developing into the idea and finished up the prototype. I was responsible for all the electrical and circuit parts, and I was helping out a lot on the assembly and testing of the mechanical flower.  

  
# Progress description
### Electrical part
The main circuits involved are the vibrator motor that goes to the wristband, and the servo that goes to the mechanical flower. 

#### Vibrator Motor
The vibrator motor is fixed on the wristband, with the vibrator motor side facing the skin of the user. Its vibration frequency and intensity increase and decrease to hint at breathing in and breathing out, which also matches the rate at which the flower opens up and closes down.

![image 3](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/fca13136-724b-4e5a-8840-f08eae71aa09)


The original circuit of the vibrator is really straightforward: red line to 3.3V and blue line to D7 for digital output. It is basically the same logic as blinking an LED, with D7 shifting between high and low to let the vibrator motor operate or stop. It works fine for initial testing, but since it is a digital output which only allows binary states (on/off), it is difficult to mimic the effect for breathing in and out. Therefore, I wanted to switch to an analogue output for more vibration modes (also I was told to use the DRV2605L Haptic Motor Controller🫣).


<img width="500" alt="62GfTF2lolxTpnWn0nJSS4hXOIy5yYQRLsM5LcjZQ_TlsLBCUpSk6r_zRhLIBTUnqjQXeS87O1QqrMkuA3rhgbddMm31ePQS0C-07b1exd-5viFv1JnodAysSiJG6kTrhAy6S2Bya-aQpuEh1XhE-XM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/e526f2ac-d27c-4552-b755-2e2e7bf7c690">

![image](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/cdae9d7d-dce7-4b49-a9cf-3a672542507d)

<img width="500" alt="image 4" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/e403b197-f870-4a61-9d4c-8726c25d905c">  

⬆️The circuit schematic, testing, and the sample code (same as Blink an LED)

After researching and asking for help from the lecturers, I soldered the vibration motor to the Adafruit DRV2605L Haptic Motor Controller and subsequently connected it to the SparkFun Qwiic Shield. Since SparkFun is an add-on shield, I soldered the female headers to it for attachment to the Photon 2. Also, I did some initial tests to make sure the circuit worked before passing this to the programming team.

![image 2](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/6970fd9d-298d-463a-a867-467a7cbb6c21)
<img width="500" alt="Screenshot 2023-10-23 at 5 43 58 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/6501bd05-4777-400d-bc4b-578d9a75452b">

It took me a while to understand the logic of controlling the vibrator motor through the SparkFun Qwiic Shield since it is not directly connected and controlled through one pin. Thanks to TJ and Sudhu, I got to know the logic behind which is the i2C protocol and now the parts connected to the Qwiic Shield can be easily controlled by the defined part code inside the code. Here is the sample code I got for the vibrator motor:

<img width="500" alt="Screenshot 2023-10-23 at 10 49 22 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/cefc9769-a589-4a05-8836-caa4499ae199">

It is a giant library which contains 123 effects of vibration modes, and we later picked and modified some of the effects to make it match the result we wanted for the vibration wristband. 


#### Servo
The servo directly controls the opening and closing of the mechanical flower. Strings which are attached to the petals are attached to the disk, and the disk subsequently attaches to the servo. Therefore, when the servo rotates, the distance of the strings from the petals gets shorter or longer, which can cause the flower to open/close. 

![IMG_377E9C724E0A-1](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/42c09e6f-c523-4eb2-9cb2-b3b0bac0dd7b)
![IMG_318C69927AC1-1](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/8a3878ea-47f9-44a0-ae88-750ccdf5cba5)

⬆️When the disk rotates, the string ‘retracts’, shortening the distance and therefore lifts up petals

The circuit of the servo is really straightforward as well: orange wire to D1 (a pin which supports PWM), red wire to 3.3V (or bigger voltage, which will be explained later), and brown wire to ground.

<img width="500" alt="Screenshot 2023-10-23 at 11 03 26 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/84bdb9ad-7735-484b-84fe-1cdf1aa734e4">

Although the circuit seems straightforward, it took me a really long time to test the circuit. All the tutorials I found online used D0 or A1 as the signal pin, and I didn’t rethink the assigned pins when the circuit wasn’t working. I was assuming there were some issues with the code or even the servo instead of me using the wrong signal pin. Then after struggling for one hour, I saw some tutorials mentioning the signal pin must support PWM, then I referred back to the datasheet of Photon 2 and realised the pins I tried didn’t support PWM. Right after I changed to the right pin, the servo worked normally. 

<img width="500" alt="Screenshot 2023-10-23 at 11 19 50 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/740081b5-4823-4a37-884b-6b5209aabdee">

Since the motion required by the servo was to rotate clockwise and anti-clockwise to retract and extend the strings of petals, the code simply needs to command it to rotate back and forth. The sample code is shown below:

<img width="714" alt="Screenshot 2023-10-23 at 11 22 39 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/c7242aeb-f5cd-474d-bbb4-1e44f3b0707f">
After many tests on the final prototype, I figured out the right angle (which is 90 degrees) to retract the petals in the right amount. I also tweaked the delay in the middle of the motion to make it match our desired pace of breathing.

We also experienced a challenge when using the servo to drive all five layers of petals: the torque provided by the servo wasn’t strong enough to drive all five layers, it was trying to rotate but ended up shaking a bit and then going backwards. I looked up the servo data sheet and realised that it can operate with 6v for bigger torque:

<img width="881" alt="Screenshot 2023-10-23 at 11 49 56 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/2bebf697-e5ee-4bd5-9b94-16f0e90e05bf">

Therefore I tried to fix this situation by using a bigger power supply instead of the 3.3V supplied by the Photon 2, and the circuit schematic looks like this:
![0a77894b0bb506adea1f135c1df8f970](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/92e8f361-76bb-4d7e-8518-bc7efff4b2e6)

![F5W81DAIUG0UQ57](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/127e75de-436d-40e0-97e9-d66502f42554)


The schematic is like this but with brown wire to GND and yellow wire to D1 of Photon 2

However, it was lifting a similar amount of petals as well, as the torque didn’t increase as it was supposed to (should be almost doubled?). As a compromise, we cut the fish wires for the bottom three layers in the end just to have a working prototype.

#### OLED Screen
Originally, we wanted to use the OLED screen as a display to indicate ‘breathe in’ and ‘breathe out’ for the users right next to the flower, and I did some initial OLED screen research. Also since we already had the Qwiic Shield which makes it a lot easier to control multiple accessories connected to it. However, since our programming team developed a web-based user interface, the laptop screen itself with the button acts as an interface with the instructions showing the screen. This replaces the need of an OLED screen.

![IMG_1BBEC787E916-1](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/df02de98-daec-4b16-b4cf-3e00497b1497)
The laptop screen shows the instructions for ‘breath in’ & ‘breath out’


#### LEDs
We also wanted to put an LED inside the mechanical flower to provide a better ambience for the meditation experience. It should switch analogously from on to off matching the pace of the mechanical flower. I also made the circuit as well as tested out the code for a breathing LED:

<img width="500" alt="Screenshot 2023-10-23 at 11 36 48 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/5087e280-b27d-45f8-9765-4c1f30fe58af">
![IMG_7FA04A52F850-1](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/b7e6bec4-b1ac-437a-bdbf-fa65f34bc088)
However, the LEDs were really tiny and it is really only suitable for signalling, we didn’t go with this in the final design. I also tried to use the Neopixel LED light strip:
<img width="500" alt="Screenshot 2023-10-23 at 11 56 16 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/e5697e64-c5d7-4581-b321-d11ac46326e4">

I soldered the pins but because I wasn’t able to access a 1000uF capacitor and we were running out of time, we decided to give up on the LED feature in the end.

### Mechanical part
I actually spent most of the time on the project helping Yuhe with the mechanical flower model. Since she designed the whole mechanical model, I was helping her tweak the design as well as doing the manual and laborious work of assembling the spherical frame as well as petals. 

There were many details of the flower as we did the testing and prototyping. For example, we realised the metal ring joint fixture wasn’t suitable for the design as it was flimsy and the petals would move in all directions instead of just up and down, we switched to zip ties for better joint fixtures as it is flat and easier to use: 

<img width="500" alt="Screenshot 2023-10-24 at 12 02 42 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/db03eee0-a511-44ca-80f3-d454966c8afc">

We also spent a lot of time attaching the petals to the fish wires and fixing each petal at the exact location on the wire by glueing. For a better look, we also spray paint the petals white to get rid of the burn marks on the petals of laser cutting. In general, the mechanical flower was really a delicate and detailed prototype, and we spent a lot of time perfecting the small details involved.




</br>


</br>
</br>
</br>
</br>


# Week 9 Report - Week from 10/19 to 10/26/2023
# Intro & Summary
This week, we were introduced with the new LLM project. I followed the tutorials during the lectures and watched the replay for some parts i was confused. I didn't do much other than catching up with the lecture contents🙈


</br>
</br>
</br>


# Week 10 Report - Week from 10/26 to 11/02/2023
# Intro & Summary
This week, we finished the project 3. I finished tweaking MINI Adorey, and made a final demo video.


# Progress description

### Overall structure of mini adorey
I have 6 instructions in total: one about the speaking tone of the bot: I customised it to be chill and with emojis 
One about my personal info, which is linked to a knowledge set
One each for project 1 and 2, and the class wiki, each of them is linked to an individual specific knowledge set for the corresponding contents 
and a welcome messsage instruction!


The major problem I encountered when doing this is the token issue
Initially after inputting all my weekly report and project report, when I asked the bot of some basic questions. The error prompt kept popping out: I didn’t record it the first time but according to the prompt, I’m pretty sure it’s because of the token limit. So I went back and check the tokens taken by my knowledge set: it’s within 5 thousand and the max token limit of gpt4 is about 8200. I was confused but I think this maybe the issue: as all the contents are chunked up in one, it’s taking longer for it to find the right info I need. So I split up the whole chunk of info into 7 pieces: each weekly report is pne piece, I also splinted up the sections of the final project report into parts like speculations, reflections etc, so it’s easier and faster for the bot to fetch the needed info.


### tweaking of language 

There is also some tweaking of language. I originally asked for the bot to have some emojis but I realised it’s using a bit too much. I also quantified the word to be around 300 at first, then I realised this is causing the problem of the bot answering questions with similar amount of words for both basic questions and technical questions. This makes the answer too long for a question like who am I, but too short for a question like describing a challenge in project 2. So I added more detailed instruction for word limit for different types of questions, and here it is! It’s now Answering different types of questions with the right amount of details~


### Different LLMs
I also tried using different large language models. The one I’ve been using is gpt 4. And I tried switching to gpt 3.5 turbo. I feel like it is answering questions a bit faster, but the tone and langue’s it similar. I also tried with chat bison 001 but it seems to be confused. It was saying not having access to my info 🫣

### Different Temp
Finally, I’ve been trying with different temperature. Since this one is related to the creativity of answers. I made the question to be What do you think should be my dream job and what my future life will be like. The one I’ve been using is 0.8, but I also tried tweaking the number to be 1.5 which is supposed to be a lot more random than before, and as you can see it is definitely more random it’s producing words and sentences. I don’t even understand. I also tried making the numbers smaller like the 0.2 and you can tell it’s definitely giving more realistic and less imaginative answers 


</br>


</br>
</br>
</br>
</br>


# Week 11 Report - Week till 11/09/2023
# Intro & Summary
This week, we started up the final project and we started with the ideation stage on project proposals. 

# Progress description 
I generally have few ideas:
1. a smart therapy lamp for SAD patient (seasonal affective disorder) that can detect the distance between the lamp and the user to adjust the light intensity for better user experience.
2. a plant interation system that can be implemented on a plant for human interaction. The plant can respond with voice and OLED display when people are touching its leaves. It will act as a smart desktop electronic companion.

I will look into more details in terms of the feasibility of the project as well as a potential part list that can be used for this project. My personal preference for now is still the plant one since it can have multiple add-on features. 

Some general researches include using a capative sensor conntected to the plant for it to have a response based on human touch:

![IMG_6385 1](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/8415a904-b9d3-4b30-bede-135ce28d23ef)

and a OLED screen with a speaker for output of the plant:
![image 5](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/019aad23-8ab6-4cc2-9bcf-28a65ddb58e0)


I do believe there are various possibilities with this project with many potential fun features: e.g. soil moisture sensoring for watering reminder, moving plant on a vase for advanced interation, smart response from the plant by integrating with LLM apis.




</br>


</br>
</br>
</br>
</br>


# Week 12 Report - Week till 11/16/2023
# Intro & Summary
This week, I finallised my final project idea and started to buy components for prototyping.

# Progress description 
Surprise surprise Lmao I didn't go with any of the suggestions above and decided to do an alone project of a curtain robot. It's basically mimicing the functions of something like this:



https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/4be30f91-349a-4bc6-b449-efb42333dab6

I lookede through a bunch of YouTube videos doing testing of the existing products in the market, and I think the internal parts of this kind of robots are pretty straightforward, it has:
a dc motor as the major wheel to go across the rod;
<img width="508" alt="Screenshot 2023-11-30 at 1 28 01 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/3f09b572-bac8-4b76-b464-317721e8b915">

a hall effect sensor and few tiny magnets on the wheel to keep track of how many revelotions it went; (i watched a bunch of YouTube videos to figure out the mechanism of hall effect sensors, there're actually super cool!)
<img width="651" alt="Screenshot 2023-11-30 at 1 28 41 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/dcbe21d2-ee8f-4720-969d-da5e6ad9e9a1">

a receiver (normally controlled through internet or bluetooth);
and a smart mechanical design part of the hook to make it the right tension for the bot to move.


### Motor
So to do a step-down for my project, i had three ideas of the motor, and i want to ask for help today during the consulting session:
1. DC motor with a tiny magnet+hall effect sensor, or just use a motor shield to control the rpm. also, does it know how many revolutions it goes?
2. Stepper motors? Cuz they're more acurate and stronger, but heavier and more difficult to control
3. or should i do distance sensors (like ultrasonic sensors on both sides, or just other types of mechanical triggers) or just hard code with the rpm feedback from the dc motor/motor shield

## Remote function
Since the bot should be high up in the reality, a remote control would be ideal instead of pushing the button manually on the bot. So i decided to go with an IR receiver with a remote control (tutorial: https://www.youtube.com/watch?v=0DgALFDwouA). I've placed the order on Amazon already!

Looking forward to the testing stage!!!

</br>
</br>
</br>
</br>


# Week 13 No Report - Week till 11/23/2023 - Happy Thanksgiving holidays yay!!!

</br>
</br>
</br>
</br>


# Week 14 Report - Week till 11/30/2023
# Intro & Summary
It's almost final week, I am a bit running out of time of the final project 🥲. I've been working hard since I am back from thanksgiving holiday, and there's what i've done so far:

# Progress description 
## Motor + Trigger
After previous discussion with instructors, I decided to go with dc motor + physical triggers! A self-made hall-effect sensor with magnets can be difficult to calibrate, and can easily fail... And a stepper motor just seems like it's a bit over-qualified for the job! Also stepper motor is a bit heavy so I am worried about the weight the bot can carry.

So the final decision is a dc motor (TT motor provided by TJ (Thx!😀)) with two limit switches on the side. So when the bot moves till the end, the limit switch will be triggered by the wall to let the bot know to stop moving.

I've used a doubler to make it vertically more compact and a DC Motor feather wing to control the motor:

<img width="489" alt="Screenshot 2023-11-30 at 1 40 19 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/f7856d3b-7057-4a7b-835c-5f17b17172e5">

And after a lot of help from Sudhu and lots of struggling from myself, there's the first successful testing video: the dc motor will stop rotating when the limit switch is triggered:



https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/292352a7-e76f-4d3c-b1ee-536db68ae383



## Remote control (aka downgraded physical button right now)
After I received my Amazon package of the IR receiver and the remote control, I did the testing right away following a tutorial on Arduino. Unfortunately, I can't manage to figure the library file out, it seems like the library is not supported by Photon 2. I did a bit of consulting with Shm and tried few methods but it still didn't work out😖

![image_720](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/8e5aac1f-23e0-4daa-bf5d-3e65734f643f)

So instead of being strucked at the beginning, I decided to go with the simpler version of control - physically buttons - right now.

So the idea of control is basically, when "going left" button is pressed, the motor goes to the left, until it hits the wall on the left (which is when the left limit switch is triggered), and when "going right" button is pressed, the motor goes to the right, until it hits the wall on the right (which is when the right limit switch is triggered).

The logic seems easy, but I've got four different switches to control one motor, and lots of bugs did happen during the testing (sometimes just because of an unhappy pin!(same code same connection, but when i changed to a different pin, it worked...)), here's the thing that FINALLY WORKS!



https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/8af8a508-7126-4c57-a778-43b9cab13be3


## Mechanical shell design
I need a physical shell to contain all these eletronics above, so I started the simple cading of a shell that can contain all the conponenets inside:

<img width="902" alt="Screenshot 2023-11-30 at 1 54 31 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/0909428f-49db-499f-bbaf-05c1ba6670fe">

This is the original CAD that's supposed to be 3D printed. The dimensions are tailored around the actual dimension of the components. The holes are left for the wires to go through. I haven't started the arm design yet.

Unfortunately... with everyone's final coming, I can't find a single 3D printer available for used... And my design does requires iterations to test for the tolerences...I decided to go with laser cutting. I basically used the (almost) same design, but sliced them into multiple layers:

<img width="666" alt="Screenshot 2023-11-30 at 1 58 39 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/28e989c1-b863-47b6-a5be-303e5fc16012">

I also left some tiny holes for the zip times to go through to fix the dc motor in position.

<img width="401" alt="Screenshot 2023-11-30 at 1 59 00 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/889ae229-25ea-4899-9392-409e970f2680">


I've cut it out and glued the layers together, but i forgot to take a picture...

I'll put more update of progress here!



</br>
</br>
</br>
</br>


# Week 15 Report - Week till 12/7/2023
# Intro & Summary
This week I worked really hard and finished the project! There's my final project description!

# Progress description 
### Mechanical
The mechanical part covers the design of the physical body of the bot. It is mainly the ‘shell’ that fits all the electronic components, the hook at the top of the bot that goes to the curtain rod, and the wheel that pressure fits the TT motor.

<img width="1093" alt="Screenshot 2023-12-09 at 11 38 20 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/da9be9a3-59c4-4147-9f93-d6c909440d64">


#### Physical Body - the ‘Shell’
The idea of the physical body is light, compact and capable of fitting in every electronic component. Originally, I wanted to 3D print the body and drafted the CAD aiming for 3D printing. I measured all electronic components and made specific CADs for each of them (the blocks) so I could assemble everything in the ‘shell’ to see whether they fit. Here’s a screenshot of my original CAD model for 3D printing:

<img width="1103" alt="Screenshot 2023-12-09 at 11 44 12 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/27f1047b-b2a3-4c61-b4de-4853878cd694">


However, all the 3D printers were super busy in the maker space as everyone was busy with their finals, I had to switch to a different approach: laser cutting. I basically sliced my previous 3D print CAD model into four layers, laser cut four layers and glued them together:

<img width="1028" alt="Screenshot 2023-12-09 at 11 48 00 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/0129d629-c431-466d-a808-be07f37fbd67">

Here’s the laser-cut sketch. I also included some details like space left for zip ties to secure the motor in place, they’re super helpful.


<img width="1098" alt="Screenshot 2023-12-09 at 11 48 31 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/a2d24a1c-38d6-45ce-99d7-e5db934e3d84">

Although it’s a little bit heavier and bulkier than 3D print, the laser-cutting process is so much faster, and did a fairly great job as well!

#### Hook
Similarly, the hooks were made with four layers of laser-cut plywood as well. Originally, the idea of the hook should have two rollers at the bottom side to decrease the friction. The size of the hook should match perfectly with the diameter of the curtain rod and the wheel size. So I made the hook in the exactly dimension to give some space for tolerance.


<img width="895" alt="Screenshot 2023-12-10 at 12 04 49 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/d535ba83-bd36-467a-aa4a-3b0656854f67">



However, due to the limited time I had and because the whole structure was laser cut and glued together, it was difficult to achieve it with the rollers. I eventually gave up on the rollers, but added some smooth paper tape on the bottom of the hook to decrease the friction.

#### The Wheel
The wheel needs to match perfectly with the extrusion bit of the TT motor:


<img width="933" alt="Screenshot 2023-12-10 at 12 11 37 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/77aea2c6-e552-4626-b3fc-9b463be5e6a6">


The wheel was 3D printed as it was a smaller part so it only took a short time to print it out. I test-printed a few partial CAD models to see whether the tolerance worked with the extrusion bit before I printed the final version. The 3D-printed wheel also has a tiny amount of difference from the actual defined version probably due to the heat expansion. 

After figuring out and printing out the wheel with the right dimension and pressure fit to the DC motor, I added some rubber bands on the side of the wheel to increase the friction. After many other tests with the whole thing on the curtain rod, I replaced the rubber band with electrical tape. I also added some electrical tape The final look of the whole mechanical part looks like this:

<img width="1097" alt="Screenshot 2023-12-10 at 12 19 41 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/f5d8220a-b905-4fc9-8594-1f4ebad86a34">



### Electrical
The electrical parts include: DC (TT) motor, two limit switches, two control buttons, Photon 2, motor shield, doubler, a switch button for Photon, battery box for motor, lithium battery for Photon, and a soldered breadboard.


<img width="821" alt="Screenshot 2023-12-10 at 12 23 15 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/79429fab-0e34-486f-9af2-16c4de5efcfe">



In general, every electronic component was there to control the DC motor. The DC motor connects to the motor shield and is directly controlled by the built-in library. An external power supply (the battery box) directly feeds power to the motor shield to power the DC motor. To add on to the direct control, the switches were added to define the scenarios of the behaviour of the motor. Four pins were assigned to four switches.

The photon 2 and the motor shield are connected together by a doubler. It is effectively doing the job of connecting them on top of each other but remaining parallel next to each other in one layer. The small little lithium battery is there to power the photon 2, and I also used the designated switch for photon so it’s a lot easier than plugging and unplugging the battery. 

Since the Curtain Bot needs to move around, all the circuits need to be secure. Therefore, lots of soldering was done. I replaced the temporary breadboard with a soldered permanent breadboard after testing the circuits. I also tried to make the circuits as compact as possible.

<img width="1102" alt="Screenshot 2023-12-10 at 12 35 07 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/a8fc0e53-00e3-470c-b71c-d1e24f4ee9c7">



### Programming
Overall, the idea is to use the states of the switches to control the motion of the wheel. I did all the simple testing of each component and then tried to combine them. For example, I first did the testing of the motor going forward and backwards, and the serial monitor showed the state of each button switch and limit switch when pressed (simple testing of individual components). 

Here’re the tests I went through before combining them all together:

<img width="369" alt="Screenshot 2023-12-10 at 1 52 53 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/4adb7811-3d59-43e2-be5e-5c1888b5305a">

After that,  I tried to combine the motor code with the limit switch code. With a lot of help from Sudhu, we figured out the logic of the code in pseudocode like this:

![IMG_7386](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/2ca39111-6f31-44f0-a245-417462438e95)


And here’s the main logic of my final code:

<img width="559" alt="Screenshot 2023-12-10 at 1 40 53 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/d15fd58a-6b17-446f-9af7-aa06398f5fe4">
















