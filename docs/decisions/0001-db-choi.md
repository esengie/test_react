# DB choi

* Status: proposed
* Date: 2023-04-08

## Context and Problem Statement

Need to choose EF vs direct sql management in the app

Want:
1) 1 source of truth
2) works with mssql
3) static typing

## Considered Options

* EF
* direct sql (stored procs)

## Decision Outcome

Chosen option: "EF", because Ease of maintenance
