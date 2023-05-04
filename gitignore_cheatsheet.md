

| Pattern | Explanation / Matches | Examples |
| ------- | --------------------- | -------- |
| *       | Matches any string of characters, except '/' | `*.txt` matches all `.txt` files in the directory |
| ?       | Matches any single character, except '/' | `file?.txt` matches `file1.txt`, `file2.txt`, etc. |
| []      | Matches any character enclosed in brackets, or a range of characters separated by '-' | `[abc].txt` matches `a.txt`, `b.txt`, or `c.txt` |
| {}      | Matches any of the comma-separated patterns enclosed in braces | `{*.jpg,*.png}` matches all `.jpg` and `.png` files in the directory |
| **      | Matches any number of directories, including none | `logs/**.txt` matches all `.txt` files in the `logs` directory and its subdirectories |
| /       | Matches only files and directories in the current directory, not in any subdirectories | `/logs/` matches only the `logs` directory in the current directory |
| /       | Matches only directories, not files | `/logs` matches only directories named `logs` in any subdirectory |
| !       | Negates the pattern, including files that match the pattern | `*.txt` ignores all `.txt` files, `!important.txt` includes `important.txt` |
| " "     | Escapes special characters or spaces in a pattern | `"file name with spaces.txt"` matches the file with spaces in its name |

