# IO500
The IO500 benchmark has been developed together with the community and its development is still ongoing. The benchmark is essentially a benchmark suite bundled with execution rules. It harnesses existing and trusted open source benchmarks.

The goal for the benchmark is to capture user-experienced performance. It aims to be:
- Representative
- Understandable
- Scalable
- Portable
- Inclusive
- Lightweight
- Trustworthy

# Workloads

The benchmark covers various workloads and computes a single score for comparison. The workloads are:
- **ior-easy**: Applications with well optimized I/O patterns (one file per process, large writes)
- **ior-hard**: Applications that require a poorly-formed IO workload (47008-byte interleaved shared-file write)
- **mdtest-easy**: Metadata in a well-organized tree (one directory per process)
- **mdtest-hard**: Metadata/small files (3901 byte files in a single shared directory)
- **find**: Finding relevant objects based on patterns

The individual performance numbers are preserved and accessible via the web or the raw data. This allows deriving other relevant metrics.

We are in the process to establish a procedure to extend the current workload with further meaningful metrics. 
