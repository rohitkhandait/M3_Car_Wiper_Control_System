# Abstract
A wiper is a vital component that removes raindrops or any other liquid from the windscreen of a vehicle. Previously, the wipers had to be manually activated by changing the frequency. The operation of increasing the wiper speed is modified as a result. The project's purpose is to improve the systems of older cars by providing automated transmission. wiping technology, to improve the system by including a sensor and actuator, and to develop a basic program that would work with the system completely. the structured  principle of this proposed wiper system is similar to that of other existing conventional wipers. Regardless of the fact that, t o drain water from the windscreen, this system will be updated to an automatic control system using a Peripheral Interface.
## Objective
- To reduce the risk of accidents.
- To automate the wiper mechanism.
- To reduce the driver’s tasks and allow driver to concentrate on driving.



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







# OVERVIEW OF STM32F407VGT6 MICROCONTROLLER :


![image](https://user-images.githubusercontent.com/74197288/168224735-419f707c-4042-419e-a927-35ec715f4b1e.png)


* The STM32F407 Discovery board uses STM32F407VGT6 Microcontroller which has ARM Cortex-M4F Processor, which is capable of running upto 168Mhz. This MCU has many peripherals such as GPIO ports, TIMERS, ADCs, DACs, Flash Memory, SRAM, SPI, UART ect. The processor and peripherals talk via BUS-Interface. There are three busses available

* I-BUS (Instruction Bus) D-BUS (Data Bus) S-BUS (System Bus) I-BUS This bus connects the Instruction bus of the Cortex®-M4 with FPU(Floating point unit) core to the BusMatrix. This bus is used by the core to fetch instructions. The target of this bus is a memory containing code (internal Flash memory/SRAM or external memories through the FSMC/FMC).

* D-BUS This bus connects the databus of the Cortex®-M4 with FPU to the 64-Kbyte CCM data RAM to the BusMatrix. This bus is used by the core for literal load and debug access. The target of this bus is a memory containing code or data (internal Flash memory or external memories through the FSMC/FMC).

* S-BUS This bus connects the system bus of the Cortex®-M4 with FPU core to a BusMatrix. This bus is used to access data located in a peripheral or in SRAM. Instructions may also be fetched on this bus (less efficient than ICode). The targets of this bus are the internal SRAM1, SRAM2 and SRAM3, the AHB1 peripherals including the APB peripherals, the AHB2 peripherals and the external memories through the FSMC/FMC.

* So instructions and data use I-bus and D-bus respectively, All the other peripheral uses System bus. The Cortex-M4 processor contains three external Advanced High-performance Bus (AHB)-Lite bus interface and one Advanced Peripheral Bus (APB) interface. The GPIOs are connected to AHB1 bus which has a maximum speed of 150Mhz and is divided into two buses as APB1 and APB2. APB1 runs at 42Mhz(max) and APB2 runs at 82Mhz(max). The different peripherals such as SPI, UART, TIMERs, ADCs, DACs, etc are connected to either APB1/APB2 buses. And the AHB2(168Mhz max) is connected to Camera and USB OTG interfaces, AHB3 is connected to External memory controller.






# WORKING PRINCIPLE :
Assuming that the automobile is the microcontroller(STM32F407VG). If the button is pressed , the first led (red) will turn on, Clicking again the wiper will starts , and the second led (blue) will turn on for a desired rate. If the button is pressed again , the third led (green) will turn on, and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth led (orange) , and the wiper speed will be increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click of the button.



# ENGINE_ON STATE : 





![ENGINE_ON STATE](https://user-images.githubusercontent.com/74197288/168262367-3097b9ae-ed68-4423-b25f-104a3c40cb95.png)


# WIPER RUNS AT LOW SPEED :






![WIPER RUNS AT 35%(LOW)](https://user-images.githubusercontent.com/74197288/168419630-910f2b77-7f47-46df-8ab5-a842c9462dbe.png)




# WIPER STARTS & RUNS AT MODERATE SPEED : 



 

![WIPER STARTS   RUNS AT 70%(MEDIUM)](https://user-images.githubusercontent.com/74197288/168262575-bb0dd897-fcec-4b27-988d-0688288a9550.png)



# WIPER RUNS FAST :





![orange led on](https://user-images.githubusercontent.com/74197288/168419506-19a8383c-93a3-4c39-a8aa-a27010adc84a.png)





# ENGINE_OFF STATE :






![ENGINE_OFF STATE](https://user-images.githubusercontent.com/74197288/168263299-aa56a1cd-a998-46f2-98f6-dcf8e25d2853.png)





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

The control system includes a rain sensor which detects the rain condition. An analog signal having an amplitude depending upon the detected rain conditions has been identified.A converter is used to convert analog signal into digital pulse signal and is transferred to a digital circuit system.The pulse signal is digitally processed where a control signal is produced.The control signal is applied to a wiper driver circuit to adjust the operational speed or timing in accordance with the control signal.

 
 


 


