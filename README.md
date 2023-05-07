# animal-factory
Comparative study of different implementation techniques, achieving the same functional result.

## Outline and intent

Evaluate different tactical options for implementing the same functionality.
Can be executed as a coding kata for practise. 
As a casus, the creation of different animals that each have their own specific quirks, will be used. More elaboration in the "kata assignment" description.
In order to keep the outward facing API identical, the implementation will feature an [Object Factory]() that hides the concrete implementation of the different classes.

The code is structured as follows:
- a top level containing the interface of the Factory to be implemented, and a test suite to assert each implementation is indeed functionally identical.
- a collection of different modules, each containing a possible implementation approach to solve the given assignment

## Kata description

### Part one

Creating an animal farm can be boring, so we will digitize the process.
Adding this automation, we need a way to construct animals that behave like their real-world equivalents do.  

We will be constructing animals. Or at least: code artifacts that resemble them closely enough.

We have a few animals that we want to model:
 - a cow
 - an eagle
 - a dolphin
 - a killer whale (orca)

 Each of these animals makes a particular sound, and has a way of moving in different environments. To keep things simple, we will focus on how they move:
 - in the sky
 - in the water
 - on the ground

Animals can move slow, average, or fast through each of these environments.
Each animal has a particular style of movement, which is also to be represented.
In case the animal in question is unable to move (unassisted) through the particular environment, it will simply refuse to do so. The expected return is "Nope!".

Your job is to implement the code that allows us to create these animals.

### Part two

> Add a new animal

### Part three

> Add a new method to be called -> (underground)

## Lessons learned
