# Chapter 07 — Engineering Case Study: Inventory Management Project

## Executive Summary

The Inventory Management Project is the largest and most comprehensive engineering project in my portfolio.

Originally developed as a spreadsheet automation workflow, the project has evolved into a complete engineering case study that demonstrates Domain-Driven Design, Quality Assurance, documentation practices, data transformation, and software architecture.

Rather than focusing solely on implementing technology, this project emphasizes understanding the business domain before designing technical solutions.

It serves as the primary demonstration of my engineering philosophy in practice.

# Problem Statement

Organizations depend on accurate inventory data to make purchasing, warehousing, production, and reporting decisions.

In practice, inventory information often originates from multiple spreadsheets, inconsistent formats, varying naming conventions, and incomplete data.

Without a reliable process for validating and standardizing that information, downstream systems become increasingly difficult to trust.

This project explores how thoughtful engineering, Domain-Driven Design, and Quality Assurance can transform inconsistent inventory data into reliable business information.

---

# Why This Problem Matters

The technical challenge of transforming spreadsheet data is relatively straightforward.

The more significant challenge is understanding the business rules that determine whether the transformed data is actually correct.

A technically successful ETL process can still produce poor business outcomes if it misunderstands inventory workflows, warehouse operations, or domain terminology.

This project therefore emphasizes business understanding before implementation.

Its primary objective is not simply to transform data, but to demonstrate how engineering decisions become stronger when they are informed by domain knowledge, documentation, and quality-focused design.

---

# Project Snapshot

| Item                  | Value                                                                  |
| --------------------- | ---------------------------------------------------------------------- |
| **Project Type**      | Inventory Management System                                            |
| **Status**            | Active Development                                                     |
| **Primary Domain**    | Inventory & Warehouse Management                                       |
| **Primary Focus**     | Domain-Driven Design, ETL, QA                                          |
| **Current Backend**   | Spreadsheet ETL                                                        |
| **Planned Backend**   | SQLite                                                                 |
| **Planned Front End** | Interactive web application                                            |
| **Primary Goal**      | Demonstrate engineering thinking through a complete software lifecycle |

---

# Project Evolution

This project began as a practical spreadsheet automation workflow created to solve repetitive data-processing tasks.

The original system accepted inventory spreadsheets from multiple sources, standardized the data, validated business rules, and generated organized reports.

As the project matured, I recognized an opportunity to transform it into a broader software engineering exercise.

Rather than simply demonstrating spreadsheet automation, I redesigned the project around a fictional inventory management domain to better showcase engineering practices, software architecture, documentation, and Quality Assurance.

The result is a project that now represents the evolution of my engineering thinking rather than merely the evolution of a technical solution.

---

# Objectives

## Engineering Objectives

* Apply Domain-Driven Design.
* Demonstrate Quality Assurance planning.
* Design maintainable software.
* Document architectural decisions.
* Build reusable engineering patterns.
* Develop a complete engineering case study.

## Technical Objectives

* Design a maintainable ETL workflow.
* Normalize inventory data.
* Validate business rules.
* Build a relational database.
* Create an interactive application.
* Demonstrate practical SQL usage.

## Professional Objectives

* Demonstrate engineering judgment.
* Show iterative problem solving.
* Produce professional documentation.
* Build a portfolio-quality software project.

---

# Engineering Approach

The project follows the engineering workflow defined earlier in this handbook.

## Understand

The first phase focused on understanding inventory management rather than immediately designing software.

Questions included:

* What information is important?
* How does inventory flow through the business?
* Which business rules govern inventory?
* What assumptions exist?
* What data quality issues occur?

Understanding the domain became the foundation for every later design decision.

---

## Design

Once the business domain was understood, the project architecture was expanded beyond the original spreadsheet automation.

Major design decisions included:

* introducing a fictional business domain,
* documenting business rules,
* designing a relational database,
* separating ETL from presentation,
* planning an interactive front end,
* documenting architecture through ADRs.

---

## Build

Development is intentionally incremental.

Current implementation includes:

