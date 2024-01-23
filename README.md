astrotemplate-db
---------------------------
A template for astronomical databases.

We encourage users to follow the detailed best practices for astronomical databases outlined in [Chen et al. 2022](https://iopscience.iop.org/article/10.3847/1538-4365/ac6268).

Installation instructions
---------------------------
The only dependency for running the template is [AstrodbKit2](https://github.com/astrodbtoolkit/AstrodbKit2). It can be installed with the following command:

`pip install git+https://github.com/dr-rodriguez/AstrodbKit2`

[todo: update?]


How does the database work?
---------------------------
[todo: add a bunch of clear description here]
At the user level, customizing this database involves working with the [schema](https://github.com/astrodbtoolkit/astrotemplate-db/blob/master/src/astrotemplate/schema.py). In database-speak, a "schema" describes how various "tables" (aggregates of related data) are related to one another.

Under the hood, this template leans heavily on [AstrodbKit2](https://github.com/astrodbtoolkit/AstrodbKit2), a codebase built on [SQLAlchemy](https://www.sqlalchemy.org/).


