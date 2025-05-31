# Database-Management-Systems

The project involved several key steps. I began by installing the RMySQL package and configuring access to an AWS-hosted MySQL database. I dropped the existing tables and created new tables: incidents, airports, and conditions. I added Constraints, including foreign keys that link incidents to airports and conditions and a constraint that limits flight phases to “takeoff,” “landing,” “inflight,” or “unknown.”

Next, I loaded data from CSV files. This included renaming a column, inserting values into conditions and airports, and retrieving airport data for accurate key mapping. I inserted Data into the incidents table, excluding military-related entries. I adjusted the column names for compatibility before final data insertion.

I performed Several SQL queries; these included counting incidents by airline and descent type (top 10), analyzing bird strikes by flight phase and calculating averages, and grouping incidents by month. I created visualizations using a line chart and scatter plot to display bird strike trends from 2005 to 2011.
I implemented a stored procedure for incident insertion, and data was retrieved for a specific record (rid = '200099'). Finally, the database connection was closed correctly.

Challenges included failed attempts to use db4free due to local data restrictions, which I resolved by switching to Amazon AWS.
