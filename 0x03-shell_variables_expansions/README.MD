# 0x03. Shell, init files, variables and expansions

## Description

This project is part of the ALX SE curriculum. It focuses on shell initialization files, environment and local variables, and shell expansions. You will write scripts to manipulate variables, perform arithmetic operations, and customize the shell environment.

This project counts towards **12.5%** of your final grade in SE 102.

## Learning Objectives

- Understand the difference between environment and local variables
- Know how to create, update, and delete shell variables
- Modify the shell environment
- Use expansions in shell scripts
- List and manipulate global and local shell variables
- Use shell arithmetic



## Project Structure

All scripts are stored in the directory:  
`0x03-shell_variables_expansions`

Each script:
- Has exactly **two lines**
- Starts with the shebang: `#!/bin/bash`
- Ends with a newline

---

## Task Breakdown

### `0-alias`
Creates an alias named `ls` that runs `rm *`.

### `1-hello_you`
Prints `hello` followed by the current Linux user.

### `2-path`
Adds `/action` to the end of the `PATH` environment variable.

### `3-paths`
Counts the number of directories in the current `PATH`.

### `4-global_variables`
Lists all global (environment) variables.

### `5-local_variables`
Lists all environment and local variables, and functions.

### `6-create_local_variable`
Creates a new local variable `BEST` with the value `School`.

### `7-create_global_variable`
Creates a global environment variable `BEST` with the value `School`.

### `8-true_knowledge`
Prints the sum of 128 and the value stored in the environment variable `TRUEKNOWLEDGE`.

### `9-divide_and_rule`
Prints the result of the division of `POWER` by `DIVIDE` (both are environment variables).

### `10-love_exponent_breath`
Prints the result of `BREATH` raised to the power of `LOVE` (both are environment variables).

---

## Setup Instructions

1. **Clone your GitHub repo:**
   ```bash
   git clone https://github.com/omichsam/system_engineering-devops.git
   cd system_engineering-devops/0x03-shell_variables_expansions


### Make scripts executable:
```bash 
  chmod +x * 
  ```

### Run a script (example):
```bash
    ./1-hello_you 
```