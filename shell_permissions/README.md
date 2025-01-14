# Shell Permissions Project

## Project Overview

In this project, you will learn how to work with Linux file permissions, user management, and system commands. You will write scripts that modify file permissions, switch users, and run commands with elevated privileges.

## Learning Objectives

At the end of this project, you will be able to:

- Understand and use Linux file permissions.
- Change file ownership and permissions using commands like `chmod`, `chown`, `chgrp`.
- Switch users and become a superuser using `su`, `sudo`.
- Use numerical values to represent file permissions.
- Use basic Linux commands to manage files and users.

## Requirements

- **Script Format**: Each script should have exactly two lines (including the shebang `#!/bin/bash`).
- **Script Permissions**: All your scripts must be executable.
- **Text Editors**: Allowed editors are `vi`, `vim`, and `emacs`.
- **Disallowed Commands**: You are not allowed to use backticks, `&&`, `||`, or `;` in the scripts.
- **Testing**: The scripts will be tested on Ubuntu 20.04 LTS.

## Scripts

### 1. **Switch to User Betty**: `0-iam_betty`
This script switches the current user to `betty` using the `su` command.

```bash
#!/bin/bash
su betty
