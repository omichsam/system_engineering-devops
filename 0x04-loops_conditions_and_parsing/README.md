# 0x04. Loops, Conditions, and Parsing

> **SM - SE 102: Foundations of Linux and Version Control**   

---

##  Description

This project introduces learners to loops, conditional statements, and input parsing in **Bash scripting**. Through hands-on scripting tasks, students will gain experience using:

- **Control flow structures** (`for`, `while`, `until`)
- **Conditional statements** (`if`, `elif`, `else`, `case`)
- **Basic input parsing techniques**



##  Learning Objectives

- Understand and implement different types of loops in Bash
- Use conditional statements to guide script behavior
- Parse input and file content effectively
- Build scripts that handle edge cases and produce consistent output

---

##  Directory Structure

Your GitHub repo should follow this structure:

system_engineering-devops/
└── 0x04-loops_conditions_and_parsing/
    ├── 1-for_best_school
    ├── 2-while_best_school
    ├── 3-until_best_school
    ├── 4-if_9_say_hi
    ├── 5-4_bad_luck_8_is_your_chance
    ├── 6-superstitious_numbers
    ├── 8-for_ls
    ├── 9-to_file_or_not_to_file
    └── 10-fizzbuzz

#!/usr/bin/env bash
# This script displays "Best School" 10 times
```bash
for i in {1..10}
do
  echo "Best School"
done 
```

## 📌 Tasks Overview

### `1-for_best_school`
Display **"Best School"** 10 times using a `for` loop.

---

### `2-while_best_school`
Display **"Best School"** 10 times using a `while` loop.

---

### `3-until_best_school`
Display **"Best School"** 10 times using an `until` loop.

---

### `4-if_9_say_hi`
Display **"Best School"** 10 times, but for the **9th iteration**, display:

- Must use a `while` loop and `if` statement.

---

### `5-4_bad_luck_8_is_your_chance`
Loop from 1 to 10 using `while`, `if`, `elif`, and `else`:

- Print **"bad luck"** at iteration 4  
- Print **"good luck"** at iteration 8  
- Print **"Best School"** for all other iterations

---

### `6-superstitious_numbers`
Display numbers from **1 to 20** using a `case` statement:

- `4` → `bad luck from China`  
- `9` → `bad luck from Japan`  
- `17` → `bad luck from Italy`

---

### `8-for_ls`
Display the names of **non-hidden files** in the current directory using a `for` loop:

- Show only the part of each filename **after the first dash (-)**  
- Example: `1-for_best_school` → `for_best_school`

---

### `9-to_file_or_not_to_file`
Inspect the file named `school` using `if` and `else` statements:

- Print whether the file **exists** or **does not exist**
- If it exists:
  - Print whether it is **empty** or **not empty**
  - Print if it is a **regular file**

---

### `10-fizzbuzz`
Print numbers from **1 to 100**:

- **FizzBuzz** → if divisible by both 3 and 5  
- **Fizz** → if divisible by 3  
- **Buzz** → if divisible by 5  
- Else → print the number

