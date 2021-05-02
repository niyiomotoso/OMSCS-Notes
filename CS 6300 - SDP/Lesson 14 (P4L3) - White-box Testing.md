# Lesson 14

In _black-box_ testing we tested a system without knowing the internal details of the system. This lesson will examine _white-box_ (structural) testing which involves the internal details of a system as wells as benefits and drawbacks.

## White-box Testing Overview

In **white-box testing**, the basic assumption is that executing the faulty statement is a necessary condition for revealing a fault.

Some advantages of white-box testing include:

- Can be measured objectively
- Can be measured automatically
- Can be used to compare test suites
- Allows for covering the coded behavior

There are also different kind of white-box testing:

- Control-flow based
- Data-flow based
- Fault based

## Statement Coverage

**Statement coverage** refers to the number of statements in the program (e.g., _expect a + b to be > 0_) and the coverage should measure the number of executed statements versus the total number of statements.

Statement coverage in practice is typically 80-90% with but not 100%.

## Control Flow Graphs

**Control flow graphs** are ways to visualize the control flow of a particular block of code.

## Branch Coverage

Similar to statement coverage, **branch coverage** refers to the number of branches in the program (a group of tests based on the control flow for a particular block of program) and the coverage should measure the number of executed branches versus the total number of branches.

## Condition Coverage

**Condition coverage** refers to the individual conditions in the program and are measured based on the number of conditions that are both true and false versus the total number of conditions.