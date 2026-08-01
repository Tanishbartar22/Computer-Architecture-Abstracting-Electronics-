It is important to understand https://github.com/Tanishbartar22/Computer-Architecture-Abstracting-Electronics/blob/main/Thought%20Behind%20Computers%20and%20Architecture%20of%20Computers.md before reading the following section.

We ended https://github.com/Tanishbartar22/Computer-Architecture-Abstracting-Electronics/blob/main/Thought%20Behind%20Computers%20and%20Architecture%20of%20Computers.md by discussing an architecture called the _Shared Space Architecture_.

We will now talk about the CPU (Central Processing Unit). The CPU is the brain of the computer. It performs computations and updates data. With the _Shared Space Architecture_, the system needs to know how to interpret the received voltages and what to do with them. With the _Space For Everyone Architecture_, the interpretation depended on the location from which the data was received. In both architectures, the CPU is designed differently. Let us first discuss how the CPU works and is designed in the _Shared Space Architecture_.

The CPU works by executing computer instructions. These instructions are themselves stored in memory (the long tunnel of storage units) as combinations of voltages. The CPU is designed to receive, interpret, and execute these instructions. A key thing to realise is that we are now working with our third major idea of computation, which, like everything else, is ultimately represented as a collection of voltages.

Let us understand computer instructions by letting the computer execute a simple process.

Suppose we want the computer to carry out the following task:

> Add 2 and 3. If the output is greater than 0, make a certain value in memory **true**; otherwise, make it **false**.

We begin with the first instruction (**I₁**). The operating system sets the Program Counter (PC) to the location of **I₁**. Since **I₁** is stored as a binary instruction, the CPU fetches it, decodes it, and executes it.

Instruction **I₁** tells the CPU to load the value **2** into one of its registers (**R₁**). It then updates the Program Counter to **I₂**, which instructs the CPU to load the value **3** into another register (**R₂**).

Next, the Program Counter is updated to **Iₙ**, which tells the CPU to add the values stored in **R₁** and **R₂** and store the result in **R₃**.

The Program Counter is then updated to **Iₘ**, which tells the CPU to check whether the value in **R₃** is greater than **0**. If it is, the CPU sets the Program Counter to **Iᵣ**, which stores the value **true** at a particular location in RAM. Otherwise, it sets the Program Counter to **Iᵩ**, which stores the value **false** at that location.

Notice that instruction **Iₘ** determines the location of the next instruction based on a condition. In other words, it changes the Program Counter depending on the result of a comparison. These are known as **branching** or **control-flow instructions**.

The CPU continues repeating the **fetch–decode–execute** cycle until the program finishes.

## Different Parts of the CPU

The CPU consists of several major components that we need to understand. These include registers, the Control Unit, the Arithmetic Logic Unit (ALU), the Floating Point Unit (FPU), cache, and internal buses.

### Registers

Registers can be thought of as very small memory spaces (again made of storage units) inside the CPU. They hold temporary information while the CPU is executing instructions.

There are different types of registers:

1. **General-purpose registers** hold values that are being used during computations.
    
2. **Special-purpose registers** include:
    
    - The **Program Counter (PC)**, which stores the location of the next instruction.
        
    - The **Instruction Register (IR)**, which holds the current instruction being executed. It exists because the CPU needs a stable copy of the instruction while it is executing it.
        
    - The **Status Register**, which stores flags that influence future instructions.
        
    - The **Memory Address Register (MAR)**, which stores the memory address that the CPU wants to access.
        

There are many other types of registers, which we will discuss later.

### ALU (Arithmetic and Logic Unit)

The ALU is responsible for integer arithmetic and logical operations. It performs operations such as addition, subtraction, comparisons, and various logical operations.

### Cache

Cache is a clever idea that improves processing speed. Accessing data from RAM is relatively slow compared to accessing data from the cache, which is located much closer to the CPU. Since the cache is much smaller than RAM, it follows specific rules to decide which data to keep and which data to remove.

### Control Unit

The Control Unit is where the **fetch–decode–execute** cycle takes place. It coordinates communication between the different parts of the CPU and ensures that each instruction is carried out correctly.

More parts of the CPU will be discussed later, once we stop abstracting away the underlying electronics.
