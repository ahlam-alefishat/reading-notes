# Read-09
## functional programming:

## What is functional programming?
- Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — `Wikipedia`

### Fundementals of functional programming:
1. *Pure functions*:
* It returns the same result if given the same arguments (it is also referred as deterministic).
* It does not cause any observable side effects.

2. *Immutability*:
* When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

3. *Referential transparency*:
* `pure functions + immutable data = referential transparency`

4. *Functions as first-class entities* :
* The idea of functions as first-class entities is that functions are also treated as values and used as data.
Functions as first-class entities can:
- refer to it from constants and variables
- pass it as a parameter to other functions
- return it as result from other functions

5. *Higher-order functions*
- When we talk about higher-order functions, we mean a function that either:
takes one or more functions as arguments, or
returns a function as its result
The doubleOperator function we implemented above is a higher-order function because it takes an operator function as an argument and uses it.
EXamples:
* Filter: `Given a collection, we want to filter by an attribute. The filter function expects a true or false value to determine if the element should or should not be included in the result collection. Basically, if the callback expression is true, the filter function will include the element in the result collection. Otherwise, it will not.`
* Map:`The map method transforms a collection by applying a function to all of its elements and building a new collection from the returned values.`
* Reduce:`The idea of reduce is to receive a function and a collection, and return a value created by combining the ite`