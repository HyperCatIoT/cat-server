Notes: Dynamic Catalogue Server
===============================

Design Choices: 
---------------
Database: 
1. Catalog entries are schema less.
2. Requires a NoSQL type DB. 
3. The entries are not time series data. 

MongoDB is most accurate choice of Database satisfying all the above requirements.
 
HyperCat:
1. hypercat provides nice (rel, val) json structure
2. Complex Search and catalog of catalog features are handy 
3. Data is stored in form of JSON style Documents, which suits MongoDB

With MongoDB and hypercat the catalog maintenance
and developing complex search is relatively easy. 
