---
title: "Huffman File Compressor"
description: "High-performance C++ compression CLI tool implementing Huffman encoding with priority queue, bit-packing and optimized I/O."
tech: ["cpp", "makefile", "stl"]
features: ["Huffman tree construction", "Bit-level packing", "Buffered I/O", "Cross-platform Makefile", "Optimized performance"]
github: "https://github.com/pri2003yam/HuffmanCompressor"
stars: 0
order: 3
---

## Overview

High-performance command-line Huffman file compressor implemented in modern C++ (C++17). Designed for speed and compact output using priority queues, efficient bit-packing and buffered I/O.

## Key Features

- Efficient Huffman tree construction and encoding for byte streams.
- Bit-level packing to minimize output size.
- Fast I/O using buffered reads/writes and small memory footprint.
- Cross-platform Makefile for easy builds.

## Build & Use

```bash
git clone https://github.com/pri2003yam/HuffmanCompressor.git
cd HuffmanCompressor
make
# compress
./huffc encode input.bin output.huff
# decompress
./huffc decode output.huff restored.bin
```

## Notes

- The tool focuses on clarity and performance; profiling-guided optimizations were applied to hot paths.
- See `README.md` in the repo for detailed file format and benchmarks.

## Links

- Repo: https://github.com/pri2003yam/HuffmanCompressor

