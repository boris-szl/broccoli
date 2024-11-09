# broccoli-pg (WIP)
Broccoli tells you where to create indexes for your postgres db.

Indexes are a common way to enhance database performance. An index allows the database server to find and retrieve specific rows much faster than it could do without an index. But indexes also add overhead to the database system as a whole, so they should be used sensibly. 

Broccoli analyzes your pgdb, retrieves the data it needs, to provide a comprehensive evaluation and recommendation where to put indexes, called Broccolites. 
