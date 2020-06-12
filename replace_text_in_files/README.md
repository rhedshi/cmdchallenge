### replace_text_in_files/

```bash
# This challenge has text files (with a .txt extension) that contain the phrase "challenges are difficult". Delete this phrase recursively from all text files.
(0)> sed -i '/challenges are difficult/d' **/*.txt
```

```bash
# This challenge has text files (with a .txt extension) that contain the phrase "challenges are difficult". Delete this phrase recursively from all text files.
(0)> find . -name '*.txt' -exec sed -i '/challenges are difficult/d' {} \+
```

```bash
# This challenge has text files (with a .txt extension) that contain the phrase "challenges are difficult". Delete this phrase recursively from all text files.
(0)> find . -name '*.txt' -print0 | xargs -0 sed -i '/challenges are difficult/d'
```
