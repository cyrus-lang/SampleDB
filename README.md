# SampleDB : A Relational Database for Demonstration and Education

This project presents a sample relational database developed using the Cyrus language. It's designed to serve as a practical example for those learning about database concepts, data modeling, and the features of the Cyrus programming language. The goal is to provide a simple yet functional model that is easy to understand, modify, and extend.

## Requirements

- [Cyrus language compiler](https://github.com/cyrus-lang/Cyrus/tree/d40af216a5a0723393020b693582c044eb623173)

This project is implemented in Cyrus. You’ll need the Cyrus compiler installed to build and run it.  
Cyrus is still under active development and not yet stable. Expect frequent changes and possible breaking updates.

## Setup

To build the project, run:

```sh
cyrus build -o ./sampledb
```

## To-Do / Roadmap

Current features:

- [x] Table creation
- [x] Column definition
- [x] Value insertion

Planned features (educational scope):

- [ ] Implement basic table relationships (foreign keys)
- [ ] Add simple SQL-like query language (SELECT, WHERE, JOIN – minimal subset)
- [ ] Support basic update and delete operations
- [ ] Improve error handling and diagnostics
- [ ] Add persistence layer (optional: simple file storage)
- [ ] Write unit tests and example scripts
- [ ] Expand documentation with tutorials and sample queries

Stretch goals (nice-to-have):

- [ ] Index support for faster lookups
- [ ] Query planner visualization (to show how queries are executed)
- [ ] Interactive CLI for experimenting with queries

## How to Contribute

We welcome contributions to improve this project. If you have an idea for a new feature, a bug fix, or a better way to explain a concept, feel free to open a pull request or submit an issue.

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push your branch and open a pull request.
