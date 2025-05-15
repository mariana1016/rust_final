# Website Checker

This Rust project application checks the HTTP status of websites. It also provides the  live output and saves the results in a JSON file.

## Build Instructions

In order to run the application, use this command:

```bash
cargo build --release
```
I chose to use this command since it is to easy to execute when accessing the target/release/website_checker directory.
-

This is the format of the command 
```bash
./target/release/website_checker [--file <sites.txt>] [suspicious link removed] [--workers N] [--timeout S] [--retries N]
```
### This is what each [ ] does

--file <sites.txt>: This specifies a text file containing a list of URLs to check, but it works only one URL per line. This references the example of 50 sites that I provided (sites.txt). You can use any valid website, but I provided examples since it was a requirement \
suspicious link removed: You can use one or more urls as command line arguments \
--workers N: the number of worker threads we are going to use \
--timeout S: the timeout for each http request \
--retries N: the amount of retries after each url failure  \
_
#### One URL at a time


