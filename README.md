# cue-query
An experiment with adding a query language to cuelang.org in the spirit of json-query.

More details will be written soon on how the query itself maps to cue/json and how to form a lattice over entire queries so that value subsumption works over queries just like it does for structs and constraints.

Since `|` is already defined for disjunction in Cue, to achieve the pipe notation from json-query I propose using `->` arrow notation.
