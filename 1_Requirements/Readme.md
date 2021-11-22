# Requirements
## Introduction
## Title: Computation of Electrical Network & Transmission Parameters
This system computes the solutions for electrical system ranging from series RLC network followed by two port network and also to compute the efficiency of LV/Hv transmission systems by providing the required parameters.This parameter helps out the engineer to know about the working of the system to reduce losses and construct it in a much faster pace with high efficiency and reliability.
## Two Port Network 
Two port network is a pair of two terminal electrical network in which, current enters through one terminal and leaves through another terminal of each port. Two port network representation is shown in the following figure.

![Two Port N/W](https://github.com/GENESIS2021Q1/sdlc2-team-3/blob/main/1_Requirements/Two_Port_Network.jpg)

Here, one pair of terminals, 1 & 1’ represents one port, which is called as port1 and the other pair of terminals, 2 & 2’ represents another port, which is called as port2.
There are four variables V1, V2, I1 and I2 in a two port network as shown in the figure. Out of which, we can choose two variables as independent and another two variables as dependent.
The coefficients of independent variables are called as parameters. So, each pair of equations will give a set of four parameters
### Two Port Network Parameters
![Two Port N/W](https://github.com/GENESIS2021Q1/sdlc2-team-3/blob/main/1_Requirements/TPN_Parameters.gif)

## Series RLC Network
An RLC circuit is an electrical circuit consisting of a resistor (R), an inductor (L), and a capacitor (C), connected in series or in parallel. The name of the circuit is derived from the letters that are used to denote the constituent components of this circuit, where the sequence of the components may vary from RLC.

The circuit forms a harmonic oscillator for current, and resonates in a similar way as an LC circuit.

![Series RLC N/W](https://github.com/GENESIS2021Q1/sdlc2-team-3/blob/main/1_Requirements/RLC_Circuit.gif)

## Series RLC Netwrok Parameters

* __Resonance Frequency__

Electrical resonance occurs in an AC circuit when the effects of the two reactances, which are opposite and equal, cancel each other out as XL = XC. The point on the above graph at which this happens is were the two reactance curves cross each other. In a series resonant circuit, the resonant frequency, ƒr point can be calculated as follows.

![Series RLC N/W f0](https://github.com/GENESIS2021Q1/sdlc2-team-3/blob/main/1_Requirements/Resonant_Frequency.gif)

* __Quality factor__

The Q factor is a widespread measure used to characterise resonators. It is defined as the peak energy stored in the circuit divided by the average energy dissipated in it per radian at resonance.

Low-Q circuits are therefore damped and lossy and high-Q circuits are underdamped. Q is related to bandwidth; low-Q circuits are wide-band and high-Q circuits are narrow-band.

![Series RLC N/W Q factor](https://github.com/GENESIS2021Q1/sdlc2-team-3/blob/main/1_Requirements/Q_Equation.png)

* __Bandwidth__

A key parameter in filter design is bandwidth. The bandwidth is measured between the cutoff frequencies, most frequently defined as the frequencies at which the power passed through the circuit has fallen to half the value passed at resonance.

![Series RLC N/W BW](https://github.com/GENESIS2021Q1/sdlc2-team-3/blob/main/1_Requirements/Bandwidth.gif)

* __Damping Factor__

Damping is caused by the resistance in the circuit. It determines whether or not the circuit will resonate naturally (that is, without a driving source). 

Circuits that will resonate in this way are described as underdamped and those that will not are overdamped. Damping attenuation (symbol α) is measured in nepers per second. However, the unitless damping factor (symbol ζ, zeta) is often a more useful measure.

![Series RLC N/W DampingFactor](https://github.com/GENESIS2021Q1/sdlc2-team-3/blob/main/1_Requirements/Zeta_Equation.png)
## Transmission Line
Transmission line is the long conductor with special design (bundled) to carry bulk amount of generated power at very high voltage from one station to another as per variation of the voltage level.
## Types of Transmission Line
In transmission line determination of voltage drop, transmission efficiency, line loss etc. are important things to design. These values are affected by line parameter R, L and C of the transmission line. Length wise transmission lines are three types.
###  [Short Transmission Line](https://www.electrical4u.com/short-transmission-line/)
A short transmission line is classified as a transmission line with:
- A length less than 80km (50 miles)
- Voltage level less than 69 kV
- Only resistance and inductance are taken in calculation capacitance is neglected.
### [Medium Transmission Line](https://www.electrical4u.com/medium-transmission-line/#:~:text=A%20medium%20transmission%20line%20is,250%20km%20(150%20miles).)
A medium transmission line is classified as a transmission line with:
- A length more than 80 km (50 miles) but less than 250 km (150 miles)
- Operational voltage level is from 69 kV to approx 133 kV
- Capacitance effect is present
- Distributed capacitance form is used for calculation purpose.
### [Long Transmission Line](https://www.electrical4u.com/long-transmission-line/#:~:text=A%20long%20transmission%20line%20is,250%20km%20(150%20miles).&text=In%20a%20long%20transmission%20line,the%20entire%20length%20of%20line.)
A long transmission line is classified as a transmission line with:
- A length more than 250 km (150 miles)
- Voltage level is above 132 kV
- Line constants are considered as distributed over the length of the line.

  ### Explaination:
   For Transmission lines it takes more time for calculating the sending end voltage to finally get the efficiency manually.This project helps the customer to re-design their transmission system with higher efficiency by simply puting their design values in this project and taking out the efficiency.
## Cost and Features
| Solution | Time | Cost | Feature | Difference |
| --- | :---: | :---: | --- | --- |
| Manual calculations | Available since very long time | Time consumption | Can be done using only pen-paper | Our system is automatic, time efficient & accurate |
| Online calculator for two port network at www.calculatoratoz.com | Since 2011 (unsure) | free but shows advertises | Online access from anywhere | Only one value(like Z11) can be calculated at a time which makes task combersome. Our system provides every value at single place which is much more handy. |
| Various websites for computing series RLC network parameters | Since last decade | free but most of them shows advertises | Online access from anywhere | Feature to find frquency for which voltage across capacitor/inductor is maximum is not available in them |
| Simulation softwares | Since long time, many new/latest releases | free as well as paid versions | Lots of features with graphical interface | Our system is very specific and limited but more lightweight |

## Defining Our System
### Explanation:
* Our sytem allows user to select a topic (and subtopic if choise is available) & give required input. Automatic computaion is performed and end results are presented to user.


## SWOT ANALYSIS
![SWOT Analysis](https://github.com/GENESIS2021Q1/sdlc2-team-3/blob/main/1_Requirements/SWOT_Analysis.png)

# 4W&#39;s and 1&#39;H

## Who
*  Electrical & electronics engineering students, analyst, TRANSCO & DISCO can benifit from this project.

## What
*  Computing various parameters of two port network, Series RLC network, transformer & overhead line and analysis of LV & HV transmission system.

## When
* Neccessary to quickly calculate many parameters. Many Transmission Line are inefficient due to prolonged time for testing the efficiency of the transmission line manually.This project gives the oopurtunity to compute all the required parameters and deploy into real world with more efficiency

## Where
*  Transmission line consultancies, Academics, power system design.

## How
*  By offloading calculation from designers, their valuable time can be utilized in other processes; system provides the facility to user for computing the parameters of his/her requirement.

# Detail requirements
## High Level Requirements
| ID | Description | Category | Status |
| ----- | ----- | ------- | --------- |
| HR01 | Compute parameters of two port network | Technical | Implemented |
| HR02 |  Computation of Series RLC Network Parameters | Technical | Implemented |
| HR03 | Computation of analysis parameters for Transformer| Technical | Implemented |
| HR04 | Analysis of Entire Transmission System| Technical | Implemented |


##  Low level Requirements
| ID | Description | HLR ID | Status |
| ------ | --------- | ------ |------- |
| LR01 | User session for selecting which parameters are to be computed and taking input | HR01 |  Implemented |
| LR02 | Validation of input for data type & zeros in denominator for selected parameter computation | HR01 |  Implemented |
| LR03 | Take voltages & currents as input and compute all Z parameters | HR01 |  Implemented |
| LR04 | Take voltages & currents as input and compute all Y parameters | HR01 |  Implemented |
| LR05 | Take voltages & currents as input and compute all h parameters | HR01 |  Implemented |
| LR06 | Take voltages & currents as input and compute all g parameters | HR01 |  Implemented |
| LR07 | Take voltages & currents as input and compute all T parameters | HR01 |  Implemented |
| LR08 | Computation of Resonanace Frequency of the Network| HR02 | Implemented |
| LR09 | Computation of Quality Factor of the Network | HR02 | Implemented  |
| LR010 | Computation of Damping Factor of the Network | HR02 | Implemented  |
| LR011 | Computation of Bandwidth of the Network | HR02 | Implemented  |
| LR012 | Compute the Frquency for which Voltage across Capacitor is Maximum | HR02 | Implemented  |
| LR013 | Compute the Frquency for which Voltage across Inductor is Maximum | HR02 | Implemented  |
| LR014 | Compute A B C D paramters for single phase transformer by taking input of turns ratio, impedance, admittance | HR03 |  Implemented |
| LR015 | Compute A B C D paramters for three phase transformer grounded wye- grounded wye by taking input of turns ratio, impedance | HR03 |  Implemented |
| LR016 | Compute A B C D paramters for three phase transformer delta- grounded wye by taking input of turns ratio, impedance | HR03 |  Implemented |
| LR017 | Compute A B C D paramters for three phase transformer ungrounded wye- delta by taking input of turns ratio, impedance | HR03 |  Implemented |
| LR018 | Compute A B C D paramters for three phase transformer delta- delta by taking input of turns ratio, impedance | HR03 |  Implemented |
| LR019 | Computing parameters for Short Line using given receiving power, voltage, resistance, inductance, power factor | HR04 | Implemented |
| LR020 | Computing A B C D parameter matrix for Medium Line using given receiving power, voltage, resistance, inductance, power factor | HR04 | Implemented |
| LR021 | Computing A B C D parameter matrix for Long Line using given receiving power, voltage, resistance, inductance, power factor | HR04 | Implemented |
| LR022 | Calculaing and multiplying A B C D parameters for delta delta transformer and long line transmission for LV system | HR04 | Implemented |
| LR023 | Calculaing and multiplying A B C D parameters for ungrounded wye delta transformer and long line transmission for LV system | HR04 | Implemented |
| LR024 | Computing Voltage regulation and Efficiency for LV Transmission System | HR04 | Implemented |
| LR025 | Computing Voltage regulation and Efficiency for HV Transmission System | HR04 | Implemented |
