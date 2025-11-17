---
title: "POSIX Download Manager"
description: "A multi-threaded CLI download manager in C++ using POSIX threads. Supports parallel chunk downloading, synchronization, and efficient memory-safe I/O."
tech: ["cpp", "posix-pthreads", "cli", "file-io", "oop"]
features: ["Parallel chunk downloading", "Resume capability", "Thread-safe I/O", "Configurable concurrency", "Checksum verification"]
github: "https://github.com/pri2003yam/Download-manager"
stars: 0
order: 5
---

## Overview

POSIX Download Manager is a lightweight, multi-threaded CLI tool written in C++ that supports parallel chunked downloads, resume capability and efficient memory-safe I/O using pthreads.

## Key Features

- Parallel chunk downloading with configurable concurrency.
- Resume downloads using partial file metadata and range requests.
- Thread-safe I/O and minimal memory overhead.
- Cross-platform POSIX-compatible code (Linux/macOS).

## Build & Use

```bash
git clone https://github.com/pri2003yam/Download-manager.git
cd Download-manager
make
# download with 8 threads
./downloader -t 8 https://example.com/largefile.zip
```

## Notes

- Designed for reliability: automatic retries and checksum verification (if available).
- Check the repo README for advanced options (bandwidth limit, proxy, logging).

## Links

- Repo: https://github.com/pri2003yam/Download-manager

