# UI and service interop

* Status: proposed
* Deciders: me, MTF
* Date: 2023-04-08

## Context and Problem Statement

How to pass data between the UI and backend?

## Decision Drivers

* 1 source of truth
* static typing
* ease of changing
* works with mssql
* maybe allows to collapse multiple calls into one? (due to how the app is done)

## Considered Options

* REST
* GraphQL
* GRPC

## Decision Outcome

Chosen option: "GraphQL", because strong typing and single source of truth

### Positive Consequences

* collapse multiple into one

### Negative Consequences

* learning curve

## Pros and Cons of the Options

### REST

* Good, because addresses all the reqs
* Bad, because is not in app
* Bad, because need to ramp up

### GraphQL

* Good, because in app
* Bad, because changes to backend need to be made again in DB
* Bad, because string typing -- no checks in place for validity

### GRPC

* Good, because presence of codegen
* Bad, because not in app
