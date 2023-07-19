# Levitating-Saucer


<img src="./images/Saucer%20skeleton%20demo.gif" height="200"  />



This was a fun and challenging project done as part of the U of C ENEL400 design course. Awarded "favorite project" by my professor. It involved many interesting technical aspects of electrical engineering including:
- Analog circuit design
- PID control 
- PCB design
- Electromagnetics
    - Magnetic levitation
    - Wireless power transfer
- Power electronics
- Microcontroller programming


## The team:  
  
<img src="./images/the%20saucer%20team.jpg" width="400" height="300" />  

Left to right: Kazi, Sam, Alex, Levi (me), Murtaz, Henry  


## What's inside?:   
Not batteries! The levitating saucer is powered wirelessly. The transmitter coil resonates at 30kHz. The recieved power consumption (after rectification and regulation) is 500mW and the working range is over 2 inches.  

<img src="./images/saucer%20block%20diagram.png" height="200" /><img src="./images/saucer%20circuit%20parts.png" height="200" />


## Levitation PID control circuit:  
More specifically, a "PD" controll system that that uses a Proportional and Derivative control to keep the levitating saucer in one place and dampen oscillations.  
This circuit uses voltage adders/subtractors/multipliers to reactively compute the power to be sent to the electromagnet that suspends the levitating object.
  
<img src="./images/levitation%20control%20circuit.jpg" width="250"/>  

