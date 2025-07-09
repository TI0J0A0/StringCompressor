# 🔡 String Compressor

[![Java](https://img.shields.io/badge/Java-17+-red?logo=java)](https://www.oracle.com/java/)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![Code Quality](https://img.shields.io/badge/code_style-clean-important)]()

A simple yet efficient Java project that implements a string compression algorithm.  
If a character is repeated consecutively, it's replaced by the character followed by the count of its occurrences — **but only if the result is shorter** than the original string.

---

## 🧠 Problem Statement

Compress strings using the rule:

> Replace repeated characters with that character followed by the number of repetitions — but only if the compressed version is shorter than the original.

### ✅ Examples

```java
Input:  "aaabbbcc"
Output: "a3b3c2"

Input:  "abcdef"
Output: "abcdef" // compressed version "a1b1c1d1e1f1" is longer
