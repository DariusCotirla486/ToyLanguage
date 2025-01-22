This is a project I built in my second year of studies. It is a Java-based interpreter for a custom toy programming language, designed with concurrency in mind.

Key features:
  - Core language constructs such as variable declarations (int x; bool flag), arithmetic and logical expressions, control flow statements like if-else and while loops, nested expressions and compound statements
  - Heap management for dynamic allocation, including a Ref (reference) Type for managing memory dynamically. Supports heap reading, writing, allocating and deallocating.
  - Automated garbage collector that removes unused heap entries to optimise memory usage.
  - Multi-threading and parallel execution, made possible with fork statements and managed with the ExecutorService.
  - File operations to make possible in/out management of data. Files are themselves managed through a file table.
  - Step-by-step execution of the program in a graphical user interface, developed using JavaFX. It allows real-time visualisation and precise control over the execution flow.

Technologies used: Java, JavaFX
