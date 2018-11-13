# Rust Syntax Index

* [Keywords](#keywords)
  - [Currently in Use](#currently-in-use)
  - [Reserved for Future Use](#reserved-for-future-use)
* [Operators and Symbols](#operators-and-symbols)
  - [Operators](#operators)
  - [Non-operator Symbols](#non-operator-symbols)

## Keywords

### Currently in Use

The following keywords currently have the functionality described.

* **`as`** - perform primitive casting, disambiguate the specific trait containing
  an item, or rename items in `use` and `extern crate` statements.
  
  *RPL FE*: [Casting Between Types (`as`)], [Universal Function Call Syntax (Angle-bracket Form)], [Associated Types]
  
  *RPL 2018E*: [Fully Qualified Syntax for Disambiguation: Calling Methods with the Same Name]
  
  *RR*: [Type cast expressions], [Trait objects], [Disambiguating Function Calls]
* `break` - exit a loop immediately
* `const` - define constant items or constant raw pointers
* `continue` - continue to the next loop iteration
* `crate` - link an external crate or a macro variable representing the crate in
  which the macro is defined
* `dyn` - dynamic dispatch to a trait object
* `else` - fallback for `if` and `if let` control flow constructs
* `enum` - define an enumeration
* `extern` - link an external crate, function, or variable
* `false` - Boolean false literal
* `fn` - define a function or the function pointer type
* `for` - loop over items from an iterator, implement a trait, or specify a
  higher-ranked lifetime
* `if` - branch based on the result of a conditional expression
* `impl` - implement inherent or trait functionality
* `in` - part of `for` loop syntax
* `let` - bind a variable
* `loop` - loop unconditionally
* `match` - match a value to patterns
* `mod` - define a module
* `move` - make a closure take ownership of all its captures
* `mut` - denote mutability in references, raw pointers, or pattern bindings
* `pub` - denote public visibility in struct fields, `impl` blocks, or modules
* `ref` - bind by reference
* `return` - return from function
* `Self` - a type alias for the type implementing a trait
* `self` - method subject or current module
* `static` - global variable or lifetime lasting the entire program execution
* `struct` - define a structure
* `super` - parent module of the current module
* `trait` - define a trait
* `true` - Boolean true literal
* `type` - define a type alias or associated type
* `unsafe` - denote unsafe code, functions, traits, or implementations
* `use` - bring symbols into scope
* `where` - denote clauses that constrain a type
* `while` - loop conditionally based on the result of an expression

[Casting Between Types (`as`)]: https://doc.rust-lang.org/book/first-edition/casting-between-types.html#as
[Universal Function Call Syntax (Angle-bracket Form)]: https://doc.rust-lang.org/book/first-edition/ufcs.html#angle-bracket-form
[Associated Types]: https://doc.rust-lang.org/book/first-edition/associated-types.html

[Fully Qualified Syntax for Disambiguation: Calling Methods with the Same Name]: https://doc.rust-lang.org/book/2018-edition/ch19-03-advanced-traits.html#fully-qualified-syntax-for-disambiguation-calling-methods-with-the-same-name

[Type cast expressions]: https://doc.rust-lang.org/reference/expressions/operator-expr.html#type-cast-expressions
[Trait objects]: https://doc.rust-lang.org/reference/types.html#trait-objects
[Disambiguating Function Calls]: https://doc.rust-lang.org/reference/expressions/call-expr.html#disambiguating-function-calls

### Reserved for Future Use

The following keywords do not have any functionality but are reserved by Rust
for potential future use.

* `abstract`
* `async`
* `become`
* `box`
* `do`
* `final`
* `macro`
* `override`
* `priv`
* `try`
* `typeof`
* `unsized`
* `virtual`
* `yield`

## Operators and Symbols

### Operators

### Non-operator Symbols
