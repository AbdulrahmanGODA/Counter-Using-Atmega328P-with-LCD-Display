# Garage-Counter-Using-Atmega328P-with-LCD-Display
How to design and implement a garage counter usingAtmega328P. The project uses external interrupts at INT0 and INT1 connected to two IR  sensors for counting. The project can count up to 17 and down to zero. The project displays the numbers on an LCD in 4-bit mode.
# Notes
The IR sensor is normally High, so when an object is detected, it outputs LOW signal that trigger the INTERRUPT (Falling Edge Triggered). 