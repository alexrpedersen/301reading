# Refactoring

## refactoring

#### When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

### Higher-order functions
#### When we talk about higher-order functions, we mean a function that either:

#### takes one or more functions as arguments, or
#### returns a function as its result
#### The doubleOperator function we implemented above is a higher-order function because it takes an operator function as an argument and uses it.

#### You’ve probably already heard about filter, map, and reduce. Let's take a look at these.

### Filter
#### Given a collection, we want to filter by an attribute. The filter function expects a true or false value to determine if the element should or should not be included in the result collection. Basically, if the callback expression is true, the filter function will include the element in the result collection. Otherwise, it will not.
