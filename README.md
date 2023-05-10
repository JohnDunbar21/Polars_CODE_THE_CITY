# Lecture Notes
## Speaker: Arturo Regalado
## Date: 10/05/2023

Pandas is one of the most popular libraries for data analysis in Python, though Polars is still in development and stands to be a strong competitor to Pandas.

Pandas Pros:
- Mature and stable;
- Standard for data teams;
- Intuitive API (sort of);
- Several learning resources;
- Recently released 2.0 (not stable)

Pandas Cons:
- Backend built on numpy;
- When initially developed it did not follow best SE practices;
- Slow

Pandas Rule of Thumb: *You will need between 5 and 10 times more RAM as the size of the dataset*.

Polars Pros:
- Fast;
- lightweight;
- Lazy or Eager Execution;
- Expressions and contexts;
- Expressive query language

Polars Cons:
- Very new (released 2021);
- Still under very active development;
- Fewer learning resources;
- Date/Time Functionality

*Use Polars if memory and speed constraints are an issue*.
