# Huffman Coding - Text Compression Algorithm

## 📌 Overview
This project implements **Huffman Coding**, a lossless data compression algorithm, in C++. It reads text from a file, compresses it using variable-length encoding based on character frequency, and decompresses it back to the original text.

## 🛠️ Tech Stack
- **Language**: C++
- **Concepts**: Binary Trees, Priority Queues (Min-Heap), Greedy Algorithms, File I/O

## 📁 Files in this Repository
| File | Description |
|------|-------------|
| `main.cpp` | Program entry point and menu |
| `HuffmanEncoder.cpp` | Huffman encoding/decoding logic |
| `HuffmanEncoder.h` | Class and struct definitions |
| `input.txt` | Sample input (`zahra`) |
| `compressed_bits.txt` | Compressed output (bit stream) |
| `output_decompressed.txt` | Decompressed output (matches input) |
| `huffman_report.txt` | Console output log (tree, frequencies, codes) |
| `Flowchart.png` | Algorithm flowchart |
| `DSA PROJECT REPORT(FINALEE).pdf` | Complete project documentation |

## 🚀 How to Compile & Run
```bash
g++ main.cpp HuffmanEncoder.cpp -o huffman
./huffman