# NSU- Student Data Warehouse Analysis and Design




### North South University, Dept. of ECE

#### CSE411, Summer 2023, SEC-2

 

Assignment on Data Warehouse (DW)

 

Analyze and Design a data warehouse for NSU academic data analytics. There are many departments in different schools. There are many students with student id, name, present address (House no., street, thana, city, district), permanent address (House no., street, thana, city, district, division), age, gender, club membership. Each student has father with NID, name, profession, income and mother with NID, name, profession, income. A student registers a course in a semester, year. Each registered course has a fee and grade point. Each registered course is associated with a department and a teacher. A teacher has id, name, highest degree, country of the degree, age, gender.  A course has course-id, title, credit hour, type (major, core, trail etc. ).

You have to design and implement a warehouse for NSU academic data analytics as per above. Perform the following tasks for the warehouse.

 

Analysis and Design

Analyze the operational database and find the appropriate fact table and dimension tables. Design the star schema for the warehouse using the scenario.
Design the architecture of the warehouse and explain the sources, preprocessing, noise reduction, transformation and uploading.
Generate synthetic dataset for this star schema at least 10 departments of NSU for 10 years data.


## Analytics

### The following are the list of analytics:

  Student, department and father financial analytics,
  
  Student, department and mother financial analytics,
  
  Teacher, department student grade point analytics,
  
  Department, student and course grade point analytics,
  
  Teacher, student and course grade point analytics
