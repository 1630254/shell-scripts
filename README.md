This repository contains a curated collection of shell scripting examples—ranging from practice exercises to production‑ready utilities. These scripts are designed to support system administrators and DevOps professionals in their day‑to‑day operations, helping automate routine tasks, streamline workflows, and significantly reduce manual effort.


# Shell Script Collection

- **`variables.sh`** – Demonstrates the fundamentals of **variable declaration and usage** in shell scripting.  
- **`greet.sh`** – Captures **user input** interactively using the `read` command.  
- **`check_number.sh`** – Implements **numeric comparison operators** (`-gt`, `-lt`, `-eq`) for conditional checks.  
- **`file_check.sh`** – Performs **file existence testing** to validate presence or absence of files.  
- **`server-check.sh`** – Accepts a **service name** from the user and checks its **status**.  
- **`for_loop.sh`** – Illustrates the **for loop** with a predefined list of values.  
- **`count.sh`** – Uses **brace expansion** within a **for loop** to generate numeric sequences.  
- **`countdown.sh`** – Implements a **while loop** to perform countdown operations.  
- **`args_demo.sh`** – Demonstrates handling of **command‑line arguments** in scripts.  
- **`safe_script.sh`** – Showcases **error handling techniques** for safer script execution.  
- **`install_packages.sh`** – Tests for package presence and installs if missing; enforces **root privileges** for execution.  
- **`function.sh`** – Implements reusable **functions** within shell scripts.  
- **`disk_check.sh`** – Monitors **root (/) partition space** using `awk` and function return values.  
- **`strict_demo.sh`** – Explores variations of the built‑in `set` command for **strict error handling**.  
- **`local_demo.sh`** – Demonstrates the difference between **local and global variables** in functions.  
- **`system_info.sh`** – Retrieves **system information** including hostname, OS details, uptime, top disk usage, memory usage, and top CPU‑consuming processes.  
- **`log_rotate.sh`** – A **production‑grade script** that automates log maintenance: compresses files older than 7 days, deletes archives older than 30 days, reports actions performed, and validates directory existence.  
- **`backup.sh`** – A **production‑grade backup script** that creates timestamped archives, verifies success, reports details, prunes files older than 14 days, and handles errors gracefully.  
- **`maintenance.sh`** – A **production‑grade orchestration script** that runs log rotation and backup functions, logging all output with timestamps to `/var/log/maintenance.log`.  
- **`log_analyzer.sh`** – A **production‑grade log analysis script** that validates input, counts errors, highlights critical events, ranks top error messages, generates a dated summary report, and optionally archives processed logs to streamline monitoring.  