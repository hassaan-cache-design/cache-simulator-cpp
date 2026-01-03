# cache-simulator-cpp
Cache Memory Simulator in C++ ( direct mapped + LRU + FIFO)
# Cache Simulator in C++

This project simulates a Direct Mapped Cache using C++.
It calculates cache hits and misses for a given sequence of memory addresses.

## Features
- Direct Mapped Cache
- Replacement Policies: FIFO, LRU
- Step-by-step simulation output
- CSV-based data generation for graph plotting

## How It Works
- User inputs cache size, block size, and memory addresses
- Cache index is calculated using:
  (Address / Block Size) % Number of Blocks
- The simulator tracks hits and misses accordingly

## Future Work
- Set Associative Cache
- Fully Associative Cache
- Write Policies (Write-Through, Write-Back)

## Tools Used
- C++
- VS Code
- GitHub
