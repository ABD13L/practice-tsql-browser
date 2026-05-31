# T-SQL Online Sandbox

**Website:** [tsqlsandbox.online](https://tsqlsandbox.online)

T-SQL Online is a free, web-based Transact-SQL environment designed for students, educators, and developers who need to practice database queries directly in the browser without installing local SQL Server environments.

It serves as a fast, accessible alternative for practicing T-SQL syntax when you don't have access to a full IDE or a dedicated PC.

## Core Features
*   **No Installation Required:** Run T-SQL queries natively in your web browser.
*   **Table Management:** Support for `CREATE TABLE`, `ALTER`, `DROP`, and `TRUNCATE`.
*   **Constraints Support:** Implements `PRIMARY KEY`, `FOREIGN KEY`, `DEFAULT`, `CHECK`, and `UNIQUE`.
*   **Full CRUD & JOINs:** Execute `INSERT`, `SELECT`, `UPDATE`, `DELETE`, and all standard `JOIN` operations.
*   **Basic Logic:** Support for variables, `IF/ELSE`, `WHILE`, and `TRY/CATCH` blocks.
*   **Auto ER Diagrams:** Automatically generates an Entity-Relationship diagram based on your created schema.
*   **Export:** Export your SQL scripts directly from the session.

## Why this exists
This project was bootstrapped to solve a real educational problem. Database students often find themselves without the proper hardware to run heavy SQL Server instances, and existing online fiddles either lack proper T-SQL support or lock basic features behind paywalls. T-SQL Online was built from scratch to provide a frictionless sandbox for academic and quick-testing purposes.

## Technical Limitations (v1)
*   The platform currently simulates T-SQL behavior and does not run a native SQL Server instance behind the scenes.
*   Complex stored procedures and advanced database functions are not yet supported.
*   Free tier allows for 1-hour sessions and 1 database per session.

## Feedback and Support
This is a bootstrapped project actively maintained by the team at **Zone 0**. We are constantly looking to improve the engine. 

If you want to leave feedback, report a bug, or suggest a feature, please visit [tsqlsandbox.online](https://tsqlsandbox.online) and use the built-in feedback message icon.
