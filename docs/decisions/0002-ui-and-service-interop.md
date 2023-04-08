# UI and service interop

* Status: proposed
* Deciders: me, MTF
* Date: 2023-04-08

## Context and Problem Statement

How to pass data between the UI and backend?

## Decision Drivers

* 1 source of truth
* static typing across the stack
* ease of change

## Considered Options

* REST
* GraphQL
* GRPC

## Decision Outcome

Chosen option: "none", because strong typing and single source of truth

## Pros and Cons of the Options

### REST

* Good, because in app
* Bad, because need to add checking (currently string typed)

### GraphQL

* Good, because less footprint?
* Good, because presence of generators
* Bad, because not in app

### GRPC

* Good, because presence of codegen
* Bad, because not in app
