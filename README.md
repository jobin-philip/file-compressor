# file-compressor
  
file-compressor is a lightweight Rust utility for basic file compression using Gzip.

## Prerequisites

Make sure you have Rust installed. If not, you can download it [here](https://www.rust-lang.org/tools/install).


## Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/jobin-philip/file-compressor.git
   cd file-compressor
   ```
   
2. **Run the program:**
   ```bash
   cargo run -- 'source_file_path' 'target_file_path'
   ```

## Usage
   ```bash
   cargo run -- 'source_file_path' 'target_file_path'
   ```
   Replace **'source_file_path'** with the path to the file you want to compress and **'target_file_path'** with the desired path for the compressed output.

## Example
   ```bash
   cargo run -- input.txt output.gz
   ```
   
   This will compress **'input.txt'** and create a compressed file named **'output.gz'**.

## Features

-   Simple and efficient file compression using the Gzip algorithm.
-   Command-line interface for easy usage.
-   Outputs information about the source and target file sizes, as well as compression time.
   
## License

This project is licensed under the [MIT License](LICENSE).