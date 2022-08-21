## 12/17/2021 - Reverse Engineered iPhone 7 📱

![iPhone7](https://user-images.githubusercontent.com/87344382/185779797-e47f1aa6-55f7-42c0-949e-286844b9c607.png)

<h3>Tools</h3>
<ul>
  <li>Tweezers</li>
  <li>Wrench</li>
  <li>Pliers</li>
  <li>Screw Driver Set for Small Screws</li>
  <li>Clean Surface</li>
  <li>Plastic Bag for Disposing of Components</li>
</ul>  

<h3>Motivation for the Project</h3>

Another iPhone to experiment on!!! I got this iPhone 7 after it was dropped and the screen completely shattered. This time I decided to look more in depth in the iPhone and break open the circuit with a wrench. After bending the metal completely to expose the circuit I finally got to see the capacitors, resistors, and ICs that get the camera working, the screen, and the phone overall. Yet, what really shattered my mind was the Apple Taptic Engine not because it was a pain to open as seen in the last picture in the gallery above with the magnets and coils, but it shows me the application of electromagnetism.

From what I observed, it seems that the reason why when you tap your iPhone such as opening the Calendar app the magnets in the engine move to induce a current between the copper coils. The current then travels to the circuit board to get processed by the ICs and produce the expected output, which was in this example opening the Calendar app. I did research the A10 Fusion, which is the IC (integrate) that makes the iPhone a computer and it is often referred as a system on a chip (<a href="https://www.notebookcheck.net/A12-Bionic-vs-A10-Fusion_10166_8178.247596.0.html">NotebookCheck</a>). I still have more to learn about the Apple Hardware, and it will take time, but I am finding myself enjoying the process of learning the computer architecture.


## 12/17/2021 - Reverse Engineered iPhone 5C 📱

![iPhone5Cgallery](https://user-images.githubusercontent.com/87344382/185779772-c8210807-dd4a-47db-8566-011a6cd213fe.png)

<h3>Tools</h3>
<ul>
  <li>Tweezers</li>
  <li>Screw Driver Set for Small Phone Screws</li>
  <li>Plastic Bag for Discarding of Components</li>
  <li>Magnifying Glass to Read Text on Components</li>
</ul>  

<h3>Motivation for the Project</h3>

During my winter break, I decided to open my iPhone 5C, which I had since freshman year in high 
school until I dropped it on the garage floor and the front screen completely shattered. 

However, out of curiosity and an attempt to understand how iPhones are designed I got my screwdrivers and 
tweezers out to begin disassembling. 

I got the cameras out first, but I could not salvage them as 
it would not be compatible with my Raspberry Pi. 

I then took out all the components from the speakers 
to the circuit boards, but I did not think to take off the covers on the circuit boards, so I just 
studied the lithium battery and speakers. 

However, in the end I discarded all the parts safely by 
putting them in a plastic bag and disposing them at the Electronic Waste area at Best Buy. 

Although, unsatisfied at only seeing the battery, cameras, and speakers I know next time I will take more time 
to take account of the names of components and research them me thoroughly.


## 10/19/2021 - Doorbell Circuit

![DBTgallery](https://user-images.githubusercontent.com/87344382/185779651-bc076c63-c5bf-463e-80a8-4dfbe9c8d37b.png)

<h3>Tools</h3>
<ul>
  <li>Soldering Iron</li>
  <li>Solder</li>
  <li>Male to Male Jumper Wires</li>
  <li>Perfboard</li>
  <li>LED</li>
  <li>Button</li>
  <li>2 AA Battery Pack</li>
  <li>Piezo Electric Buzzer</li>
  <li>1 2.2 k<span>&#8486;</span> resistor</li>
</ul>  

<h3>Motivation for the Project</h3>

My first functioning soldering project is this doorbell circuit I crafted on a perfboard. However, it took three failed attempts to make it correctly since I faced difficulty creating the solder joints to the leads of the battery pack, so what I did to resolve this issue was to solder wires to complete the connections between components, which worked well. 

As seen in the second picture when the batteries are placed in the battery pack all that must be done to activate the buzzer is pressing the button in the middle, which will also cause the LED to light indicating the buzzer is on. 

In my failed attempts, cold solder joints and excessive solder were my demise, so this time I was quick with the soldering iron and tinning the tip after each connection to ensure the solder would stay in place rather than joining in one spot. 

Creating this doorbell circuit inspires me to take future soldering projects, which I recently discovered there are an abundance of soldering kits online to take on.

## 10/03/2021 - SMD Soldering Practice Board

![SMTPractice](https://user-images.githubusercontent.com/87344382/185779624-f1214c65-3222-4a61-b6d7-912b95c372e4.png)

<h3>Tools</h3>
<ul>
  <li>Soldering Iron</li>
  <li>Solder</li>
  <li>1 - 2 AA Battery Pack </li>
  <li>Helping Hands</li>
  <li>Magnifying Glass</li>
  <li>Tweezers</li>
</ul>  

<h3>Motivation for the Project</h3>

I received the <a href="https://www.amazon.com/Gikfun-Welding-Practice-Soldering-Training/dp/B00VWB8F8K">SMD Soldering Practice Board </a> as a gift during Christmas, but I delayed the project to garner more soldering experience which I did with my doorbell circuit that took four attempts to successfully complete. Now that I felt comfortable with through-hole components I decided to get comfortable with SMD components, which has resistors and capacitors that range from 1206 to 0402 sizes. My eyesight is not the best so when it came to soldering the 0402 and 0630 resistors and capacitors I used a magnifying glass from a <a href="https://www.amazon.com/Neiko-01902-Adjustable-Magnifying-Alligator/dp/B000P42O3C/ref=sr_1_2?dchild=1&keywords=helping+hand&qid=1628035660&sr=8-2">helping hand</a> I found on Amazon.

The only difficult part I felt from soldering the SMD components were keeping track of them since they are so small. However, to not loss any components I just focused on one column of components at a single time, along with keeping those components in their own pile. I could not grab the components, so I just used my tweezers to grab SMD components. In regards to the soldering process, I discovered the best way to solder all these components is to add some solder each column where the components will be soldered to. When I did that, then only I needed to do was solder one side of the component to board, so it stayed in place. Lastly, I just added solder to the other side of the component to complete the connections.

If you'd like to see a demonstration check out my Youtube video by clicking on the image:

[![SMD Light Show](https://img.youtube.com/vi/F8OCW8js3JA/0.jpg)](https://www.youtube.com/watch?v=F8OCW8js3JA)


## 10/03/2021 - DIY Radio Soldering Kit

![DIYRadio](https://user-images.githubusercontent.com/87344382/185779541-29d64261-c2de-4315-aaa5-ff34d63aac83.png)

<h3>Tools</h3>
<ul>
  <li>Soldering Iron</li>
  <li>Solder</li>
  <li>Ability to Read Schematics</li>
</ul>  

<h3>Motivation for the Project</h3>
Hi there, today my <a href="https://www.amazon.com/MiOYOOW-Soldering-Adjustable-87-108MHz-Education/dp/B08RXQDNL6/ref=sr_1_5?dchild=1&keywords=diy+radio+kit&qid=1628030975&sr=8-5">DIY Radio kit</a> came from Amazon, so I decided to build it as soon as I got home. It took me roughly four hours due to the assembly of the outer case since it came with no instructions, so thankfully my intuition helped me put it together. 

The most difficult soldering part was soldering the volume adjuster and power supply input since the volume adjuster required making a bridge from the radio PCB to the metal tip of the volume adjuster. The power supply challenged me in soldering its long tips since I needed to get enough solder for a connection, while being cautious to not add more solder than necessary. However in the end, a got functioning FM radio that is a joy to share with family and friends, particularly my grandma who still an avid listener of the radio, and although the speaker is not the largest it gets the job done.

To see a test of the radio click on the image to see my YouTube video:

[![My Own Radio](https://img.youtube.com/vi/1k571OwCdPE/0.jpg)](https://www.youtube.com/watch?v=1k571OwCdPE)


## 09/11/2021 - OshPark PCB Continuity-Tester 

![myPCB](https://user-images.githubusercontent.com/87344382/185779495-15af6553-c1b7-4aca-adc6-f5efc9e69d8b.png)

<h3>Tools</h3>
<ul>
  <li>Soldering Iron</li>
  <li>Solder</li>
</ul>  

<h3>Motivation for the Project</h3>

As a final project for my Circuits 1 course, I tested and designed my own continuity tester using LTspice and Eagle then having it manufactured by OshPark. It took three hours to get comfortable with LTspice and Eagle, but then after than it was simple to create my model for the continuity tester printed circuit board (PCB). Once I received the PCB boards I started soldering the components, but one mishap was not ordering a soldering socket for the IC1 on the circuit board since I could then remove the IC from the board with the need for desoldering. After soldering all the components, I verified my continuity tester worked by inserting the red and black soldered in wires on the PCB to my Arduino’s 5V and GND ports, which caused the continuity tester’s red LED lit up as was intended. Although, my PCB functioned I learned I needed to improve my soldering skills since I was quite messy with this board and I did not properly clean the board after I was done to make it presentable, so I hope to improve my soldering skills this summer.


## 09/11/2021 - Ohmmeter with a Potentiometer

![OhmPotent1](https://user-images.githubusercontent.com/87344382/185779451-4eeffa37-2010-44ad-b34e-0cc687809a50.png)

<h3>Tools</h3>
<ul>
  <li>Breadboard</li>
  <li>Arduino</li>
  <li>Male to Male Wires</li>
  <li>LED</li>
  <li>LM358 op-amp</li>
  <li>1 820 <span>&#8486;</span> resistor</li>
  <li>Resistor you wish to Measure</li>
  <li>Potentiometer</li>
</ul>  

<h3>Motivation for the Project</h3>

Similar to before I made another ohmmeter to measure the resistance of a resistor, but this time with a potentiometer, which served as tuner for the voltage. I tuned the voltage to provide me with the most accurate reading of the resistor’s resistance in Ohms since I since still relied on finding the resistance with Ohm’s law R = V / I. However, the Arduino code was modified to account for the potentiometer. Additionally, to verify the resistance was accurate I both identified the resistance of the resistor by observing its color bands and also using a digital multi-meter to ensure my ohmmeter on the breadboard is accurate. Hence, building this ohmmeter largely assisted me in getting comfortable with Arduino programming.


## 09/11/2021 - Ohmmeter with a Button

![OhmButtonGal](https://user-images.githubusercontent.com/87344382/185779415-656a6c1b-4724-480b-97d4-58594b4ba95c.png)

<h3>Tools</h3>
<ul>
  <li>Breadboard</li>
  <li>Arduino</li>
  <li>Button</li>
  <li>2 LEDs </li>
  <li>Male to Male Jumper Wires </li>
  <li>1 10 k<span>&#8486;</span> resistor </li>
  <li>1 1.2 k<span>&#8486;</span> resistor </li>
</ul>


<h3>Motivation for the Project</h3>

I created an ohmmeter that measures the resistance of a resistor by pressing a button since the button initiates the program to start reading the resistor by supplying current to flow through the resistor I will measure. Using a voltage divider equation I can just attain the voltage of resistor, that is then used to calculate the resistance by using Ohm’s law R = V/I, in which R is the resistance, V is the voltage of the resistor, and I is the current flowing through the resistor. I wrote the code for this program completely in Arduino and utilized only the analog pins to then convert them to digital values as part of the solution for the resistance.


## 09/11/2021 - Breadboard Continuity-Tester

![CTgallery](https://user-images.githubusercontent.com/87344382/185779350-185145b6-5769-498a-9d1b-93b3b8d7083a.png)

<h3>Tools</h3>
<ul>
  <li>Breadboard</li>
  <li>Arduino</li>
  <li>Male to Male Wires</li>
  <li>LED</li>
  <li>LM358 op-amp</li>
  <li>1 470 <span>&#8486;</span> resistor</li>
  <li>1 10 k<span>&#8486;</span> resistor</li>
  <li>1 2 k<span>&#8486;</span> resistor</li>
  
</ul>  

<h3>Motivation for the Project</h3>

In a Circuits 1 assignment, I got the opportunity to create a continuity tester, which would serve as the model for the continuity tester we design on Eagle and test using LTspice. I faced immense difficulty building this continuity tester due to it being my first time reading a data sheet for a component, but learning how to read a data served me well in my future projects and assignments since now I know where to make the appropriate connections with wires to get my desired output. 

Here specifically what required reading of a data sheet was the Texas Instruments LM358 op-amp since I had to identify the inverting and non inverting input for the continuity tester to work properly. The circuit I built here was also my first time working with an Arduino since prior I have only worked with Raspberry Pi, but it was simple to get adjusted since the programming involved is highly similar to C++.
