# alu-shell - I/O Redirections and Filters

This repository contains Unix shell scripts designed to explore and demonstrate the power of I/O redirections, data filtering tools, pipelines, and basic text processing automation in a Linux (Ubuntu 20.04 LTS) environment.

## Script Requirements & Constraints
* All scripts are exactly two lines long (`#!/bin/bash` followed by the command).
* Every file ends cleanly with a trailing newline.
* Script operations strictly bypass the use of backticks, `&&`, `||`, `;`, `sed`, or `awk`.
* All files are configured with executable permissions.

---

## Directory: `io_redirections_and_filters`

| File Name | Description |
| :--- | :--- |
| `0-hello_world` | Prints "Hello, World" followed by a newline to the standard output. |
| `1-confused_smiley` | Displays the specific confused facial smiley character composition: `"(Ôo)'`. |
| `2-hellofile` | Displays the raw system content of the `/etc/passwd` file. |
| `3-twofiles` | Displays the combined content of both the `/etc/passwd` and `/etc/hosts` system files. |
| `4-lastlines` | Displays only the final 10 trailing lines of the `/etc/passwd` file. |
| `5-firstlines` | Displays only the initial 10 leading lines of the `/etc/passwd` file. |
| `6-third_line` | Displays exactly the 3rd line of a file named `iacta` located in the current working directory. |
| `7-file` | Creates a custom-named file featuring heavy special character escapes (`*\\'"Best School"\'\\*$\?\*\*\*\*\*:)`) filled with the text `Best School`. |
| `8-cwd_state` | Writes the detailed layout state of the current working directory (`ls -la`) into a tracker file named `ls_cwd_content` (overwriting it if it exists). |
| `9-duplicate_last_line` | Duplicates the exact last line of the file `iacta` and appends it to the end of the same file. |
| `10-no_more_js` | Recursively searches the current directory and subdirectories to delete all regular files ending in a `.js` extension. |
| `11-directories` | Counts the exact number of directories and sub-directories in the current workspace, including hidden ones (excluding `.` and `..`). |
| `12-newest_files` | Displays the 10 newest modified files in the current working directory, ordered from newest to oldest (one file per line). |
| `13-unique` | Filters a stream of raw words, sorting them alphabetically and printing only the entries that appeared exactly once. |
| `14-findthatword` | Filters and displays lines inside `/etc/passwd` containing the target pattern string "root". |
| `15-countthatword` | Calculates and returns the total count of lines inside `/etc/passwd` containing the string "bin". |
| `16-whatsnext` | Matches the pattern "root" inside `/etc/passwd` and returns the matching lines along with the subsequent 3 lines following each match. |
| `17-hidethisword` | Inverts filtering to display all entries inside `/etc/passwd` that do **not** contain the pattern string "bin". |
| `18-letteronly` | Parses the system ssh daemon configuration to display only lines that start strictly with an alphabetical letter (capital or lowercase). |
| `19-AZ` | Acts as a character map translator, replacing all input instances of `A` and `c` with `Z` and `e` respectively. |
| `20-hiago` | Trims all structural instances of the letters `c` and `C` directly out of a standard input stream. |
| `21-reverse` | Reverses the positional layout order of any incoming input text strings string-by-string. |
| `22-users_and_homes` | Extracts, isolates, and displays all system usernames matched to their home directories out of `/etc/passwd`, sorted cleanly by user names. |
| `23-empty_casks` | Recursively searches the directory map to surface and print *only* the base file/directory names of objects containing zero byte data data-size. |
| `24-gifs` | Recursively crawls directories to locate regular `.gif` files, strips their trailing extension, and lists them via a case-insensitive byte value sort. |
| `25-acrostic` | Decodes a hidden vertical poem sequence (acrostic) by isolating the first character of every line and joining them into a clean single line. |
| `26-the_biggest_fan` | Parses structural TSV web server data streams, aggregates unique hits, and tracks down the top 11 host/IP connections generating the most web request traffic. |
