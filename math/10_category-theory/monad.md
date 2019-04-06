# Monad

Monad functional structure, originated in the category theory, was introduced into functional programming languages in the 1990s, becoming more prominent with the popularity of the pure functional languages, such as Haskell.


## The State
The state of a system is composed of global variables, IO and anything that's not local to a particular function. This state is time-dependent; if various parts of program are able to change the state, then the configuration of the state varies with time.

The problem with state mutation is especially evident in concurrent programming, e.g. where two functions access and change the same global value. One function reads the global value and starts some processing involving that value. In the meantime, another function updates that global value. At that moment the first function is already dealing with a stale value, but so far the corruption is contained within it. It is when that function writes back the result, which it obtained based on old data, that the corruption infects the global state. Having mutable state gives rise to an entire domain of problems, from iterator invalidation to data races.

Managing the global state is problematic because it doesn't have a manager or owner; no language entity owns the state, but all language entities have access to it.

Modern programming languages, such as Rust, have introduced the concept of ownership, such that every value is owned by exactly one variable. A variable that owns a value/resource can borrow it to other parts of the program, even multiple times, as long as it is borrowed for reading only. In order to mutably borrow its value, there cannot be any outstanding read-only borrows and it can only do exclusive mutable borrows. Generally, a value can have either multiple readers or an exclusive writer.

Pure functional languages deal with the problem of state mutation by disallowing it completely. All identifiers in a pure FP language have the quality of *referential transparency*, which means once an identifier is bound to an expression, it cannot be rebound, therefore, it has the exact same value throughout the program. Referencing that identifier is always transparent.



Types have their own set of fundamental functions associated with themselves; e.g. integer types have the set of arithmetic (and other math) functions. The fundamental function associated with a string type is concatenation. A boolean type has the set of logic functions.

To qualify as a monad, a type must have a function, of particular form, which uses the monad's *pertinent value*.

To qualify as a monad, a type must have a `bind` function.



---

https://www.infoq.com/articles/Understanding-Monads-guide-for-perplexed
