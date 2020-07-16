### remove_extensions_from_files/

```bash
# Rename all files removing the extension from them in the current directory recursively.
(0)> find . -type f | rename 's/\.\w*$//'
```
