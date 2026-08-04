Chapter 07 — Engineering Case Study: Inventory Management Project

Executive Summary

The Inventory Management Project stands out as the most ambitious and complete engineering effort in my portfolio.

What started out as a spreadsheet automation workflow grew into a full case study—one that puts Domain-Driven Design, QA, documentation habits, data transformation, and software architecture all to work.

But the real focus goes beyond just building with technology. At its core, this project pushes for a deep understanding of the business itself before any code gets written.

This is the work that best sums up my engineering approach.

Problem Statement

Businesses need accurate inventory data to make calls about purchasing, warehousing, production, and reporting.

In reality, inventory data comes in from all directions—different spreadsheets, different formats, inconsistent names, and gaps everywhere.

Without a solid process for checking and cleaning that info, you can’t really trust the systems built on top of it.

This project explores how clear thinking, Domain-Driven Design, and Quality Assurance help turn messy data into trustworthy information.

Why This Problem Matters

Honestly, cleaning up spreadsheet data isn’t the tricky part.

What actually gets tough is nailing down the business rules—what counts as “correct” inventory for this company? If you don’t get how inventory flows through their daily work, your technical solution can pass all the usual tests and still fail the business.

That’s why the project keeps the focus on listening and understanding first. Code is just a tool—the goal is to show that every engineering decision gets stronger when it’s built on solid domain knowledge, documentation, and attention to quality.

Project Snapshot

Item                       Value
Project Type               Inventory Management System
Status                     Active Development
Primary Domain             Inventory & Warehouse Management
Primary Focus              Domain-Driven Design, ETL, QA
Current Backend            Spreadsheet ETL
Planned Backend            SQLite
Planned Front End          Interactive web application
Primary Goal               Demonstrate engineering thinking through a complete software lifecycle

Project Evolution

This project started as a simple spreadsheet automation tool—to save time on repetitive data processing.

The first version grabbed spreadsheets from different departments, standardized the data, checked business rules, and spit out clear reports.

As the project grew, I saw a chance to turn it into a full software engineering piece—not just spreadsheet tricks, but a bigger demonstration of architecture, documentation, and QA.

Instead of just solving a single technical task, I rewrote it to frame a fictional business case to better highlight real engineering work and the thinking behind it.

Now, the project reflects my growth as an engineer—not just my progress with a specific technical problem.

Objectives

Engineering Objectives

- Use Domain-Driven Design
- Plan for Quality Assurance
- Design software that’s maintainable
- Keep track of decisions with documentation
- Build patterns that can be reused
- Develop a complete case study

Technical Objectives

- Design a maintainable ETL workflow
- Normalize inventory data
- Validate business rules
- Build a relational database
- Create an interactive application
- Use practical SQL

Professional Objectives

- Show good engineering judgment
- Demonstrate real problem solving, step by step
- Produce professional documentation
- Build something worth putting in a portfolio

Engineering Approach

The project follows my usual engineering workflow.

Understand

First, I dug into the inventory domain—it’s not about building right away. Questions I asked:
- What data actually matters?
- How does inventory move and change at each step?
- What business rules control inventory?
- What assumptions are there?
- Where does data quality break down?

Knowing the domain laid the groundwork for all later choices.

Design

Once I had a handle on the business side, I broadened the project’s scope. Key moves included:
- Creating a fictional company to work with
- Writing out business rules
- Building out a relational database
- Keeping ETL and presentation separate
- Laying plans for an interactive front end
- Recording decisions in Architecture Decision Records (ADRs)

Build

Development moves in small steps. Right now, the project does:
- Spreadsheet ETL
- Data normalization
- Validation
- Data transformation
- Reporting
- Documentation

The next phase will take this into a full, working application.

Verify

QA sits alongside everything else. I test for:
- Business rule accuracy
- ETL accuracy
- Bugs found by exploring the system
- Making sure changes don’t break old features
- Checking requirements
- Keeping documentation complete

Improve

The project is always evolving—every time I learn something new, it gets better. But improvements stick to documented needs, not just random feature stacking.

Architecture

I split out the architecture into layers so each section stands on its own and can change easily:
Vendor Files → ETL Pipeline → Validation → SQLite Database → Business Logic → Reporting → User Interface

This keeps things maintainable and flexible.

Key Design Decisions

Domain-Driven Design

Instead of jumping into coding, I made sure to understand the business first. Language, workflows, and requirements from the business shaped every technical decision.

Fictional Business

A made-up inventory company lets me create real-world scenarios without using any private or sensitive data. This way, I can show off good engineering habits in a safe example.

Documentation First

I write documentation as I build—requirements, architecture decisions, journals, engineering choices. Everything important gets recorded alongside the code.

Incremental Development

The project grows one stage at a time. Each phase works on its own and sets the stage for the next changes.

Challenges

Some of the trickiest problems:
- Creating realistic business requirements
- Keeping business know-how separate from code
- Designing data transformations that are easy to maintain
- Balancing simple design with future plans to grow
- Making sure all engineering context stays documented

Quality Assurance

QA is right at the center of things. Tests focus on:
- Business rules
- Getting ETL steps correct
- Data staying trustworthy
- Odd edge cases
- Making sure transformations do what they should
- Regression and exploratory testing

The idea is simple: the more you understand the business, the better you can design tests and catch issues.

AI Collaboration

AI has helped with:
- Analyzing the business
- Domain-Driven Design brainstorms
- Documentation
- Mapping out architecture
- QA strategies
- Engineering reviews
- Brainstorming sessions

But AI is just a tool—final decisions are always my call.

Outcomes

Here’s what the project has already nailed down:
- Defined business domain
- Step-by-step engineering workflow
- QA strategy
- Reusable documentation for the next steps
- Concrete architecture plans
- A roadmap for what’s next

Lessons Learned

This project really drove home some truths:
- Understand the business before touching code
- Good documentation shapes better architecture
- Test plans come from requirements
- Real engineering changes in cycles, not in one shot
- Aim for quality from day one
- Keep things simple and easy to maintain for the long haul

Engineering Decisions That Changed

Here’s where the project changed direction:
- Switched from Kadence to Divi
- Picked WordPress over a custom framework
- Decided the site should highlight engineering, not just marketing
- Created this Engineering Handbook
- Moved all documentation into GitHub

Step by step, the work shifted from simple spreadsheets, through a general ETL portfolio, into a deeper domain model, through Domain-Driven Design, and finally toward a relational database and interactive demo.

Future Roadmap

Coming soon:
- Build out the SQLite backend
- Launch the web interface
- CRUD inventory operations
- Dashboards for inventory
- Warehouse management features
- Advanced reporting tools
- API integration
- Automated tests
- Expanded QA docs
- More engineering case studies

Related Documentation

Related Handbook Chapters:
- Chapter 02 — Engineering Philosophy
- Chapter 03 — Engineering Standards
- Chapter 05 — Documentation & Knowledge Management

Related Repositories:
- Inventory Management Project
- Engineering Handbook
- QA Toolkit

Supporting Docs:
- Architecture Decision Records
- Project Journal
- README
- ETL documentation
- Database design notes
- QA test plans
- API documentation (planned)

Chapter Information

Version: 1.0.0
Status: Draft

Revision History

Version   Description
1.0.0     Initial chapter
