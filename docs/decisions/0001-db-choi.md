# DB choi

* Status: proposed
* Deciders: me, MTF
* Date: 2023-04-08

## Context and Problem Statement

Need to choose EF vs direct sql management in the app

## Decision Drivers

* 1 source of truth
* static typing
* ease of changing
* works with mssql

## Considered Options

* EF
* direct sql (stored procs)

## Decision Outcome

Chosen option: "EF", because Ease of maintenance

## Pros and Cons of the Options

### EF

* Good, because addresses all the reqs
* Bad, because is not in app
* Bad, because need to ramp up

### direct sql

* Good, because in app
* Bad, because changes to backend need to be made again in DB
* Bad, because string typing -- no checks in place for validity
