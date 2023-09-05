this firt line in new te
## find_empty.sh

This script finds and lists all empty files and directories in the current directory and its subdirectories. It adheres to the following requirements:

- The script uses `find` to search for empty files and directories.
- It uses `-exec` to execute the `basename` command on each result to extract only the names without paths.
- The script combines the results for empty files and directories and prints them.
- It is executable and adheres to the specified constraints.

