# Banking Core Engine (Java)

## Overview

This project implements a domain-driven banking engine using pure Core Java. 
The objective is to model real-world banking entities and enforce business rules 
before integrating persistence frameworks such as JDBC, Hibernate, and Spring Boot.

## Key Concepts Covered

- Object-Oriented Design
- Encapsulation & Immutability
- Business Rule Enforcement
- Exception Handling
- Transaction Integrity
- Concurrency Control (Upcoming)

## Project Structure
src/com/bank/
 ├── model → Domain entities (Account, Customer, Transaction)
 ├── service → Business logic layer
 ├── exception → Custom domain exceptions
 ├── security → Basic security validation (PIN, lock handling)
 ├── util → Utility helpers
 └── app → Entry point for simulation

## Roadmap

Phase 1: Core domain modeling  
Phase 2: Transaction engine  
Phase 3: Concurrency safety  
Phase 4: JDBC persistence layer (separate repo)  
Phase 5: Hibernate ORM integration  
Phase 6: Spring Boot REST API  

---