# PerfLab — CPU Performance & Memory Analyzer

PerfLab is a C++ benchmarking project that compares matrix multiplication algorithms and measures their execution time.

## Features

* Compare different matrix multiplication implementations.
* Measure execution time across repeated runs.
* Validate computation results using checksums.
* Record benchmark results in CSV format.

## Technologies Used

* C++17
* Standard C++ Chrono library
* CSV

## Project Structure

```text
PerfLab/
├── src/
│   └── main.cpp
├── results/
│   └── benchmark.csv
├── .gitignore
└── README.md
```

## How to Run

Compile the program:

```bash
clang++ -std=c++17 -O2 src/main.cpp -o perflab
```

Run the program:

```bash
./perflab
```

## Future Improvements

* Cache simulation
* Multithreading experiments
* Performance visualization

## Author

Sachin Ram N P
