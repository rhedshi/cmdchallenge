### print_nth_line/

```bash
# Print the 25th line of the file faces.txt.
(0)> head -n 25 faces.txt | tail -n 1
```

```bash
# Print the 25th line of the file faces.txt.
(0)> sed -n '25 p' faces.txt
```
