# commands-i-usually-forgot


1. to find the files 

```bash
# By extension
find . -type f -name "*.pdf"
```

```bash
# Multiple extensions
find . -type f \( -name "*.pdf" -o -name "*.docx" \)


```


- `.` — current directory
- `~` — home directory
- `/` — root directory
- `-iname` — case-insensitive search
- `>` — save output to a file
