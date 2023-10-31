# Anansi Data Catalog Templates

Contains useful CSV templates for the Data Catalog.

## Relationships

### When to use the templates in this folder?
These templates are to be used when creating after creating a new catalog in the Anansi tool and you want to start adding relationships to your entities.

### Introduction
There are 3 types of relationships possible in the tool:

1. Owner Relationships
    This kind of relationship is used to specify the ownership of an entity.  

2. Tag Relationships
    This kind of relationship is used to tag an entity.

3. Graphical Relationships
    We can visually "graph" relationships between systems using this kind of relationship.  

### General Instructions
The Node Information table has a primary key setup on Node Name. Hence you cannot have repeated Node Names.

#### In case you have only 1 catalog setup in your tool

1. Replace "System" in RelationshipMetaInfo.csv file with the entity (i.e. you Node Name) for which you want to add Owner and Tag Relationships.

#### In case you have more than 1 catalog setup in your tool

1. Replace the following Node Names in the NodeInfo.csv and PropertyInfo.csv table with a new name of your choice. BUT, please make sure that they are suffixed by the word: "Relationships".  

2. Replace the words: "Metadata Catalog" with your new catalog name in all the provided CSV files.  

3. Replace "System" in RelationshipMetaInfo.csv file with the entity (i.e. you Node Name) for which you want to add Owner and Tag Relationships.

### Templates Provided
1. NodeInfo.csv -> To be imported into the Node Information Table.
2. PropertyInfo.csv -> To be imported into the Property Information Table.
3. RelationshipMetaInfo.csv -> To be imported into the Relationship Meta Info Table.
