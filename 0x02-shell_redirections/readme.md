# 0x02. Shell, I/O Redirections and Filters

## Description

This project focuses on learning how to use I/O redirections and filters in shell scripting. Each task includes writing a shell script that performs specific operations related to file manipulation, input/output redirections, and text processing using basic shell commands.

---

## Learning Objectives

By the end of this project, you should be able to:

- Use commands such as `cat`, `head`, `tail`, `find`, and `echo`.
- Redirect standard input and output using `>`, `>>`, `<`, and `|`.
- Work with special characters in file names.
- Manipulate file content from the command line.
- Understand how to write efficient one-liner scripts.

---

## Project Structure

| File | Description |
|------|-------------|
| `0-hello_world` | Prints "Hello, World" to standard output |
| `1-confused_smiley` | Displays the confused smiley: `"(Ôo)'` |
| `2-hellofile` | Displays the contents of `/etc/passwd` |
| `3-twofiles` | Displays contents of both `/etc/passwd` and `/etc/hosts` |
| `4-lastlines` | Shows the last 10 lines of `/etc/passwd` |
| `5-firstlines` | Shows the first 10 lines of `/etc/passwd` |
| `6-third_line` | Displays the 3rd line of a local file `iacta` without using `sed` |
| `7-file` | Creates a file with special characters in its name containing "Best School" |
| `8-cwd_state` | Saves the result of `ls -la` into `ls_cwd_content`, overwriting if exists |
| `9-duplicate_last_line` | Appends the last line of the file `iacta` to itself |
| `10-no_more_js` | Deletes all `.js` files recursively in the current directory and subdirectories |

---

## Usage

To run a script:
```bash
./<file_name>
