---
description: Give an overview of the inspiration for Verse and its design.
---

# About Verse

## Inspiration

Verse was inspired by several programming languages: Python \([link](https://python.org/)\) which uses duck-typing and whitespace-sensitive syntax, Dotty \([link](https://dotty.epfl.ch/)\) which is a future Scala \([link](https://scala-lang.org/)\) release and blends OOP with FP on the JVM, Haskell \([link](https://haskell.org/)\) which is purely-functional, the Go \([link](https://golang.org/)\) use of implicit interfaces, and a _few_ pieces from Perl 6 \([link](https://perl6.org/)\).

A common issue faced by new developers is the decision of whether to use OOP or FP. Scala/Dotty strikes a balance, but we feel it could be better. Verse balances OOP and FP by encouraging use of new OOP types while implementing them in a FP manner.

Python follows the rule of [duck typing](https://en.wikipedia.org/wiki/Duck_typing): if it looks like a duck, and sounds like a duck, then it is a duck. By allowing gradual typing in Verse, we allow the programmer to gradually build up to a fully-typed program.

## What Verse _Is_

Verse is a [functional ](https://en.wikipedia.org/wiki/Functional_programming)and [object-oriented](https://en.wikipedia.org/wiki/Object-oriented_programming) programming language with [gradual ](https://en.wikipedia.org/wiki/Gradual_typing)typing \(the compiler will deduce types for you whenever it can\).

We chose for it to be functional because functional programs are easier to reason about: a function, given identical inputs, will produce identical outputs.

We chose for Verse to be object-oriented because it is useful in making information more concise. Mathematicians often create words that mean something useful, so we should be able to do the same as programmers with our data structures.

With gradual typing, Verse allows the programmer to omit type annotations when it is suitable.

Verse can be used as a [system programming language](https://en.wikipedia.org/wiki/System_programming_language) \(in the future\).

Verse is an [interpreted ](https://en.wikipedia.org/wiki/Interpreted_language)language.

## What Verse _Is Not_

Verse is not a scripting language.

Verse is not purely-functional. Verse allows non-functional code in blocks marked `unsafe`. 

