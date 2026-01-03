# cache-simulator-cpp
Cache Memory Simulator in C++ ( direct mapped + LRU + FIFO)
# Cache Simulator in C++

This project simulates a Direct Mapped Cache using C++.
It calculates cache hits and misses for a given sequence of memory addresses.

## Features
- Direct Mapped Cache
- Fully Associative Cache
- Replacement Policies: FIFO, LRU
- Step-by-step simulation output
- CSV-based data generation for graph plotting

## How It Works
- User inputs cache size, block size, and memory addresses
- Direct Mapped: Index = (Address / Block Size) % NumberOfBlocks
- Fully Associative: Any block can be replaced using FIFO or LRU
- The simulator tracks hits and misses accordingly

## Future Work
- Set Associative Cache
- Write Policies (Write-Through, Write-Back)

## Tools Used
- C++
- VS Code
- GitHub
