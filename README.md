# Museum-database

The database for the subject area "Museum" should contain information about: 
1. branches: phone number, address and number of each branch;
2. events: event code, branch number, date, time and hall number;
3. exhibitions: exhibition code, exhibit code, name and age restrictions;
4. auctions: auction code, buyer code, lot code and its initial cost;
5. authors: the author's code, his full name, artistic style and phone number; 
6. collectors: the collector's code, his full name and phone number;
7. exhibits: the author's code, the code of the exhibit and the material from which it is made;
8. collections: collection code, collector code, type of collection and its name.

The first stage of database creation is the creation of the entity–relationship model. 
The basic concepts of such a model are Entity, Relationship and Attribute.
Entities in the database will be: "Branch", "Event", "Auction", "Exhibition", "Collector", "Author", "Exhibit", "Collection".
An attribute is a property of an entity or relationship. 
For example, the attributes of the "Exhibition" entity are: exhibition code, exhibit code, name and age restrictions.
A relationship is a relationship between entities. 
For example, "Exhibit" "Participates in" "Exhibition".

The result of the work is a designed database. The database contains eight tables with test data and SQL queries.