* spreadsheet ETL,
* data normalization,
* validation,
* transformation,
* reporting,
* documentation.

Future implementation will extend these capabilities into a complete application.

---

## Verify

Quality Assurance planning accompanies every stage of development.

Verification includes:

* business rule validation,
* ETL validation,
* exploratory testing,
* regression testing,
* requirements verification,
* documentation review.

---

## Improve

The project is expected to continue evolving as new concepts are learned.

Future improvements will be guided by documented requirements rather than feature accumulation.

---

# Architecture

The planned architecture separates responsibilities into distinct layers.

Vendor Files
      │
      ▼
ETL Pipeline
      │
      ▼
Validation
      │
      ▼
SQLite Database
      │
      ▼
Business Logic
      │
      ▼
Reporting
      │
      ▼
User Interface

This separation improves maintainability while allowing each component to evolve independently.

---

# Key Design Decisions

## Domain-Driven Design

Rather than designing software first, the project began with understanding the business domain.

Business language, workflows, and requirements guide technical implementation.

---

## Fictional Business

A fictional inventory company provides realistic business requirements while avoiding proprietary information.

This allows the project to demonstrate professional engineering practices without exposing real business data.

---

## Documentation First

Documentation accompanies development throughout the project.

Requirements, ADRs, journals, and engineering decisions are recorded alongside implementation.

---

## Incremental Development

The project intentionally grows in stages.

Each phase produces a working system while establishing a stronger foundation for future capabilities.

---

# Challenges

Major engineering challenges include:

* Defining realistic business requirements.
* Separating domain knowledge from implementation.
* Designing maintainable data transformations.
* Balancing simplicity with future scalability.
* Preserving engineering context through documentation.

---

# Quality Assurance

Quality Assurance plays a central role in this project.

Testing focuses on:

* business rules,
* ETL correctness,
* data integrity,
* edge cases,
* transformation accuracy,
* regression,
* exploratory testing.

The project demonstrates that understanding the business domain improves testing quality.

---

# AI Collaboration

AI has contributed to:

* business analysis,
* Domain-Driven Design discussions,
* documentation,
* architectural planning,
* QA strategy,
* engineering reviews,
* brainstorming.

AI functions as a collaborative engineering assistant while final design decisions remain my responsibility.

---

# Outcomes

The project has already established:

* a documented business domain,
* an engineering workflow,
* a QA strategy,
* reusable documentation,
* architecture planning,
* and a scalable roadmap for future implementation.

---

# Lessons Learned

The project reinforced several important ideas:

* Business understanding precedes software design.
* Documentation improves architecture.
* Requirements shape testing.
* Engineering is iterative.
* Quality begins before implementation.
* Simplicity and maintainability support long-term growth.

---

# Engineering Decisions That Changed

This section records decisions that significantly redirected the project.

Examples:

* Switching from Kadence to Divi
* Choosing WordPress instead of a custom framework
* Centering the website on engineering thinking rather than marketing
* Creating the Engineering Handbook
* Moving documentation into GitHub

Original Spreadsheet

↓

Portfolio ETL

↓

Inventory Domain

↓

DDD

↓

SQLite

↓

Interactive Demo

---

# Future Roadmap

Planned enhancements include:

* SQLite implementation.
* Interactive web interface.
* CRUD operations.
* Inventory dashboards.
* Warehouse management.
* Advanced reporting.
* API integration.
* Automated testing.
* Expanded QA documentation.
* Additional engineering case studies.

---

# Related Documentation

## Related Handbook Chapters

* Chapter 02 — Engineering Philosophy
* Chapter 03 — Engineering Standards
* Chapter 05 — Documentation & Knowledge Management

## Related Repositories

* Inventory Management Project
* Engineering Handbook
* QA Toolkit

## Supporting Documentation

* Architecture Decision Records
* Project Journal
* README
* ETL Documentation
* Database Design Documents
* QA Test Plans
* Future API Documentation

---

## Chapter Information

**Version**

1.0.0

**Status**

Draft

---

## Revision History

| Version | Description |
|----------|-------------|
| 1.0.0 | Initial chapter |
