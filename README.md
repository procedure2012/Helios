# Helios Development Repository

> 🚧 **Development Branch** - main development repository for Helios

## About Helios

Helios is a modular ETL framework with pluggable sources and sinks.

## 🔧 Development Status

This repository is under active development. Many features are TODO.

### 🔴 High Priority TODOs

- There are currently 7 open TODOs across 4 files.

### 📝 Complete TODO List

- [ ] **helios/core/scheduler.py:4** - support priority-based ordering
- [ ] **helios/core/scheduler.py:5** - add retry policy with backoff
- [ ] **helios/io/readers.py:4** - infer column dtypes automatically
- [ ] **helios/io/readers.py:5** - stream large files in chunks
- [ ] **helios/io/writers.py:4** - add gzip compression option
- [ ] **helios/transform/joiner.py:4** - support hash join
- [ ] **helios/transform/joiner.py:5** - spill to disk on large joins

## 🤝 Contributing

1. Pick a TODO item from the list above
2. Implement the functionality
3. Update this README when TODOs are completed
