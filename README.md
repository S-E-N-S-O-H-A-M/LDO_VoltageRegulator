# LDO_Voltage_Regulator
This repository presents the design of a LDO Voltage Regulator with 2.55V-3.55V input voltage and a 1.50V reference voltage using the sky130 technology.
## Table of Contents ##

- [1. Introduction](#introduction)
- [2. Pre Layout Simulations](#pre-layout-simulations)
  * [ LDO Voltage Regulator](#LDO-Voltage-Regulator)
- [3. Observation](#observation)
- [4. Steps to install the tools and execute the pre layout design](#steps-to-install-the-tools-and-execute-the-pre-layout-design) 
- [5. Layout](#layout)
  * [LDO Voltage Regulator](#LDO Voltage Regulator)
- [6. Executing the postlayout design simulations](#executing-the-postlayout-design-simulations)
- [7. Further Work](#further-work)
- [8. Contributors](#contributors)
- [9. Acknowledgements](#acknowledgements)


# Introduction



# Pre Layout Simulations

The tools used for these simulations are:
* eSim
* ngspice

The schematics for a LDO Voltage Regulator circuit was designed in eSim. As the input voltage was 2.55V-3.55V and reference voltage was 1.50V.

## LDO Voltage Regulator
The eSim schematic is as shown below:

![LDO_VoltageRegulator](https://github.com/S-O-H-A-M/LDO_VoltageRegulator/blob/main/Schematics/screenshot/Schematic_Screenshot.PNG)

The Output Vs Input Voltage of this schematic is as shown below:

![OutputVsInputVoltage](https://github.com/S-O-H-A-M/LDO_VoltageRegulator/blob/main/Pre%20Layout%20Simulations/screenshots/OutputVsInputVoltage_avsdvr_3v05.PNG)

The Output Voltage at Input Voltage of 2.55V of this schematic is as shown below:

![Output_Voltage_2.55v](https://github.com/S-O-H-A-M/LDO_VoltageRegulator/blob/main/Pre%20Layout%20Simulations/screenshots/Output_Voltage_2.55v_avsdvr_3v05.PNG)

The Output Voltage at Input Voltage of 3.55V of this schematic is as shown below:

![Output_Voltage_3.55v](https://github.com/S-O-H-A-M/LDO_VoltageRegulator/blob/main/Pre%20Layout%20Simulations/screenshots/Output_Voltage_3.55v_avsdvr_3v05.PNG)

The Ouiescent Current of this schematic is as shown below:

![OuiescentCurrent](https://github.com/S-O-H-A-M/LDO_VoltageRegulator/blob/main/Pre%20Layout%20Simulations/screenshots/current_avsdvr_3v05.PNG)


The circuit with load of this schematic is as shown below:

![with_load](https://github.com/S-O-H-A-M/LDO_VoltageRegulator/blob/main/Pre%20Layout%20Simulations/screenshots/with_load_avsdvr_3v05.PNG)

The circuit without load of this schematic is as shown below:

![without_load](https://github.com/S-O-H-A-M/LDO_VoltageRegulator/blob/main/Pre%20Layout%20Simulations/screenshots/without_load_avsdvr_3v05.PNG)

The PSSR of this schematic is as shown below:

![PSSR](https://github.com/S-O-H-A-M/LDO_VoltageRegulator/blob/main/Pre%20Layout%20Simulations/screenshots/PSSR_avsdvr_3v05.PNG)


# Observation



# Steps to install the tools and execute the pre layout design
## Steps to install eSim
1. Install the eSim tool using this [website](https://esim.fossee.in/downloads). Note: You can also refer to the eSim [Spoken Tutorial](https://spoken-tutorial.org/tutorial-search/?search_foss=eSim).


## Executing the prelayout design simulations


## Executing the postlayout design simulations


# Further Work

Further work would be to obtain the simulatios of 9 bit DAC and 10 bit DAC and calculate INL and DNL for 10 bit DAC.

# Contributors

* Soham Sen , B.Tech (Electronics and Communication Engineering), Amity University Kolkata - sohamsen25420001@gmail.com

# Acknowledgements

 * Kunal Ghosh, Co-Founder of VLSI System Design (VSD) Corp. Pvt. Ltd. - kunalghosh@gmail.com
