# Website Checker

This Rust project application checks the HTTP status of websites. It also provides the  live output and saves the results in a JSON file.

## Build Instructions

In order to run the application, use this command:

```bash
cargo build --release
```
I chose to use this command since it is to easy to execute when accessing the target/release/website_checker directory.

This is the format of the command 
```bash
./target/release/website_checker [--file <sites.txt>] [suspicious link removed] [--workers N] [--timeout S] [--retries N]
```
This is basically what each [ ] does:

