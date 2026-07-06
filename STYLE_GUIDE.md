# STYLE_GUIDE.md

## Java Architect Interview Bible – Style Guide

### Purpose

This document defines the writing, formatting, and documentation standards for the Java Architect Interview Bible.

Every chapter in this repository should follow these guidelines to ensure consistency, readability, and long-term maintainability.

⸻

## Writing Principles

### Explain Concepts, Don't Memorize Definitions

Avoid writing short dictionary-style definitions.

Instead:

* Explain what the concept is.
* Explain why it exists.
* Explain how it works internally.
* Explain when it should be used.
* Explain when not to use it.
* Explain common production problems.
* Explain interview expectations.

⸻

### Write for Senior Engineers

Assume the reader has:

* 8–20 years of Java experience
* Enterprise application experience
* Knowledge of Spring Boot
* Microservices exposure

Do not oversimplify advanced topics.

⸻

### Focus on Production Systems

Every chapter should answer questions like:

* How is this used in production?
* What problems does it solve?
* What failures can occur?
* How do you troubleshoot it?
* What metrics should be monitored?
* What interview follow-up questions are likely?

⸻

## Chapter Structure

Every chapter must follow this order.

1. Learning Objectives
2. Introduction
3. Theory
4. Internal Working
5. Architecture
6. Flow Diagram
7. Memory Diagram (if applicable)
8. Real Production Example
9. Code Examples
10. Performance Considerations
11. Advantages
12. Disadvantages
13. Best Practices
14. Common Mistakes
15. Interview Questions
16. Scenario-Based Questions
17. Coding Exercises
18. Company-Specific Questions
19. Summary
20. Revision Notes
21. Cheat Sheet
22. References

⸻

## Code Standards

### Use:

* Java 17 or later unless an older version is required.
* Meaningful class names.
* Meaningful variable names.
* Proper formatting.
* Small examples before large examples.
* Explain every important code block.

### Avoid:

* Single-letter variable names (except loop counters).
* Unexplained "magic numbers."
* Overly complex examples without context.

⸻

## Diagrams

Prefer diagrams wherever they improve understanding.

### Examples:

* Architecture diagrams
* Sequence diagrams
* Flowcharts
* JVM memory diagrams
* Class diagrams
* Deployment diagrams
* Component diagrams

Use Mermaid syntax where appropriate so diagrams can be rendered directly in documentation tools.

⸻

## Tables

Use tables to compare concepts.

### Examples:

* HashMap vs ConcurrentHashMap
* Heap vs Stack
* REST vs gRPC
* Kafka vs RabbitMQ
* Docker vs Virtual Machines

⸻

## Interview Question Format

Every interview question should include:

1. Question
2. Expected answer
3. Why interviewers ask it
4. Common mistakes
5. Follow-up questions

### Example:

#### Question

Why is HashMap not thread-safe?

#### Expected Answer

Explain concurrent modification, race conditions, and why synchronization is required for shared mutable state.

#### Why This Is Asked

To evaluate understanding of concurrency and collections internals.

#### Common Mistake

Answering only "because multiple threads access it" without explaining the underlying issue.

⸻

## Production Scenario Format

Each scenario should include:

* Problem statement
* Symptoms
* Possible causes
* Investigation steps
* Root cause
* Resolution
* Prevention
* Lessons learned

⸻

## Coding Exercises

Every chapter should contain:

* Easy exercise
* Medium exercise
* Advanced exercise
* Expected solution
* Time complexity
* Space complexity
* Optimization discussion

⸻

## Company Interview Tips

When relevant, include notes on how different companies may approach the topic.

For example:

* Product companies often emphasize trade-offs and scalability.
* Financial institutions frequently focus on reliability, transactions, concurrency, and production support.
* Cloud-focused organizations may explore deployment, observability, and resilience.

Avoid assuming every company asks identical questions.

⸻

## Best Practices

### Prefer:

* Immutable objects
* Composition over inheritance
* Constructor injection
* Clear separation of concerns
* Clean code
* SOLID principles
* Defensive programming
* Observability
* Automated testing

⸻

## Revision Notes

End every chapter with:

* Five-minute revision
* Important interview points
* Common pitfalls
* Cheat sheet
* Suggested next chapter

⸻

## Language Guidelines

### Use:

* Clear technical English
* Consistent terminology
* Active voice where practical
* Complete explanations

### Avoid:

* Unexplained jargon
* Marketing language
* Ambiguous statements
* Unsupported performance claims

⸻

## Repository Standards

* One topic per chapter.
* Keep filenames descriptive and consistent.
* Update the table of contents when new chapters are added.
* Cross-reference related chapters where helpful.
* Review examples for correctness before committing.

⸻

## Long-Term Goal

Create a professional, comprehensive Java Architect reference that serves as:

* An interview preparation guide
* A technical learning resource
* A mentoring handbook
* A production troubleshooting reference
* A long-term knowledge base

⸻

---

**Last Updated:** July 6, 2026

For questions about this style guide, please refer to the [README.md](./README.md) or [SUMMARY.md](./SUMMARY.md).
