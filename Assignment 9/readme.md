## ThreadExample

### Description:
This Java program demonstrates thread creation, setting thread priority, starting a thread, and waiting for a thread to complete its execution. It also showcases how to use various methods associated with threads.

### Instructions:
1. Compile the Java program:
   ```
   javac ThreadExample.java
   ```

2. Run the compiled program:
   ```
   java ThreadExample
   ```

### Code Overview:
- `ThreadExample` class:
  - Implements the `Runnable` interface to define a thread.
  - Inside the `run()` method, it prints "Thread is running...", pauses execution for 1 second, and then prints "Thread completed".
- `main()` method:
  - Creates a new thread using `Thread` class, passing an instance of `ThreadExample` as the target runnable.
  - Sets the thread's priority to the maximum value using `setPriority(Thread.MAX_PRIORITY)`.
  - Starts the thread with `start()`.
  - Waits for the thread to complete its execution using `join()`.
  - Prints information about the thread using various thread methods:
    - Thread name (`getName()`).
    - Thread priority (`getPriority()`).
    - Thread state (`getState()`).
    - Whether the thread is alive (`isAlive()`).

### Output:
The program will output information about the created thread, including its name, priority, state, and whether it's alive.
