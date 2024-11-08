Lamport Clock Simulation
This repository contains a Python implementation of the Lamport Clock algorithm, a logical clock system for distributed systems. Lamport clocks help maintain causal ordering of events across multiple processes in a distributed environment by assigning logical timestamps to each event.

Features
Lamport Clock Class: A LamportClock class representing individual processes, each with its own logical clock.
Event Simulation: Demonstrates internal, send, and receive events across processes.
Causal Ordering: Ensures the correct logical order of events when messages are passed between processes.
