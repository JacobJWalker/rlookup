# rlookup

rlookup is an R function that performs a reverse lookup to find a unique identifier for data that has non-unique identifiers

The rlookup function can help when data is collected about known entities (for example customers), but the data collected does not contain a unique
identifier for the entity (for example customer survey data that does not contain the customer id).  If the data contains non-unique identifiers (for example first name, last name, age, and city), the rlookup function compares permutations of these non-unique identifiers with a lookup table (such as a customer database) to find unique matches between the two datasets. The rlookup function then adds the unique identifier (i.e. customer id) to the
entities in the data that does not have the unique identifier (i.e. survey data), so that traditional data tools can connect the two data sources.

This is being developed in JupyterLab first, but will ultimately be made into a CRAN package.
