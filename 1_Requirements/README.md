# Wiper Control Sysytem :

# INTRODUCTION :

A windscreen wiper, often known as a windshield wiper, is a device that cleans the windscreen of rain and debris. Almost every motor vehicle, including trains, planes, and boats, is fitted with wipers, which are frequently a mandatory feature. A wiper is typically made out of an arm with a long rubber blade attached to one end and pivoting to the other. The amount of features in today's autos is substantially higher. While driving, the driver must focus on the road, which becomes increasingly irritating as traffic increases. Features in the automobile such as GPRS to track the path, music system, and air conditioning system may divert the driver's attention.





# SOFTWARE USED : 

1) STM32CubeIDE
2) Qemu


# COMPONENTS : 

1) STM32F4O7VG MICROCONTROLLER BOARD


# DESCRIPTION

# STM32F407VG :



The STM32F407 Kit takes advantage of the high-performance STM32F407 microcontrollers' capabilities to make it simple for users to create audio-based applications.It comes with an ST-LINK embedded debug tool, an ST-MEMS digital accelerometer, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector.Ethernet connectivity, an LCD display, and other features have been added to the STM32F4 DISCOVERY kit. The STM32F405xx and STM32F407xx families are built around the high-performance Arm® Cortex®-M4 32-bit RISC core, which runs at up to 168 MHz.



# FEATURES OF STM32F407VG MICROCONTROLLER : 

* In a LQFP100 package, the STM32F407VGT6 microcontroller has a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM.

* On-board ST-LINK/V2 or ST-LINK/V2-A on STM32F4 DISCOVERY (old reference) or STM32F407G-DISC1 (new order code)

* USB ST-LINK with three separate interfaces and re-enumeration capability.

* Virtual Com port Debug port (with new order code only)

* Large-scale storage (with new order code only)

* Board power is supplied through USB or an external 5 V supply source.

* 3 V and 5 V external application power supply.



# USES OF STM32F407VG MICROCONTROLLER : 


* This Microcontroller is utilised in printing and scanning machines ,heat ventilation, air conditioning, and security systems.

* This module can be found in a variety of household products.


# FOLDER STRUCTURE :

  |Folder |Description|
  |:------------------|:----------------|
  | `1_Requirements`    |Documents detailing requirements and research|
  | `2_Architecture`     |Documents specifying design details|
  | `3_Implementation`   |All code and documentation|
  | `4_Testplan & Output`|Documents with test plans and procedures|
  | `5_Report`           |Overall report of the project|
  | `6_ImageAndOutput`   |Code execution output images|


# DETAIL REQUIREMENTS :

# HIGHLEVEL REQUIREMENTS 

|High Level Requirements|Description|
|:------|:---------|
|HLR1|Programming language(C language)|
|HLR2|Arm based microcontroller(STM32F40VGT6)|
|HLR3|operating system(Windows)|
|HLR4|RAM(Min 4GB)|
|HLR5|Hard Disk(Min 250GB)|

# LOWLEVEL REQUIREMENTS

|Low Level Reqiurements|Description|Status|
|:-----|:--------|:---|
|LLR1|ON-Ignition key|Implemented|
|LLR2|Press Multi-functional button|Implemented|
|LLR3|4 Different Color Leds|Implemented|
|LLR4|Timer|Implemented|
|LLR5|OFF-Wiper button|Implemented|



# WORKING PRINCIPLE :
Assuming that the automobile is the microcontroller(STM32F407VG). If the button is pressed , the first led (red) will turn on, Clicking again the wiper will starts , and the second led (blue) will turn on for a desired rate. If the button is pressed again , the third led (green) will turn on, and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth led (orange) , and the wiper speed will be increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click of the button.

 
 
 # 4W's & 1H
  
  
  # Who :
 
  * When it starts to rain, the front of the automobile normally employs a wiper system that uses two blades at once and a parallel tandem system to move the two blades. When the wiper motor starts to come on, the crank arm rotates, causing the connecting rods to pull and push against each other.
 
 # What :
 
 
 * Windshield wipers are a minor component of your vehicle, but they have a significant impact on your driving and overall safety. At the touch of a button, they    quickly and cleanly remove rain, snow, dirt, pollen, frost, and other material. Windshield wiper arms are moved across the windshield by the windshield wiper motor.

 # Where :
 
 
 * A wiper drive and two wiper arms make up a windshield wiper system. The drive pushes the two wiper arms across the windshield at an angle that allows the driver and passenger to see clearly. A carefully contoured rubber wiping lip gives the best possible wipe.
 
 
 # Why :
 
 
 * The wiper cleans the front and rear windshields of the car, albeit not all cars have wipers on the back side. WIper cleans the windshield by removing oil, dust, moisture, and grime that have become attached.



# How :

* The control system includes a rain sensor which detects the rain condition. An analog signal having an amplitude depending upon the detected rain conditions has been identified.A converter is used to convert analog signal into digital pulse signal and is transferred to a digital circuit system.The pulse signal is digitally processed where a control signal is produced.The control signal is applied to a wiper driver circuit to adjust the operational speed or timing in accordance with the control signal.



# SWOT ANALYSIS

# STRENGTH

 * Low Budget
 * Good Reputation
 
# WEAKNESS

* Structural Inertia
* High Transaction Cost

# OPPRONUTIES

* Emerging New Markets
* Demand for Saver Equipments

# THREATS

* Low Bargaining Power Buyers
* Econimical Crisis



 

