# University Database & Query Analytics

A comprehensive relational database schema and analytics project simulating a University Management System. Built using robust relational constraints and structured queries to handle student records, lecturer assignments, course tracks, and examination metrics.

##  Database Schema Design

The architecture models a real-world university system with 6 interconnected tables:
- `university` (Host institutes with rating attributes)
- `lecturer` (Faculty member profiles linked to universities)
- `students` (Student enrollment, birthdates, and financial stipends)
- `subject` (Course details, specific semesters, and durations)
- `subjectlectur` (A junction table resolving Many-to-Many faculty course assignments)
- `exammarks` (Dynamic table tracking individual student grades per subject)

##  SQL Techniques Demonstrated

- Data Integrity Constraints: Implemented `PRIMARY KEY`, `FOREIGN KEY (REFERENCES)`, `NOT NULL`, and conditional evaluations (`CHECK`).
-Data Analytics & Aggregations: Developed structured analytics reporting using `GROUP BY`, conditional metrics through `HAVING`, and built-in analytical averages (`AVG`, `COUNT`, `MIN`).
- String & Date Manipulations: Advanced application of relational string mechanics (`LIKE`, `CHARINDEX`, `UPPER`, `LOWER`, `CONCAT`) and advanced date/time logging computations (`DATEDIFF`, `DATEADD`).
- Relational Operations: Optimized table intersections using strict `INNER JOIN` conditions for high-efficiency structural reporting.
