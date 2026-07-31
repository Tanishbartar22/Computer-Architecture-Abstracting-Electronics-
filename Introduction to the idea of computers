# The Three Big Ideas

There were three ideas that came up together and hold huge importance in the idea behind computers. When we say that these ideas came up together, it does not mean that they originated at the same time; it means that all three were important for the development of computers.

1. The first idea was that information from various sciences and structures can be represented by a single system borrowed from a specific branch. Let me illustrate the first idea with an example: imagine all alphabets being represented by combinations of 5 0s and 1s. So `01010`, `11111`, `00000`, `01011` can mean A, B, C, D, etc. We just need a key or a rule to tell us which combination of 0 and 1 means which alphabet. Greek letters can be represented the same way. Numbers themselves can be represented the same way.

2. The second idea was to actually give physical meaning to 0 and 1. What if we have a collection of electronic storage units with either high voltage (1) or low voltage (0)? Then those electronic storage units can actually store data (see idea 1). We just need a system to change the voltages, access the voltages, and know what information is where and how many electronic storage units it is using. If we do this, we have a system that stores data.

3. The third idea is that of computation. We have information stored as states (0 or 1). Now, what if we design a system where we can actually perform operations? To give you an example, if we have numbers stored as binary numbers (as combinations of 0 and 1), then we can actually design addition such that the result it gives from the addition is a binary number that is actually axiomatically correct. It is also important in computation to store any result of any operation according to the representation scheme. Here, we design the hardware to work for us in our desired way.

Using these three big ideas, let's come up with different ways we can create computer machines.

One obvious architecture you can come up with is having a large number of electrical storage units placed together, where it may look like this at any instant:

`10011010010100101011101010101001010100.........`

Here we can use $n_1$ amount of storage units for numbers, the next $n_2$ storage units for, let's say, alphabets, the next $n_3$ storage units for Greek letters, the next $n_4$ storage units for maybe logical symbols, and so on. We must know where everything is, and for computation, we must design the system such that it knows where to look for anything in that long tunnel of electrical storage units.

Let's call this type of architecture *Space For Everyone Architecture*.

## Space For Everyone Architecture

Let's discuss this type of architecture in more detail.

We start by storing numbers in the electrical storage units. Now, 1 can be stored using one storage unit; however, `10029872772727` cannot be stored using one storage unit.

Now, a solution to this problem is to decide on a single, big enough number of storage units required to store any number. Let's say that number $N$ is `100000000`.

If we follow this rule, then every number can be represented by using `100000000` storage units. This solution wastes a lot of physical storage units to store information, and at maximum, you can only represent $2^N$ numbers.

The better solution is to have flexibility; that is done by dividing numbers into various chunks and saying that numbers below, let's say, a certain number must use a certain amount of storage units.

Now our system of computation knows and can be designed in such a way that it works according to those rules. For example, if we are computing $1 + 100$, then the system knows how 1 is stored and how 100 is stored, how to add them, and how (using how many storage units) to store the result.

Alphabets can be stored much more simply by just choosing a single method to represent alphabets. More such different types of data can be stored.

As you can see, you saw two different types of architecture even under *Space For Everyone Architecture*.

In this architecture, it is important for the system/computer to know where numbers are and how they are stored, and where the alphabets are and how they are stored.

The next architecture is a more clever architecture. Imagine having no separate collection of storage units for different types of data. Just a long collection of storage units.

Now the same collection of storage units can represent a number or even an alphabet. For computation, the system just needs to know how to interpret the received set of voltages.

Let's call this the *Shared Space Architecture*.

## Shared Space Architecture

A simple idea of letting the system handle the data: you have the same electrical storage units, but it depends on how the system is interpreting them.

Just like in the *Space For Everyone Architecture*, storing numbers will have two prominent solutions, out of which one wins.

You can see both major architectures now, and clearly, we don't know which one wins and what decides that a certain architecture may be superior.
