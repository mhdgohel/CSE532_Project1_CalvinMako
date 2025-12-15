# CSE532 Project 1: Calvin & Mako

This repository serves as the parent directory for CSE532 Project 1, containing submodules for the **CalvinMako** and **Enhanced Calvin** systems. This structure is designed for redirecting to the respective project implementations.

## Repository Structure

The repository is organized into two main submodules:

### 1. [CalvinMako](./CalvinMako)
**Mako** is a high-performance distributed transactional key-value store with geo-replication support.
- **Documentation**: See [CalvinMako/README.md](./CalvinMako/README.md) for detailed architecture, installation, and benchmarking instructions.

### 2. [Enhanced Calvin](./enchanced_calvin)
**Enhanced Calvin** is an implementation based on the Calvin deterministic database system.
- **Documentation**: See [enchanced_calvin/README](./enchanced_calvin/README) and [enchanced_calvin/INSTALL](./enchanced_calvin/INSTALL) for prerequisites and build steps.

## Getting Started

To clone this repository and ensure all submodules are downloaded correctly, use the recursive flag:

```bash
git clone --recursive <repository-url>
```

If you have already cloned the repository without the recursive flag, you can initialize the submodules with:

```bash
git submodule update --init --recursive
```

## Navigation

- Go to **[CalvinMako](./CalvinMako)** for the Mako implementation.
- Go to **[enchanced_calvin](./enchanced_calvin)** for the Enhanced Calvin implementation.
