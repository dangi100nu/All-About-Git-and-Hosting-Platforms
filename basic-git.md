## Best Practices for Branching and Commit Messages

### Branching Best Practices
1. **Common Branch Types:**
   - `feature/`: For new features.
   - `bugfix/`: For fixing bugs.
   - `hotfix/`: For critical fixes in production.
   - `release/`: For release preparation.
   - `chore/`: For maintenance tasks.

2. **Examples:**
   - `feature/add-login-page-123`
   - `bugfix/456-fix-header-alignment`
   - `hotfix/resolve-deployment-error-789`

---

### Commit Message Best Practices
1. **Common Commit Prefixes:**
   - `feat`: New feature.
   - `fix`: Bug fix.
   - `docs`: Documentation changes.
   - `style`: Code formatting (no logic changes).
   - `refactor`: Code refactoring.
   - `test`: Adding or updating tests.
   - `chore`: Maintenance tasks (e.g., dependency updates).

2. **Examples:**
   - `fix: resolve error (#2345)`
   - `feat: add dark mode (ODI-234)`


## Differences Between Git Bash, CMD, and PowerShell

- **Git Bash**:  
 it is an application that provides a commond-line interface for git operations on windows.basically it is A Unix-like command-line interface for Windows, designed specifically to work with Git and provide Unix commands like `ls`, `cd`, and `cat`.

- **CMD (Command Prompt)**:
  It is a default cli tool for windows.  
  A basic command-line interpreter built into Windows, used for running native DOS and Windows commands like `dir`, `copy`, and `del`.

- **PowerShell**:  
  An advanced scripting environment and shell for Windows, designed for automation and system management, using object-oriented commands like `Get-ChildItem` and `Set-ExecutionPolicy`.


## Git Bash Commands with Flags

### File and Directory Management

#### `ls` - List files and directories
- `ls` – List files and directories.
- `ls -a` – Include hidden files.
- `ls -l` – List with detailed information (permissions, size, etc.).
- `ls -la` – Combine `-l` and `-a` to list all files with details.

#### `rm` - Remove files or directories
- `rm [file]` – Remove a file.
- `rm -f [file]` – Forcefully remove a file without prompting.
- `rm -rf [directory]` – Forcefully remove a directory and its contents.

#### `mkdir` - Create directories
- `mkdir [directory_name]` – Create a new directory.
- `mkdir -p [path/to/directory]` – Create nested directories.

#### `pwd` - Print working directory
- `pwd` – Print working directory..

#### `touch` - Create files
- `touch [file_name]` – Create an empty file.

#### `cat` - Display file contents
- `cat [file_name]` – Print file contents.

### System Commands

#### `clear` - Clear terminal screen
- `clear` – Clear terminal output.

#### `exit` - Close Git Bash
- `exit` – Close the terminal session.


## Command Prompt Commands with Flags

### File and Directory Management

#### `dir` - List files and directories
- `dir` – List files and directories.
- `dir /a` – Include hidden files.

#### `del` - Delete files
- `del [file]` – Delete a file.
now we also use rm instead of that.

#### `mkdir` - Create directories
- `mkdir [directory_name]` – Create a new directory.

#### `echo` - Create files
- `echo. > [file_name]` – Create an empty file..

#### `type` - Display file contents
- `type [file_name]` – Print file contents.

#### `cd` - Print working directory
- `cd` – Print working directory.

### System Commands

#### `cls` - Clear terminal screen
- `cls` – Clear terminal output.

#### `exit` - Close Command Prompt
- `exit` – Close the terminal session.
