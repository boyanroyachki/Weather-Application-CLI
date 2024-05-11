# Weather CLI Application

This is a command line interface (CLI) application for weather updates, written in Rust.

## Prerequisites

Before running the program, ensure you have Rust installed on your system. You can download Rust from [the official Rust website](https://www.rust-lang.org/).

## Configuration

To run the application, you need to create a configuration file in the root directory of the project:

1. **Create a JSON file named `config.json`:**

    ```json
    {
        "api_key": "YOUR_API_KEY"
    }
    ```

2. **Replace `YOUR_API_KEY` with your actual API key.**

    This key allows the application to fetch weather data from the weather API. Obtain an API key from your weather data provider and replace `YOUR_API_KEY` with the actual key.

## Running the Application

To run the application, use the following command in the terminal:

```bash
cargo run
