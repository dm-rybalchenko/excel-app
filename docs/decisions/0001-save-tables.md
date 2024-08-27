# save tables

* Status: proposed
* Date: 2022-12-31

## Context and Problem Statement

Need - quick save data from tables. Nobody knows how many columns can be in tables. Nobody knows how many tables should be saved.

## Considered Options

* MySQL
* PostgreSQL
* ClickHouse
* Reddis
* MongoDB
* CouchDB
* TreeDB

## Decision Outcome

Chosen option: "Redis", because easy to use and have some libraries with client and server components to start to use.
