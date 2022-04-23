# REPORTS
# Introduction
One of the newest innovations for feeding pets is the automated pet feeder. It will assist pet owners in caring for their pets when they are away from home. Even if the owners are not at home, their pets can be fed. The automated pet feeder is designed to assist pet owners in caring for their animals. One of the pet feeders that will be operated by a wireless infrared remote control is an automated pet feeder. The automated pet feeder will be operated by a wireless infrared remote control and will automatically dispense predefined amounts of food at the times specified by the user. As pet owners, users should be aware that their dogs require proper dietary control as well.Life's obligations can sometimes prevent pet owners from properly caring for their animals. Whether the user is suddenly gone from home or simply wants one less duty to worry about, they can rest certain that their favourite pet will be cared for and fed on time, every time.Pet care should be enjoyable, not taxing, and the purpose of this project is to make pet care easier for owners by offering an automated pet feeder.
# Objective Of This Project
The project's goal is to assist pet owners in feeding their pets on time, even while they are not at home. Aside from that, it can also assist the owner in understanding their pet's diet. It is critical for the owner to understand the pet's nutrition in order to ensure that the pet is healthy. This technique makes it easier for pet owners to feed their pets. The system works in two ways: one, it feeds the pet and transmits the feeding information to the owner, and the other, it feeds the pet and sends the feeding information to the owner. After feeding the pet, the system will stop responding for a period of time to ensure that the pet does not overeat.
# Principle
One of the newer technologies for feeding pets is the automated pet feeder. It will assist pet owners in caring for their animals when they are away from their homes. Even if the owners are not there, their pets can be fed. The purpose of an automated pet feeder is to assist pet owners in caring for their animals. A wireless infrared remote control will be used to operate an automated pet feeding. With the use of a wireless infrared remote control, the machine-driven pet feeder will automatically dispense fixed amounts of food at the precise times set by the user. Users should be aware that, as pet owners, their dogs require proper dietary control as well.
# Components and Supplies
* Atmega 328
* Voltage Source
* Servo Motor
* LED Bulbs
* Resistors
* Switch
* Wires
## Atmega 328 Microcontroller
The ATMEGA328 is a well-known microcontroller since it is used in many Arduino board devices. With a maximum clock frequency of 20MHz, 32KB of programme FLASH, and 2KB of RAM, the ATMEGA328P-PN is the Arduino Uno and Nano's 8-bit RISC heart. The ATMEGA328P-PN is a 28-DIP package with various on-board peripherals, including UART, SPI, timers, ADC, comparators, and a watchdog, that allows designers to easily prototype their designs before committing to surface mount technology. The ATMEGA328 is a flexible and cost-effective microcontroller with a temperature range of -40°C to 105°C and a voltage range of 1.8V to 5.5V.
## Servo Motor
A servomotor (also known as a servo motor) is a basic electric motor that is controlled by servomechanism. When a motor is used as a controlled device and is connected to a servomechanism, it is referred to as a DC Servo Motor. A controlled motor that is powered by AC is referred to as an AC Servo Motor. A servomotor is a linear or rotary actuator that provides for exact control of position, acceleration, and velocity in linear or angular directions. It is made comprised of a motor and a position feedback sensor. It also necessitates a complex controller, which is frequently a separate module created exclusively for servomotors.
## Voltage Source
We can start with the electrical supply as an introduction. It's just a gadget that can supply electricity to a linked circuit. They can be either a current or voltage source. We may talk about the most typical voltage source in this section. In reality, a voltage source is a passive component that may generate a constant force for electron flow across the wire to which it is attached. Typically, it is a two-terminal gadget. Voltage sources are divided into two categories: independent voltage sources and dependent voltage sources. A 5v fixed supply is used in this project.
## LED
The light-emitting diode (LED) is a common light source in electrical devices. It may be used in a variety of ways, from your phone to enormous advertising billboards. They are most commonly seen in devices that display the time and various forms of data. When an electric current passes through a light-emitting diode (LED), it emits light. When current travels through an LED, electrons recombine with holes, resulting in light. LEDs enable electricity to flow in one direction but prevent it from flowing in the opposite way.
## Resistor
A resistor is a passive electrical component having two terminals that is used in electrical circuits to control or regulate the passage of electric current. The primary function of a resistor is to reduce current flow and lower voltage in a specific area of the circuit. It's comprised of copper wires that are wrapped around a ceramic rod and have an insulating paint coating on the outside. The Ohm is the SI unit for resistance.
## Switch
A switch is an electrical component that may interrupt or redirect electric current from one conductor to another by disconnecting or connecting the conducting channel in an electrical circuit. An electromechanical switch, which consists of one or more sets of moveable electrical contacts coupled to external circuits, is the most common form of switch. When two contacts are in contact, current can flow between them, but when they are separated, no current can flow.
# Goals
* A more customised pet-keeping experience.
* They no longer have to be concerned about their dogs when on work or vacation.
* You won't have to buy many feeders if you have multiple pets.
* There's no need to be concerned about your dogs devouring each other.
# Advantages
* Pet feeder controller mechanically feed your pet without you having to be present.
* Pet feeder controller  assist in weight control by providing your pet with the portioned feedings they require.
* It provide you piece of mind by ensuring that your pet is fed when you are away from home or at work.
* Instead of approaching you for food, your pet will learn to go to the feeder.
# Disadvantages
* When the dish spins, it might make a whirring sound that can be annoying, especially at night. This may cause your cats to get agitated.
* Despite the fact that it is electrical, it runs on batteries rather than direct current. It's tough to put batteries in and take them out.
* It does not include ice packs to keep the food fresh, it is not recommended to use moist food for more than 24 hours with this type of feeder.
# Scope
* The pet feeder will be configurable in terms of the amount and timing of food delivered, the system's ability to keep any sort of pet food, and the type of food that is distributed.
* The mechanism will be automated and include a timer. Clock timings, the user's set time, the personalised meal amount, and the system's on/off are among the inputs.  This logic architecture will be sequential as well as combinatorial.A timed clock circuit and counters will be used as inputs, causing the motors to operate.
# Limitations
* The pet feeder has a number of drawbacks, including a lack of sound variation, the need for manual food and water refills on a regular basis, and a restriction on the amount of food and water that can be dispensed.
* The digital system's limitations include the need for a clock circuit reset before it can count the amount of time it takes to deliver meals.
# SWOT Analysis
![image](https://user-images.githubusercontent.com/101519714/164944657-c44af219-dcb2-48de-8c3c-226c3fa2f59f.png)
# HIGH LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL01 | MOTOR INTERFACING WITH ATMEGA328 | IMPLEMENTED |
| HL02 | SERVO MOTOR INTERFACING | IMPLEMENTED |
# LOW LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL01-LL01 | ABLE TO DETECT THE ROTATION OF THE MOTOR | IMPLEMENTED |
| HL01-LL02 | MOTOR INTERFACING WITH ATMEGA328 | IMPLEMENTED |
| HL02-LL01 | ITS ROTATE RIGHT AS WELL AS ROTATE LEFT | IMPLEMENTED |
| HL02-LL02 | SERVO MOTOR ROTATES THE PANNEL POSITION	| IMPLEMENTED |
# 4 W&H's
![image](https://user-images.githubusercontent.com/101519714/164944686-a85239a2-183c-4b9f-9869-e287153d2f9a.png)
# Diagram
## Flow Chart
![image](https://user-images.githubusercontent.com/101519714/164944783-658890fa-5105-44d9-b90f-93819eac898f.png)
## Circuit Diagram
![image](https://user-images.githubusercontent.com/101519714/164944790-d2e6a316-3535-442d-9d72-142520c2400f.png)
## Block Diagram
![image](https://user-images.githubusercontent.com/101519714/164944795-1be1f2b3-1335-44e3-a468-007730afdb02.png)
## State Transmission Diagram
![image](https://user-images.githubusercontent.com/101519714/164944807-1a6e6ed1-a7fa-4a7e-b85e-d1124acfeb44.png)
## Data Flow Diagram
![image](https://user-images.githubusercontent.com/101519714/164944823-1b40e1e7-8d61-4f01-a56a-52d1f8b7d9dd.png)
# Output
## OFF Mode
![image](https://user-images.githubusercontent.com/101519714/164944855-b252d8e9-bea6-4764-8e2e-6cd944d6c789.png)
## ON Mode
![image](https://user-images.githubusercontent.com/101519714/164944867-a9bbd58e-4c45-48fe-90aa-2718782a53aa.png)
![image](https://user-images.githubusercontent.com/101519714/164944868-abee0a28-8083-48ce-bfb2-e1ce38da885a.png)

