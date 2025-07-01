# Shell Permissions Scripts

This repository contains a series of shell scripts designed to manipulate file and directory permissions, as well as user/group ownership. Each script corresponds to a specific task, including changing user permissions, file ownership, and more.

## Tasks

### 0. **My Name Is Betty**

- **Description**: This script switches the current user to the user `betty`.
- **Usage**:

    ```bash
    ./0-iam_betty
    ```

### 1. **Who Am I**

- **Description**: This script prints the effective username of the current user.
- **Usage**:

    ```bash
    ./1-who_am_i
    ```

### 2. **Groups**

- **Description**: This script prints all the groups the current user is part of.
- **Usage**:

    ```bash
    ./2-groups
    ```

### 3. **New Owner**

- **Description**: This script changes the owner of the file `hello` to the user `betty`.
- **Usage**:

    ```bash
    ./3-new_owner
    ```

### 4. **Empty!**

- **Description**: This script creates an empty file called `hello`.
- **Usage**:

    ```bash
    ./4-empty
    ```

### 5. **Execute**

- **Description**: This script adds execute permission to the owner of the file `hello`.
- **Usage**:

    ```bash
    ./5-execute
    ```

### 6. **James Bond**

- **Description**: This script sets the permissions for the file `hello` such that:
  - Owner: no permissions
  - Group: no permissions
  - Others: all permissions
- **Usage**:

    ```bash
    ./6-James_Bond
    ```

### 7. **John Doe**

- **Description**: This script sets the mode of the file `hello` to `rwxr-x-wx` (Owner: `rwx`, Group: `r-x`, Others: `wx`).
- **Usage**:

    ```bash
    ./7-John_Doe
    ```

### 8. **Directories**

- **Description**: This script adds execute permissions to all subdirectories of the current directory for the owner, group, and all other users.
- **Usage**:

    ```bash
    ./8-directories_permissions
    ```

### 9. **More Directories**

- **Description**: This script creates a directory called `my_dir` with permissions `751`.
- **Usage**:

    ```bash
    ./9-directory_permissions
    ```

### 10. **Change Group**

- **Description**: This script changes the group owner of the file `hello` to `school`.
- **Usage**:

    ```bash
    ./10-change_group
    ```

## Requirements

- A Unix-based system (Linux or macOS) with the ability to run shell scripts.
- The user `betty` should exist on the system for the first script.

## License

This project is open-source and available under the [MIT License](LICENSE).
