# flight-calculator-kata
A tdd kata based on an interview test for a travel and tourism company.

## Description
A user should be able to enter a new flight which has a departure airport and a destination airport.

This new flight should be persisted into the system so that it can be retrieved later on.

Business logic should be able to calculate the distance between the two airports their GPS positions and to calculate the fuel needed for this flight, given the aircraft fuel consumption per distance/flight time + takeoff effort.

The program should be able to list the different flights which are loaded from a persistence medium, technology for this can be chosen freely.

It should also be possible to edit a flight and persist these changes.

A report page should be included that shows a summary of all entered data including the calculated data.

## Rules
1. Follow the TDD principles to design a simple calculator implementation.
2. User interaction is not implemented.
3. Persistence solution is linked to the program instance.