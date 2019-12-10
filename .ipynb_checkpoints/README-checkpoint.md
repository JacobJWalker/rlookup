# rlookup

This project is to have R code, that will ultimately be in a CRAN package, that can take data that does does not have a unique identifier, and find a unique identifier for each record from a lookup source.  As an example, let's say you have a customer database, and you did a survey, but the survey software you used did not have their customer ID number, but included asking for their first name, last name, age, and city.  By using rlookup it will look at pairs of these non-unique identifiers in the survey data and see if any of them uniquely match with your customers in the database, and if they do, to then add the customer number to the surey data, so you can link the data with traditional data tools.

This is being developed in JupyterLab first, but will ultimately be made into a CRAN package.
