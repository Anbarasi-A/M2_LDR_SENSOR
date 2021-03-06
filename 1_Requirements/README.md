
# INTRODUCTION
 * The LDRs are used in a bridge sensor circuit to convert light into voltage, allowing various actions to be performed, such as determining the darkness in the room and turning on or off the light by feeding the voltage signal into the microcontroller.

# PRINCIPLE
 * These devices are light-dependent; when light falls on the LDR, the resistance decreases, while in the dark, it increases. When an LDR is kept in the dark, it has a high resistance, and when it is maintained in the light, it has a lower resistance.When light is absorbed by the substance, the material's conductivity improves. When light shines on the LDR, the electrons in the material's valence band rush to the conduction band.

# COMPONENTS AND SUPPLIES
 * Atmega 328
 * 3 LEDs
 * voltage source
 * LDR
 * 4 Resistors
 * Buzzer
 * Switch

## LDR SENSOR DESIGN
  Atmega 328, 3 LEDs,voltage source,LDR,4 Resistors,Audio out
  
## Atmega 328 
 * Microchip's ATmega328 is an 8-bit, 28-pin AVR Microcontroller that uses RISC architecture and includes a 32KB flash-type programme memory.
The Atmega328 microcontroller is found in the Arduino UNO, Arduino Pro Mini, and Arduino Nano boards.
It has a 1 KB EEPROM memory and a 2 KB SRAM memory.

## LED
 * The term "light emitting diode" refers to a device that emits light. In comparison to incandescent light bulbs, LED lighting products produce light up to 90% more effectively. How do they function? A microchip receives an electrical signal, which ignites the tiny light sources known as LEDs, resulting in visible light.

## Voltage source
 * A voltage source is a power source that provides a constant voltage regardless of the amount of current required to keep that voltage constant. In theory, an endless current can be generated by a voltage source, although this is obviously not the case in practise.

## LDR 
 * When the LDR is in the dark, it can be used to turn on a light, and when it is in the light, it may be used to turn off a light. A typical light-dependent resistor has a resistance of 1MOhm in the dark and a resistance of a few KOhm in the light.

## Resistor
 * In an electronic circuit, a resistor is an electrical component that controls or regulates the passage of electrical current. Resistors can also be used to supply a specific voltage to an active device like a transistor.

## Buzzer
 * Buzzers are electronic components that can make a sound. I'd call it a sound rather than a noise, but I don't want to offend buzzers, so let's call it that.

## Switch
 * Switches come in a variety of shapes and sizes, with numerous sets of contacts operated by the same knob or actuator with the contacts operating simultaneously, sequentially, or alternately.
 
# HIGH LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL01 | LDR INTERFACING WITH ATMEGA328 | IMPLEMENTED |
| HL02 | BUZZER INTERFACING | IMPLEMENTED |

# LOW LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL01-LL01 | ABLE TO DETECT THE INTENSITY OF LEDs WITH LDR | IMPLEMENTED |
| HL01-LL02 | LDR INTERFACING WITH ATMEGA328 | IMPLEMENTED |
| HL02-LL02 | BUZZER INDICATES THE INTENSITY OF LEDs	| IMPLEMENTED

# 4W and H

## WHO
* LDR Sensor is using in most of the organization.

## WHAT
* These devices are light-dependent; when light shines on the LDR, the resistance drops, whereas in the dark, it increases. When an LDR is kept in the dark, it has a high resistance, and when it is maintained in the light, it has a lower resistance.

## WHERE
* These devices are employed in situations where it is important to detect the presence and absence of light. These resistors are employed as light sensors in alarm clocks, street lights, light intensity metres, and burglar alarm circuits, among other things.

## WHEN
* Light dependent resistors (LDR) are light-sensitive devices that are commonly used to detect the presence or absence of light, as well as to measure the intensity of light.

## HOW
* Their resistance lowers as the light intensity increases: an LDR's resistance is high in the dark and at low light levels, and only a small amount of current may flow through it.










