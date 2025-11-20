# How a program execution is done ? Compiler Edition.

<h2>- Tasks of compiler:</h2>

1. Converts high level code to low level code.

2. Check for errors and syntax.

3. Does not run the program.

4. Does not schedule anything.

5. Compiler only translates.

<h2>- Tasks of OS:</h2>

1. Loads the program into memory (RAM).

2. Schedules when and how long it runs (CPU time slice).

3. Control resources such as - Memory, Files, IO devices and Network.

4. Switches between processes with context switching.

The OS never computes the program.
It only manages and schedules.

<h2>- Tasks of CPU:</h2>

This is where actual execution happens.

1. Executes machine code instructions

2. Performs arithmetic (+ - * /)

3. Performs logic (== < >)

4. Handles control flow (loops, conditions)

5. Reads/writes registers, cache, RAM

> Note: Read the below paragraph it was the gist of above things.

So compiler won't run the program it just convert the high level code to the low level code then when we run the executable the operating system schedules the process allot when and for how long the process will execute and when the process has been alloted the CPU the CPU finally executes and gives the output so this is how the program execution has been done.