# Advanced SQL Business Analysis

A structured collection of **400 progressively challenging T-SQL exercises** for practicing business analysis, data validation, transformation, reusable database logic, and advanced SQL Server techniques.

The exercises use a representative enterprise relational schema spanning human resources, people, sales, purchasing, and production. They progress from foundational filtering and aggregation to reusable functions, stored procedures, dynamic SQL, and control-flow patterns.

## Skills demonstrated

- Complex joins, subqueries, and Common Table Expressions (CTEs)
- Aggregation, conditional logic, and analytical reporting
- Window functions, ranking, partitioning, and segmentation
- Temporary tables, PIVOT, and data-type conversion
- Table-valued and scalar functions
- Stored procedures, variables, and dynamic SQL
- `CROSS APPLY`, `COALESCE`, and safe conversion patterns
- Conditional execution, loops, existence checks, and bit flags

## Learning path

| Module | Exercises | Focus | File |
| --- | ---: | --- | --- |
| 01 | 1–50 | Filtering, aggregation, subqueries, CTEs, temporary tables, and date functions | [`01-sql-foundations.sql`](./01-sql-foundations.sql) |
| 02 | 51–100 | Multi-CTEs, joins, date calculations, rounding, casting, and intermediate manipulation | [`02-data-manipulation.sql`](./02-data-manipulation.sql) |
| 03 | 101–150 | String transformation, conditional logic, segmentation, and randomized ordering | [`03-transformations-and-segmentation.sql`](./03-transformations-and-segmentation.sql) |
| 04 | 151–200 | `EXISTS`, `PIVOT`, ranking, partitioning, and analytical queries | [`04-ranking-and-analysis.sql`](./04-ranking-and-analysis.sql) |
| 05 | 201–250 | Reusable table-valued functions and parameterized retrieval | [`05-table-valued-functions.sql`](./05-table-valued-functions.sql) |
| 06 | 251–300 | Stored procedures, variables, execution patterns, and dynamic SQL | [`06-procedures-and-dynamic-sql.sql`](./06-procedures-and-dynamic-sql.sql) |
| 07 | 301–350 | Advanced functions, `TRY_CAST`, `COALESCE`, and `CROSS APPLY` | [`07-advanced-functions.sql`](./07-advanced-functions.sql) |
| 08 | 351–400 | Subqueries, `WHILE`, `IF`, `EXISTS`, and control-flow logic | [`08-control-flow.sql`](./08-control-flow.sql) |

## Repository structure

Each module contains:

1. The tables used by that module
2. A numbered business or analytical requirement
3. A corresponding T-SQL solution
4. Comments describing the principal concepts being practiced

The scripts intentionally increase in complexity so they can be used sequentially as a learning path or individually as an interview-preparation reference.

## Running the exercises

1. Use Microsoft SQL Server or a compatible T-SQL environment.
2. Connect to an enterprise sample database containing the referenced schemas and tables.
3. Review the table references at the beginning of each module.
4. Run exercises individually; several later modules create functions or stored procedures and should not be executed as one unrestricted batch.
5. Adapt schema and table names when using a different database.

> The dataset is not bundled with this repository. The scripts are designed as reusable SQL-learning examples and may require small schema adjustments for another environment.

## Professional relevance

The collection emphasizes SQL capabilities used in data engineering and analytics work: requirements translation, repeatable transformations, data reconciliation, analytical reporting, reusable logic, and production-minded validation.

## Author

**Parveen Kumar**  
[LinkedIn](https://www.linkedin.com/in/parveen-kumar22/) · [SQL & Data Engineering Portfolio](https://parveenmittal1.github.io/sql-data-engineering-portfolio/)

