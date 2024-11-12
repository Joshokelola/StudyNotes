## Types Of Database Models

- <u><b>Hierarchical Database Model:</b></u> this is when the data is organised into a **tree like structure**. The data are stored as records which are connected to each other through links in a one-to-one relationship. The data is connected in such a way that the records have **a single root**. Relationships among the records are determined at the runtime of the database transaction.

- **Network Database Model:** this is basically an improvement on the hierarchical database model. It organises data in a tree-like structure too but in a flexible way so as to accommodate many-to-many relationship.

- **Relational Database Model:** this is when data is organised with the help of tables. It exemplifies the separation of data into logical structures, data tables, views and indexes. Relationships between records are achieved using the foreign key.
	
	**Features of relational DB model**
	- Tables are arranged in form of records and the records are in turn arranged in form of attributes.
	- Records are differentiated by a so called **primary key**, the primary key ensures uniqueness of each of the records.
	- It has the concept of **foreign keys** which helps to initiate a logical connection between one relation and another.
	- **Secondary key** is an attribute of a relation that serves as indexes to a cluster of related records. It enables a cluster of records to be pulled out by just one command instead of continually retrieving records one after the other.
	- A relational DB looks like the normal file which has rows and columns
	- A row of a relational database is described as a tuple that represents a record.
	- A column of a relational DB describes the attributes of the record.
	- An attribute draws it values from a value set called a domain.
	- 2 or more attributes of a record may draw their values from the same domain
	- Each record or tuple must have unique identifiers called the primary key.

> [!NOTE]
> ***Use Claude***
> Get the technical and economical significance of the following concepts in relational db model:
> - Primary key
> - Foreign key
> - Secondary key.

Primary Key
- Technical Significance:
  - Uniquely identifies each record in a table
  - Ensures data integrity by preventing duplicate records
  - Can't contain NULL values
  - Creates an automatic index for faster record retrieval
  - Forms the basis for table relationships

- Economic Significance:
  - Reduces data redundancy, saving storage costs
  - Enables faster queries, reducing processing time and computing costs
  - Helps maintain data quality, reducing error correction costs
  - Facilitates data integration, saving development time

Foreign Key
- Technical Significance:
  - Creates relationships between tables
  - Enforces referential integrity
  - Prevents orphaned records
  - Enables join operations between tables
  - Can be NULL (unlike primary keys)

- Economic Significance:
  - Enables data normalization, reducing storage costs
  - Supports complex queries across related data
  - Prevents data inconsistencies, reducing maintenance costs
  - Allows for flexible database design and scalability

Secondary Key (Also called Candidate Key)
- Technical Significance:
  - Alternative unique identifier for records
  - Can be used as backup identification method
  - Often used for natural business identifiers
  - May contain NULL values (depending on configuration)

- Economic Significance:
  - Provides additional access paths to data
  - Supports business-specific queries
  - Enables alternative indexing strategies
  - Can improve query performance for specific use cases