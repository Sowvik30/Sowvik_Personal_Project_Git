💥 Embedded Systems Interview Prep

💻 Embedded C & Programming
----------------------------
1. volatile – what it does, use in hardware register access and ISR flags.

2. const – how it behaves with pointers and memory protection

3. Difference between hashtag#define, const, and enum for constants

4. struct vs union – padding, memory alignment, practical use-cases

5. When and why to use typedef struct?

6. Macros – Function like, Object like, Conditional, multi-line macros
Function pointers and Callback functions


7. Null pointer vs dangling pointer – examples and consequences

8. Pointer arithmetic – accessing arrays, peripheral registers

9. Operator precedence – especially in bitwise and logical expressions

10. Bit manipulation techniques – bit set, bit clear, bit toggle, bit read

11. Byte ordering (Endianness) – why it matters in embedded systems?

12. compilation stages from code to binary

🔩 Microcontroller & Architecture
1. What makes microcontrollers suitable for real-time control?

Ans: **Direct Hardware Access: Unlike general-purpose processors, microcontrollers can directly control peripherals (e.g., motors, sensors) without layers of abstraction, 
reducing delay
**Timers and Real-Time Clocks (RTCs): Built-in timers and RTCs help schedule tasks with precise timing and maintain accurate timekeeping—even during power-down modes
**Interrupt Handling: They support fast and prioritized interrupt mechanisms, allowing immediate response to external events like sensor triggers or button presses
**Deterministic Execution: Microcontrollers often run without an operating system or with a lightweight RTOS.

This means tasks execute in a predictable order with minimal latency—crucial for real-time systems


Interrupt vector table and how it's mapped
Linker script sections – .isr_vector, .data, .bss, .stack, .heap
Common causes of memory leaks even in embedded systems
Use of watchdog for system recovery and failure detection
GPIO direction setting, pull-up/pull-down resistor
Timers, PLL
Software vs hardware interrupts

🔁 Bootloader & Flash
Bootloader functions: hardware init, version check, flash jump
How to jump from bootloader to main app safely
CRC/checksum verification
Failsafe OTA: rollback strategy if update fails
Flash erase vs write – timing and voltage considerations

🧵 RTOS & Multitasking
Task states: ready, running, blocked, suspended
Preemptive vs cooperative scheduling
Stack usage per task – configuration and monitoring
Binary vs counting semaphores
How watchdogs behave in RTOS systems with many tasks
Heap management schemes

⚡ Interrupts & ISRs
What if an interrupt occurs inside another ISR?
What precautions to follow inside an ISR?
How is nested interrupt handled?

🛠️ Debugging & Tools
What is a logic analyzer and how is it used?
How does JTAG work in debugging?
What is a core dump?

📡 Communication Protocols
Compare SPI, UART, I2C, and CAN.
How does CAN arbitration and error handling work?
What’s new in CAN FD?

🧠 Memory & Variable Scope
Difference between RAM, ROM, Flash, EEPROM?
Stack vs heap — how and where are variables stored?
What are C storage classes and scopes?