🚀 Using STM32Cube-MX (Stm32f446) we generate a program depend on >> FREERTOS.

⚡ But the most existing in our project is >> SEGGER TOOL.

Let's illustrate the program and what SEGGER TOOL do??

1️⃣ First we create 2 Tasks ( TASK_1, TASK_2 ) importing them by FREERTOS and they have the same priority, then we call the scheduler.

2️⃣ By SEGGER TOOL we can find out that:


1 - How many tasks are running and how much duration they consume.

2 - All context in the Program.

3 - ISR entry & exit and how much Timings.

4- How every task occupies CPU load.

5- Full timeline for the program.


👉 So it's clarifies what exactly happen in which order, Which interrupt has triggered, Which task is switched.
