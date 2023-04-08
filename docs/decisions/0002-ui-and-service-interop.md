# UI and service interop

* Status: proposed
* Date: 2023-04-08

## Context and Problem Statement

How to pass data between the UI and backend?

Want:
1) 1 source of truth
2) static typing

## Considered Options

* Json like thing
* GraphQL
* GRPC

## Decision Outcome

Chosen option: "GraphQL", because strong typing and schema + not much overhead
