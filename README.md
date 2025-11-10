# A DAG Analysis Template

A template for research projects using Dagu.

## Why DAGs in research?

Notebooks are great for research, but they also have problems. A DAG workflow solves many of these.

- **Non-linear workflows**: notebooks are  top-to-bottom, but analyses often branch off and merge later
- **State and variables**: notebooks hide variable state and depend on execution order; DAGs make data flow explicit and repeatable.
- **Memory and scale**: notebooks retain large data in memory; DAGs save step outputs to disk and release memory.
- **Figures and artifacts**: plots don't auto-save and consume memory; DAGs produce versioned files automatically.
- **Navigation and reuse**: scrolling hinders code navigation; DAG tasks are modular, discoverable, and reusable.
- **Robustness and variants**: easily parameterize data versions and analyses; DAGs cache results and recompute only changes.

In short: replace "run cells in order" with "define tasks + dependencies" for reproducible, fast, maintainable research.

Dagu is a lightweight package that lets you run workflows defined as DAGs in a simple and efficient manner.

## Installation

```bash
# Installation instructions
```

## Usage

```bash
# Usage instructions
```
