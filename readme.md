# Snowflake Tutorial Assignment

**Student Name:** Sandeep  
**Tool Used:** SnowSQL CLI  
**Database:** DEMO_DB  
**Schema:** DEMO_SCHEMA  
**Warehouse:** DEMO_WH  

---

## Assignment Tasks Completed

### Task 1: SnowSQL Login and Connection Context
* Connected using SnowSQL CLI to account `zgiybbn-la16852`.
* Displayed connection metadata (`CURRENT_USER()`, `CURRENT_ROLE()`, etc.).

### Task 2: Creation of Snowflake Objects
* Created warehouse `DEMO_WH`, database `DEMO_DB`, schema `DEMO_SCHEMA`, internal stage `DEMO_STAGE`, and table `EMPLOYEES`.
* Performed standard DML queries (`INSERT`, `SELECT`, `UPDATE`, `DELETE`).

### Task 3: Data Loading via SnowSQL
* Prepared `data.csv` locally and staged it using `PUT`.
* Bulk loaded the staged file into `EMPLOYEES` using `COPY INTO`.

### Task 4: Snowflake Time Travel
* Modified records and queried historical baseline states using `AT(TIMESTAMP => ...)`.

### Task 5: Data Recovery via Time Travel
* Simulated accidental deletion of Sales records.
* Restored deleted rows using offset-based Time Travel (`AT(OFFSET => -120)`).