## Introduction
 A Door Sensor is connected to bit 1 of Port B,and an led is connected to
 bit 6 of port C.Write an AVR C program to monitor the door sensor and,
  when it opens, turns on the LED without changing the state of other pins

## Features

- Door sensor will sense if there anyone present or not.
- Modular Approach.

## Folder Structure
|Folder             | Description |
|-------------------| -----------------------------------------|
| `1_Requirements`   | Documents detailing requirements and research|
| `2_Design`         | Documents specifying design details|
| `3_Implementation` | All code and documentation|
| `4_TestplanAnd Output`      | Documents with test plans and procedures

## SWOT- Strengths, and Weakness, Opportunities Threats
### Strengths
- User Friendly
- Modular Approach
- Low cost and Robust system.

### Weakness
- It can ba only use for single home
### Opportunities
- It can be implemented other than house.
### Threats
- sometimes it may not be work.

# 4W's and 1'H
## Who:  
This Device can be used by anyone, It is easy to use .
## What:
The Temperature measurement using atmega328 is capable of maintaining the proper temperature inside the bus what this system will do it will sense the temperature inside the Bus using temperature sensor (LM 35) and it will give the signal to fan which will get switched ONN and Off accourding to requirement  .
## When:
It is made as a part of LTTS Step-in Mini Project work.
## Where:
It's made using Visual Studio Code IDE on Windows 10.
## How:
A simple algorithm is used which has a simple Temperature measurement code and can analyse the input and give the result.

## Detail requirements
### High Level Requirements
| High Level Requirements      | Description |
| ----------- | ----------- |
| HLR1      | Microcontroller   |
| HLR2   | door Sensor|
| HLR3  | Display|
| HLR4   | Software used|

### Low Level Requirements
| Low Level Requirements      | Description |
| ----------- | ----------- |
| HLR1_LLR1   | ATmega328     |
| HLR2_LLR1   |  ADC|
| HLR2_LLR2   | ADC with PWM-fast|
| HLR3_LLR1   |LED|
| HLR4_LLR1   | Code Blocks with AVR GCC compiler |
| HLR5_LLR2   | SimulIDE |
