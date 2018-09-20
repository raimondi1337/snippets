# Useful snippets I've come accross/up with

### Python
Efficiently check if a list contains any values from another list
```python
def a_contains_any_b(a, b):
    return next((True for item in a if item in b), False)
```

### Bash
Watch a log file, but limited to terminal width
```bash
tail -f error.log | cut -c-$(tput cols)
```
