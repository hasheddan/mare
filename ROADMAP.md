### Features from Pony (and other basic language features)

- [x] - FFI function calling
- [x] - Stateless, non-allocated primitives with pure functions
- [x] - Numeric machine word types
- [x] - Stateful, allocated classes with constructors and methods
- [x] - Properties (fields hidden behind getters/setters)
- [x] - Interfaces
- [ ] - Virtual table calls on abstract types
- [ ] - Boxed numeric values
- [ ] - Non-looping flow control (`if`, `match`, etc)
- [ ] - Looping flow control (`while`, etc)
- [ ] - Reference capabilities (`iso`, `trn`, `val`, `ref`, `box`, `tag`)
- [ ] - Actors and behaviours
- [ ] - For-loop iterator syntax sugar (`for x in y`)
- [ ] - Generic types
- [ ] - FFI-compatible struct types

### New features (that were *NOT* in Pony)

- [x] - Compile-time constant values
- [x] - User-defined custom numeric types (`numeric MyNumber:`)
- [ ] - Enumerated custom numeric types (`enum MyEnum:`)
- [ ] - Non-allocated class references with "static" stateless functions.
- [ ] - Typeclasses (`implement SomeInterface for SomeClass:`)
- [ ] - Automatic specialization of functions to avoid virtual table calls.

### New sugar and other conveniences

- [x] - More type inference (return types, parameter types, etc)
- [x] - Self-value syntax sugar (`@`, `@method(args)`, etc)
- [x] - Setter syntax sugar (`obj.prop = value` calls the `prop=` method)
- [x] - Parameter assign expression syntax sugar (`new (@propa, @propb)`)

### Tooling features

- [ ] - Docker image of the Mare compiler
- [ ] - Distributable package for Linux with Mare compiler static binary
- [ ] - Sublime Text syntax highlighting support
- [ ] - Language Server Protocol support
- [ ] - Doctests support
- [ ] - Dependency manager / package manager