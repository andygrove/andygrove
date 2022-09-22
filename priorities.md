# What Am I Working On?

## Spark RAPIDS

Tracking: [Issues](https://github.com/NVIDIA/spark-rapids/issues/assigned/andygrove) [PRs](https://github.com/NVIDIA/spark-rapids/pulls/andygrove)

Current areas of focus:

- AQE / CBO research
- Improve Delta Lake support
- Regular Expression support

## Dask SQL

Tracking: [Issues](https://github.com/dask-contrib/dask-sql/issues/assigned/andygrove) [PRs](https://github.com/dask-contrib/dask-sql/pulls/andygrove)

Current areas of focus:

- Support complex aggregate queries with DISTINCT aggregates
- Improve quality of Rust code and add more Rust unit tests

## DataFusion

Tracking: [Issues](https://github.com/apache/arrow-datafusion/issues/assigned/andygrove) [PRs](https://github.com/apache/arrow-datafusion/pulls/andygrove)

Current areas of focus (mostly driven by Dask SQL requirements):

- PR reviews (especially in SQL query planning and logical plan optimizations)
- Improve Type Coercion logic
- Improve quality of the logical plan optimizer
- Improve SQL support to cover popular benchmarks
- Improve error handling (replace `panic!` and `unwrap()` with `Result`)
- Release Management 

## sqlparser-rs

Tracking: [Issues](https://github.com/sqlparser-rs/sqlparser-rs/issues/assigned/andygrove) [PRs](https://github.com/sqlparser-rs/sqlparser-rs/pulls/andygrove)

Current areas of focus:

- PR reviews
- Release Management

## Ballista

Tracking: [Issues](https://github.com/apache/arrow-ballista/issues/assigned/andygrove) [PRs](https://github.com/apache/arrow-ballista/pulls/andygrove)

Ballista is mostly my weekend hobby project for now, but I am also the only active Arrow PMC involved in the project so I spend some time on related duties.

Current areas of focus:

- Improve usability (user interface, documentation, etc)
- Review PRs
- Run popular SQL benchmarks and compare query plans with other solutions (Spark, Dask SQL)
- Release Management
