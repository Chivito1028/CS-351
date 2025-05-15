Unoptomized (-g) Real Time User Time System Memory Throughput Speedup vs hash -00

Program

Hash-00 335.09 337.81 10.13 2880 0.045 1.00

Hash-01 23.53 16.66 2.96 2880 0.680 15.1

Hash-02 15.80 14.18 1.28 2880 1.01 22.5

Hash-03 16.38 14.96 1.22 2880 0.98 21.7

Hash-04 14.43 12.92 0.38 5012352 1.11 24.6

Optimized(-02)

Program

Hash-00 334.48 328.62 2.85 2880 0.048 1

Hash-01 7.82 6.72 1.03 2880 2.05 42.8

Hash-02 8.17 6.82 1.21 3456 1.96 40.9

Hash-03 8.04 6.68 1.26 2880 1.99 41.6

Hash-04 7.11 6.45 0.48 5011776 2.25 47.0

1. Parsing through all the characters in the string
2. alloca() is faster.
3. Yes because by using a fixed array it does not need to dynamocilly allocate space as often.
4. Since the memory is shared with the o/s then it allocates larger memory area.
