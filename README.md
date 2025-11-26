How to Build and Run (The "Magic" Command)

1. **Install the build tool:**

    ```bash
    
    pip install maturin
    ```

2.  **Build the Rust library:**
    
    In your terminal, inside the `optitok` folder (where `Cargo.toml` is):

    ```bash
    maturin develop --release
    ```

      * `develop`: Installs the package into your current python environment.
      * `--release`: Turns on all optimizations (makes it 10-100x faster).

3.  **Run the Python script:**
    
    Now we can use `SOTATokenizer` in our scripts.