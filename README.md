# Anansi Data Catalog Templates

Contains useful CSV templates for the Data Catalog.

## Azure Import

### When to use the templates in this folder?
These templates are to be used when you use the Azure Import Wizard in Anansi.  
These templates are used to set up the `AzureSystem` Table which will hold the output of the wizard.

### General Instructions
Please replace the Catalog Name in the CSV files with the catalog that you want to use.

## Relationships

### When to use the templates in this folder?
These templates are to be used after creating a new catalog in the Anansi tool and you want to start adding relationships to your entities.

### Introduction
There are 3 types of relationships possible in the tool:

1. Owner Relationships
    This kind of relationship is used to specify the ownership of an entity.  

2. Tag Relationships
    This kind of relationship is used to tag an entity.

3. Graphical Relationships
    We can visually "graph" relationships between systems using this kind of relationship.  

### General Instructions

1. If a user is adding more than one catalog, they can replace 'System' in the RelationshipMetaInfo.csv file with the entity (i.e., your Node Name) for which they want to add Owner and Tag Relationships.

2. If a user is adding more than one catalog, they can replace 'Metadata Catalog' with the new catalog name in all relevant CSV files.

Note: We can use the same Node Name in multiple catalogs.

### Templates Provided
1. NodeInfo.csv -> To be imported into the Node Information Table.
2. PropertyInfo.csv -> To be imported into the Property Information Table.
3. RelationshipMetaInfo.csv -> To be imported into the Relationship Meta Info Table.
