# Card Conduit “Ride App” Exercise

This is a sample Laravel application that is meant to be used for a coding exercise.
There are two steps to this exercise:

1. Implement a small refactor
2. Implement a slightly larger refactor

Be prepared to discuss the decision-making that went into each step, and why you
chose to implement both in the same way or in two different ways (your choice).

## Completing this Exercise

Please clone this repository and implement step one (below). Generate a patch file
of your changes (using `git diff`) and save that patch as `step-1.patch`. Then implement
step two (below) and create a second patch file (`step-2.patch`). Send these two files
to us as your completed exercise.

## Notes on Code Style/Preferences

Each team has its own code style and preferences that inform how best to approach a given task. 

In general, at Card Conduit we stick to standard Laravel and RESTful conventions as much
as possible.  Simple, readable code is the ideal. We want to solve complex problems with plain, expressive solutions.

## The Tasks

### Step One

First, please update the code to support rides by taxi, at a rate of $18.25 per passenger.
Start with `RidesController` and make any adjustments as needed. Don’t worry about
functionality that does not already exist, but ensure that the new code works in the same
way as the existing code does.

### Step Two

Next, update the code to support rides by:

- Bus: $3.25/passenger
- Taxi: $18.25/passenger
- Ride Share: $19.00/passenger
- Limo: $30.00/passenger
- Shuttle: $10.00/passenger
- Boat: $50.00/passenger
- Helicopter: $500.00/passenger

Again, add as many files as you see fit, and change the `RideCalculator` API in any
way you like.
