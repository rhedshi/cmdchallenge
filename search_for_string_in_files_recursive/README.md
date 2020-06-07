### search_for_string_in_files_recursive/

```bash
# Print all matching lines (without the filename or the file path) in all files under the current directory that start with "access.log" that contain the string "500".
(0)> grep -hr "500" --include access.log*
```
