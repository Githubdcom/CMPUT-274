# CMPUT-274 Python & Functional Programming Cheat Sheet

This repository contains a comprehensive **two-sided cheat sheet** covering the key concepts from the CMPUT-274 course.

## Contents

The cheat sheet includes:

### Side 1 (Page 1):
- **Python Basics**: Data types, operations, control structures
- **Recursion Basics**: Simple recursion patterns, string and numeric recursion
- **Linked Lists (LList)**: Operations, recursion, building, and accessing lists
- **Higher-Order Functions**: Map, filter, fold, and building lists with functions

### Side 2 (Page 2):
- **Accumulator Pattern**: Tail recursion optimization
- **String Manipulation**: Pig Latin, Leet Speak, string equality
- **Common Patterns**: List operations, parity checking
- **Efficiency Tips**: Time and space complexity, fast vs slow algorithms
- **Key Concepts**: Functional programming principles, design recipe, recursion template

## Files

- `cheatsheet.tex` - LaTeX source file
- `cheatsheet.pdf` - Compiled PDF (ready to print double-sided)
- `.gitignore` - Excludes LaTeX auxiliary files

## How to Use

1. **Print**: Print `cheatsheet.pdf` on both sides of a single sheet
2. **Study**: Use as a quick reference for Python and functional programming concepts
3. **Customize**: Edit `cheatsheet.tex` and recompile to add your own notes

## Compiling from Source

If you want to modify the cheat sheet:

```bash
# Install LaTeX (Ubuntu/Debian)
sudo apt-get install texlive-latex-base texlive-latex-extra texlive-fonts-recommended

# Compile
pdflatex cheatsheet.tex
```

## Topics Covered

Based on the course lectures:
- 00: Introduction
- 01: What is a Program
- 02: Functions
- 03: Basic Python
- 04: Functions in Python
- 05: Simple Recursion
- 06: Linked Lists
- 07: Efficiency
- 08: Accumulators
- 09: First-Class Functions
- 10: Searching

## Code Examples

All code examples are drawn from the Python files in this repository, including:
- Factorial and recursion examples
- List operations (map, filter, fold)
- String manipulation (pig latin, leet speak)
- Efficiency patterns (accumulator vs naive)

---

**Note**: This cheat sheet is designed to fit on a single A4 sheet printed double-sided in landscape orientation.
