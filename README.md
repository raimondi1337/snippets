# Useful snippets I've come accross/up with

### Python
```python
# Efficiently check if a list contains any values from another list
def a_contains_any_b(a, b):
    return next((True for item in a if item in b), False)
```
```python
# Deep object to dict
def deep_dict:
    return json.dumps(note, default=lambda o: getattr(o, '__dict__', str(o)))
```

### Bash

```bash
# Watch a log file, truncate lines to terminal width
tail -f error.log | cut -c-$(tput cols)
```
