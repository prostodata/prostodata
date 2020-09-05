***
## [Prosto Data Processing Toolkit: No join-groupby, No map-reduce](https://github.com/prostodata/prosto)

`Prosto` is a Python data processing toolkit to programmatically author and execute complex data processing workflows. Conceptually, it is an alternative to *set-oriented* approaches to data processing like map-reduce, relational algebra, SQL or data-frame-based tools like `pandas`.

`Prosto` radically changes the way data is processed by relying on a novel data processing paradigm: concept-oriented model of data. It treats columns (modelled via mathematical functions) as first-class elements of the data processing pipeline having the same rights as tables. If a traditional data processing graph consists of only set operations than the `Prosto` workflow consists of two types of operations:

* *Table operations* produce (populate) new tables from existing tables. A table is an implementation of a mathematical *set* which is a collection of tuples.

* *Column operations* produce (evaluate) new columns from existing columns. A column is an implementation of a mathematical *function* which maps tuples from one set to another set.
***
