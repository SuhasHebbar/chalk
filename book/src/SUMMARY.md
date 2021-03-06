# Summary

- [What is Chalk?](./what_is_chalk.md)
    - [Crates](./what_is_chalk/crates.md)
- [Contribution guide](./contribution_guide.md)
- [REPL](./repl.md)
- [Representing and manipulating Rust types](./types.md)
    - [The role of the `Interner`](./types/role_of_interner.md)
    - [Controlling representation with `Interner`](./types/how_to_control_repr.md)
    - [Rust types](./types/rust_types.md)
        - [Application types](./types/rust_types/application_ty.md)
    - [Rust lifetimes](./types/rust_lifetimes.md)
    - [Operations](./types/operations.md)
        - [Fold and the Folder trait](./types/operations/fold.md)
- [Representing traits, impls, and other parts of Rust programs](./rust_ir.md)
- [Lowering Rust IR to logic](./clauses.md)
    - [Unification and type equality](./clauses/type_equality.md)
- [How does the engine work](./engine.md)
- [Glossary and terminology](./glossary.md)
