# java6

## Duck Behavior Simulation

## Overview

This Java application demonstrates the behavior of different types of ducks using the Strategy Design Pattern. The program defines interfaces for Fly_behaviour and Swim_behaviour and implements different behaviors for various duck types.

## Features

### Fly_behaviour Interface

Fly: Ducks that can fly.

NotFly: Ducks that cannot fly.

### Swim_behaviour Interface

Swim: Ducks that can swim.

Float: Ducks that float on water.

Drown: Ducks that drown in water.

### Duck Superclass

Ducks can perform flying and swimming based on their behaviors.

### Duck Types

MallardDuck: Can fly and swim.

RedheadDuck: Can fly and swim.

RubberDuck: Cannot fly but can float.

DecoyDuck: Cannot fly and drowns.

## How to Run

Clone the repository:

git clone https://github.com/yourusername/DuckBehaviorSimulation.git

Navigate to the project directory:

cd DuckBehaviorSimulation

Compile the Java files:

javac Main.java

Run the program:

java Main

## Expected Output

I'm a Mallard Duck
I can fly!
I can swim!

I'm a Redhead Duck
I can fly!
I can swim!

I'm a Rubber Duck
I cannot fly!
I am floating!

I'm a Decoy Duck
I cannot fly!
I am drowning!

## Design Pattern Used

This project follows the Strategy Design Pattern, which allows ducks to change their flying and swimming behaviors dynamically without modifying existing code.

## Contribution

Feel free to fork the repository, improve the code, and submit a pull request.

## License

This project is licensed under the MIT License.
