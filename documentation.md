## Project title: Interface 8-digit 7 segment LED display and 8 keys. Display 8-digit message

in 8 different ways as follows as per key pressed
Cases to implement when key is pressed:

    1. (Key 1) - Steady message
    2. (Key 2) - Blinking message
    3. (Key 3) - Rolling through left
    4. (Key 4) - Rolling through right
    5. (Key 5) - Odd number LED's blinking others steady
    6. (Key 6) - Even number LED's blinking others steady
    7. (Key 7) - Rolling half message from outside to inside
    8. (Key 8) - Rolling half message from inside to outside

**Aim:** To display a message in different ways using 8-digit 7 segment LED display and 8 keys depending on the key pressed.

**Hardware specifications**

 1. Microcontroller 8051 (AT89S51)

The AT89S51 is a low-power, high-performance CMOS 8-bit microcontroller with 4K bytes of flash programmable and erasable read only memory (PEROM). The device is manufactured using Atmel’s high-density nonvolatile memory technology and is compatible with the industry-standard MCS-51 instruction set and pinout. The on-chip Flash allows the program memory to be reprogrammed in-system or by a conventional nonvolatile memory programmer. By combining a versatile 8-bit CPU with Flash on a monolithic chip, the Atmel AT89S51 is a powerful microcontroller which provides a highly-flexible and cost-effective solution to many embedded control applications

 2. Resistor Pack

Resistors are used before the seven-segment display to limit the current flowing through the display's
segments and to protect both the display and the microcontroller or driver circuitry.

     1. Current Limitation
     2. Voltage Matching
     3. Protection for the Microcontroller
     4. Uniform Brightness

 3. 33pF Ceramic capacitors

These capacitors are typically used in parallel with the crystal oscillator leads to stabilize the oscillations and prevent unwanted noise or harmonics. They are often connected between the crystal pins and the ground to improve the stability of the clock signal.

 4. 12 MHz crystal

The 12 MHz crystal is an external clock source for the microcontroller. It's connected to the microcontroller's crystal oscillator pins to provide a stable timing reference for the CPU operations. The crystal frequency determines the speed at which the microcontroller operates. 10μF Electrolytic capacitor
This capacitor is often used for filtering and smoothing purposes. It might be connected in parallel with the power supply pins of the microcontroller to help stabilize the supply voltage and filter out high frequency noise.

 5. Push button

A push button can be used as a user input in a circuit. For example, you could connect the push button to a microcontroller's GPIO pin as an external interrupt source. When the button is pressed, it triggers an interrupt, allowing the microcontroller to respond to the event

 6. Common Anode 8-Digit 7-Segment Display

A Common Anode 8-Digit 7-Segment Display is a type of electronic component used to display numeric digits and some characters using seven-segment displays. Each digit is composed of seven LED segments arranged in a specific pattern, plus an additional eighth segment used as the common
anode connection.

 7. NPN Transistor

The transistor is used for current amplification as the microcontroller provides a limited current for the display so we have to amplify the current so we can have uniform brightness along with resistors.

 8. Connecting wires

To connect different components.

 9. IC base

It is used in order to allow safe removal and insertion of IC chips because microcontroller may be damaged from heat due to soldering/
