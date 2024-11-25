## Overview

This repository is designed to assist in creating `.job` test files for the **IST Key Value Store (IST-KVS)** project. The IST-KVS project is a scalable key-value storage system implemented with a hash table, offering parallelization, synchronization, and inter-process communication. This repository provides an automated tool to generate commands for testing, ensuring robust evaluation and debugging.

## How to Use

### Prerequisites

- Python 3.6 or higher.

### Steps to Generate Test Files

1. **Clone the Repository**
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```
   
2. **Set the number of tests to generate**
- Change the value of `NUMBER_OF_TESTS` to your desired number of tests.
- The default number is 100.
  

4. **Run the Script**
   Execute the script to generate a series of commands:
   ```bash
   python generate_jobs.py
   ```

## Contribution

- Fork the repository and submit pull requests for improvements or bug fixes.

---

By following this guide, you can create and validate `.job` test files to thoroughly evaluate the IST-KVS system and ensure its functionality and reliability under diverse conditions.
