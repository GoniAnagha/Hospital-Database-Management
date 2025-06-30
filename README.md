# Mini-World Database Project 

## Phase-1

## Project Overview
This project involves designing a database for a chosen mini-world scenario—a specific environment with users interacting with the database. The goal is to define the data requirements and functional requirements for database operations that support this mini-world.

## Mini-World Requirements
- **Entities:** At least 5 entity types, including one with two key attributes and at least two weak entities.
- **Relationships:** Minimum 5 relationship types, including cardinality and participation constraints, one relationship of degree greater than 3, and at least one subclass.
- **Attributes:** Use composite, multi-valued, and derived attributes appropriately.
- **Bonus:** A relationship type where the same entity participates in distinct roles (e.g., supervisor and subordinate).

## Functional Requirements
- **Retrieval Operations:**
  - Selection queries (e.g., retrieve all students from a specific batch).
  - Projection queries (e.g., list courses with more than 50 students).
  - Aggregate functions like SUM, MAX, MIN, AVG (e.g., highest exam score).
  - Partial text search within entity data (e.g., searching "APP" matches "APPLE").
  - At least two analysis reports involving joins across entities (e.g., number of students scoring above average across courses).

- **Modification Operations:**
  - Data insertion with integrity constraint checks.
  - Update operations on existing data.
  - Delete operations.

## PDF content
- A PDF document summarizing:
  1. The mini-world description, purpose, and users.
  2. The database requirements.
  3. The functional requirements.

## Notes
- The requirements document defines what the database must store and the functionalities it must support.
- Specify all constraints such as attribute domains, cardinalities, and participation constraints.
- Understanding of concepts like joins and aggregates will be developed by the time of app development.
- Final ER models and programs will be based on these requirements and should not be changed drastically later.

## Phase-2

## Task Overview
Design an Entity-Relationship (ER) diagram for mini-world based on the previously submitted requirements document. The ER diagram should comprehensively represent all entities, their attributes, and the relationships between them as outlined in your requirements.

## Guidelines
- Use any digital tool (e.g., Creately, draw.io, Lucidchart) to create your ER diagram.
- Use (min-max) notation to specify cardinality and participation constraints clearly.
- Pay special attention to:
  - Cardinality constraints
  - Participation constraints
  - Correct representation of attributes (e.g., multivalued, primary keys)

## Phase-3

## Task Overview
Convert your previously designed ER diagram into a relational model and then iteratively normalize it through the following stages:
- Initial relational model (mapping from ER)
- First Normal Form (1NF)
- Second Normal Form (2NF)
- Third Normal Form (3NF)

## Phase-4

## Task Overview
Using your relational schemas from Phase 3, you will:
- Create and populate the database in MySQL.
- Develop a Python 3 command-line interface (CLI) that interacts with the database to fulfill the functional requirements.

## Project Details
1. **Database Creation and Population**  
   - Define all tables and relationships as per your relational schema using MySQL CLI or scripts.  
   - Insert relevant, legitimate data for testing and demonstration.

2. **CLI Application**  
   - Write a Python script to connect to the MySQL database using libraries such as PyMySQL.  
   - Implement at least 5 query commands and 3 update commands using raw SQL queries (no built-in ORM or abstraction functions).  
   - The CLI should handle all functional requirements specified earlier.

## Folder contains:  
  - Python script(s) implementing the CLI  
  - A README file listing all CLI commands with short descriptions, ordered as they appear in demo video  
  - The Phase 3 report renamed as `phase3.pdf`  
  - A video file named `<team_number>.mp4` (max 5 minutes) demonstrating:  
    - Two terminal windows open simultaneously  
    - One terminal running CLI commands  
    - Another terminal showing the database state before and after commands  
