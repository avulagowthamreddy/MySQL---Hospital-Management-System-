# MySQL---Hospital-Management-System-
Built a full Hospital Management System from scratch in MySQL — 15 normalized tables (patients, doctors, admissions, billing, insurance, staff, and more) and 30 analytical SQL queries to answer real operational questions.

A few of my favourites:

 → Top 3 highest-paid doctors per department using ROW_NUMBER() OVER (PARTITION BY ...)

 → Patients who have insurance and a pending bill, using nested EXISTS

 → A running hospital revenue total with a window function

 → An 8-table report joining patients → doctors → rooms → lab tests → prescriptions → bills → payments → insurance

Concepts covered: joins, correlated subqueries, CTEs, RANK/DENSE_RANK/ROW_NUMBER, LAG/LEAD, EXISTS/NOT EXISTS, ALL, and schema design with FK constraints.
