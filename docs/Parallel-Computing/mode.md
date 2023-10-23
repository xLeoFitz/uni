# This is a test Homepage for Parallel Computing

Task -> Parallel Software -> Solution

What is a good solution?
- Fulfill a set of hard tast-specific metrics
- Soft metrics exist, e.g.:
    - Do we trust the software?
    - Is the future development of the software secured?
    - Does our current/future hardware support the software?
- Parallel computing is a core-driver for innovation; tradeoffs for more parallelism have to be considered

## Time-to-Solution
Mission Statemant
$$Value of an operation = \frac{Solution}{Operation}$$ maximize
$$Throughput = \frac{Operations}{second}$$ maximize
$$Time-to-Solution = \frac{Solution}{Value \cdot Throughput}$$ minimize

## Summary
- Best time-to-solution requires us to maximize the throughput and the value of each operation; often two contradicting targets
- Time-to-solution is a good metric to keep in mind when diving into advanced parallel computing topics
- Time-to-solution is not the one and only truth, other metrics exist, e.g, energy-to-solution, $-to-solution, science-per-flop, […]
- Goal of this lecture: Maximize throughput via parallel computing, keep an eye on the value of the operations
- Additional parallel computing- specific metrics later in this class, e.g., scalability
