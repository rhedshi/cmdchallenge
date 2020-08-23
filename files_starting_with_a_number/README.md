### files_starting_with_a_number/

```bash
# There are a mix of files in this directory that start with letters and numbers. Print the filenames (just the filenames) of all files that start with a number recursively in the current directory.
(0)> find . -type f -name '[0-9]*' -printf '%f\n'
```
