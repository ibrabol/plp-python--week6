# Safe Tools - Python Week 6

## Files

* `safe_tools.py` - Contains three safe functions that handle common Python errors using `try` and `except`.
* `README.md` - Explains the assignment and the purpose of the files.

## Why can't an `if` check catch `abc` on its own?

An `if` check can test a condition, but `"abc"` causes an error when Python tries to convert it to an integer with `int()`. The `ValueError` happens during the conversion, so `try` and `except` are needed to catch the error and keep the program running.
