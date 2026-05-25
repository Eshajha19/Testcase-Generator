# Testcase-Generator

A robust and flexible tool designed to automate the generation of test cases for competitive programming, algorithm validation, and software testing.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Customizable Constraints**: Easily define ranges for integers, lengths for strings, and sizes for arrays.
- **Multiple Data Types**: Built-in support for common types including integers, floats, strings, and nested structures.
- **Reference Validation**: Automatically generate expected output files by running inputs against a reference solution.
- **Batch Generation**: Efficiently create large sets of test cases for stress testing.
- **Platform Compatible**: Generated cases are formatted to be compatible with popular Online Judges (OJs).

## Getting Started

### Prerequisites

- Python 3.8+ (or your preferred runtime)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Testcase-Generator.git
   cd Testcase-Generator
   ```

2. (Optional) Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

## Usage

To generate test cases using the default configuration, run:

```bash
python main.py --config config.json --output ./tests
```

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

## License

Distributed under the MIT License. See `LICENSE` for more information.