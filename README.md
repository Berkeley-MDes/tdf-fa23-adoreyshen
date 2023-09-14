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

![](Screenshot%202023-09-14%20at%202.21.18%20PM.png)  

  
I made it by doing individual geometry sketches and then extruding it in Grasshopper. I made each part individually and then joined them together.

![10](https://github.com/Berkeley-MDes/tdf-fa23-adoreyshen/assets/143139247/bd0d28d1-a517-4ae0-bd72-fc6fd66194d7)


For example, this is the geometry of one part (the bottom base)


There was also a small issue I had when trying to laser cut: the actual thickness of the plywood was less than it said, making the gap I left for insertion too wide. It is supposed to be 1/4 inch which is 6.35mm, but it was only 5.35mm (annoying🫠). So I had to modify the ai. file at the last minute, and the dimensions are still a bit off. I glued the insertion part just to make them less flimsy. 


## Conclusion
It was a good attempt to try everything with grasshopper. Also it was really fun to play with the mechanical mechanisms. I think this phone holder can be a really useful item in my daily life now hehe☺️ For more detailed description of the project, it will be in the PDF file later!




