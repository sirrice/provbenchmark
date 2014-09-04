# dimensions for data & error generation

Error rate (% of errors in the dataset)

Distinguishability

* well defined for discrete attributes
* in a numerical dataset, one example are the distances between the means of the normal and error values
    

Gradient

* are all errors either exactly normal or error value, or are error values "smeared" between the two extremes?

Dimensionality

# Metrics

The weights of each of these metrics depends on the application.

The result is either

* a (possibly ordered) set of predicates over the table
* a single disjunctive predicate over the table

Latency

* seconds to run algorithm
* seconds for user to find best predicate?

Precision

* For discrete error types: the percentage of records selected byt he predicate 
* For numerical attributes: ???

Recall

* For discrete error types: well defined

Predicate complexity

* an arbitrary function of the predicate (could be a linear function of string length, # attrs, # clauses, etc)

Overlap

* for each predicate in the set, or each conjunctive clause in a disjunctive predicate, the total amount of overlap of records between them

API complexity

* How many parameters are necessary for the user to set in order to run the system
    * e.g., c & lambda for scorpion

% of inputs needed (needs work)

* if there are N errors in the query results, how well does the algorithm do on the above metrics given X% of the N errors?
* We discussed cross validation, and discarded it.
