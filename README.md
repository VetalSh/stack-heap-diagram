## Stack-Heap Diagram

The **Stack-Heap Diagram** illustrates the internal memory structure of a Java Virtual Machine (JVM), highlighting how variables and objects are allocated across two main memory areas: the **Stack** and the **Heap**.

### Key Points:

#### Stack Memory Segment:
- Local **primitive variables** (such as `int`, `boolean`, etc.) and **references** to objects are allocated here.
- The stack maintains the correct order of **method calls**, with variables being pushed and popped as methods are invoked and completed.
- The diagram displays this sequence, showing which variables and references are in memory at each stage of execution.

#### Heap Memory Segment:
- All **objects** (such as instances of classes) are stored in the heap memory.
- Objects are properly linked to **local references** in the stack, visualizing the relationship between the two memory segments.

By following the diagram, you can easily understand how memory is managed during the lifecycle of a Java program, from method execution to object instantiation.
