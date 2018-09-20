# Useful snippets I've come accross/up with

### Python
```python
def fast_a_contains_any_b(list_a, list_b):
    return next((True for item in list_a if item in list_b), False)
```

### Bash
Watch a log file, but limited to terminal width
```bash
tail -f error.log | cut -c-$(tput cols)
```
