# Computer-Architecture-Abstracting-Electronics-
Understanding the idea behind computers. No electronics. 


# Understanding Computer Architecture

> Building an understanding of computers from first principles — while temporarily treating the underlying electronics as an abstraction.

## About

This repository documents my attempt to understand how computers actually work.

The goal is not simply to learn the definitions of RAM, CPUs, caches, registers, instructions, and other components. I want to understand **why these structures exist, what problems they solve, how they interact, and how increasingly complex computation emerges from relatively simple underlying mechanisms.**

Rather than treating a computer as a single black box, I want to progressively open that box.

## Current Abstraction Boundary

For now, I am **abstracting away the electronics**.

I will treat components such as transistors, logic gates, memory cells, and electronic circuits at the level necessary to reason about computer architecture, without yet attempting to derive their behaviour from the underlying physics.

Conceptually, my current boundary looks something like:

Physics  
↓  
Electromagnetism  
↓  
Quantum Mechanics  
↓  
Solid-State Physics  
↓  
Semiconductors  
↓  
Transistors  
↓  
Digital Logic  
↓  
**Computer Architecture ← Current focus**  
↓  
Machine Instructions  
↓  
Programs  
↓  
Algorithms  
↓  
Software

The layers below computer architecture are not being ignored — they are being **temporarily abstracted**.

As my understanding of electromagnetism, quantum mechanics, and semiconductor physics develops alongside my study of physics, I intend to return to this boundary and progressively open the abstraction from underneath.

Eventually, I want the statement

> "A computer executes instructions."

to connect all the way down to an understanding of the physical processes that make those instructions possible.
