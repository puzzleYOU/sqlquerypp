# DEPRECATED: sqlquerypp – a SQL query preprocessor

`sqlquerypp` was a library for preprocessing SQL queries to transform SQL queries
written down in a simple syntax to complex, highly optimized recursive MySQL 8 CTEs.

We noticed that the preprocessor implementation contains various pitfalls and bugs,
so we suggest to not use it anymore because we refrain from using it ourselves after
we could solve the necessary query optimization differently.

Nonetheless, we decided to keep the repository as it may be useful to inspect how to
set up a simple Rust-based Python extension with
* mixed Rust & Python source code using [PyO3](https://github.com/PyO3/pyo3)
* unit tests in both Rust and Python unit tests
* GitHub Actions for CI and PyPI publishing
