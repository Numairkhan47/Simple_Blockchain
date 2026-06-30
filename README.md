# Simple Blockchain in Python

## Description

This project implements a basic blockchain in Python using SHA-256 hashing. Each block stores data, its own hash, and the previous block’s hash to create a linked chain of blocks.

The project demonstrates fundamental blockchain concepts including:

* Block creation
* Hash generation using SHA-256
* Genesis block initialization
* Linking blocks using previous hashes
* Basic data integrity mechanism

## Features

* Create a blockchain
* Add new blocks
* Generate secure hashes
* Maintain block relationships

## Requirements

* Python 3.x

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Move into the project folder:

```bash
cd <project-folder>
```

Run the program:

```bash
python blockchain.py
```

## Project Structure

```text
project/
│
├── blockchain.py
└── README.md
```

## Example Output

```text
{'data': 'gen-data', 'hash': '...', 'pre_hash': '...'}
{'data': '1', 'hash': '...', 'pre_hash': '...'}
{'data': '2', 'hash': '...', 'pre_hash': '...'}
{'data': '3', 'hash': '...', 'pre_hash': '...'}
```
