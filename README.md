# Stop-watch-timer
it's a simple Mini Project Using Atmega32 to count time and overflow when reach to 100 Hours
using ATmega32 Microcontroller with frequency 1Mhz.

Timer1 in ATmega32 with CTC mode to count the Stop Watch time.

Six Common Anode 7-segments.

Six 7-segments in the project using the multiplexed technique.

one 7447 decoder for all 7-segments.
## Stop watch features
Reset button: External Interrupt INT0 with falling edge. Connect a push button with the internal pull-up resistor, If a falling edge detected the Stop Watch time should be reset.

Pause button: External Interrupt INT1 with raising edge. Connect a push button with the external pull-down resistor, If a raising edge detected the Stop Watch time should be paused.

Resume button: External Interrupt INT2 with falling edge. Connect a push button with the internal pull-up resistor, If a falling edge detected the Stop Watch time should be resumed.
