Copied from rustc with some planned minor changes:


- Write trait uses fmt::write instead of io::Write. Reasoning behind is that it's easier to implement Display for types and the fmt::Write methods are sufficent.
- Provide freestyle styling of nodes instead of a limited set of options
