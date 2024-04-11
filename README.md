# Embedded-System-Project

This college project involved creating an embedded application based on the freeRTOS operating system and the F401RE development kit. The project specifications included: acquiring analog input every X milliseconds in Task T1; controlling LEDs based on the read value in Task T2; transmitting acquired values through the serial interface in a specific format in Task T3; a manual control mode using a second potentiometer and the ability to switch between automatic and manual modes through a switch connected to an external interrupt pin. In manual mode, Tasks T1, T2, and T3 are suspended, and Task T4 is activated for LED control and serial transmission. Inter-task communication is achieved using queues. The project provided insights into embedded systems and real-time systems, including threads, tasks, queues, race conditions, mutexes, serial port, ADC, interrupts, and other associated concepts.

__________
HARDWARE:

- 1x NUCLEO F401-RE DEVELOPMENT BOARD
- 2x POTENTIOMETERS
- 3x LEDS(RED,BLUE,YELLOW)
- 15x JUMPER WIRES
- 1x USB-A TO USB-B MINI

[https://github.com/CBgdC/Embedded-System-Project/issues/1#issue-2237869753](https://github.com/CBgdC/Embedded-System-Project/issues/1#issue-2237869753)
