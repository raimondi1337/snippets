# snippets
Useful snippets I've come up with

### Python

def fast_a_contains_any_b(list_a, list_b):
    return next((True for item in list_a if item in list_b), False)
