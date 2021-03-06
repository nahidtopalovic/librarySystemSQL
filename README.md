# Library Database System

This project is part of database system coursework taught at Queen Mary University of London, where the goal was to design and implement a relational database using OracleSQL.

Database was designed to conform following scenario: 
“A college library provides various resources for students and staff, including books, videos, DVDs, and CDs. Commonly, several copies are kept of some resources, for example, recommended books for courses. The usual loan period of a resource is two weeks, but some resources are available for short loan only (2 days), and some other resources can only be used within the library. The library consists of 3 floors. Resources are stored in the library on the shelves. A combination of floor number and shelf number is used to locate a specific item in the library. In addition to this, a class number system is used to identify in which subject area a particular item belongs; for example, all resources concerned with Database Systems will have the same class number. Students hold library cards that identify them as valid members of the library. Students can loan a number of different resources at one time, but the total number of resources they may borrow at a given time must never exceed 5. Staff members at the College also hold library cards and are allowed to loan up to 10 different items at one time. The library charges a fine for resources that are loaned for longer than the time allowed for that resource. For each day a resource is overdue; the member is fined one dollar. When the amount owed in fines by a member is more than 10 dollars, that member is suspended until all resources have been returned and all fines paid in full” (Tony Stockman, 2020).

## UML model of the database ##

![alt text](https://github.com/nahidtopalovic/librarySystemSQL/blob/master/UMLfinalModel.png)

**Database can be generated using the Database_creator_script.sql file**