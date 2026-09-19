\# Week 7 Assignment — Shopping List Manager



This assignment practices Python lists, indexing, adding and removing items, membership checking, loops, and list comparisons.



\## Files



\- `list\_warmup.py` — Demonstrates creating a list, accessing items by index, using `append()`, using `remove()`, and counting items with `len()`.

\- `shopping\_list.py` — Provides an interactive shopping list manager for adding, removing, showing, and finishing a shopping list.

\- `list\_report.py` — Prints a numbered shopping list, counts item names with more than four letters, and finds the longest item name using a loop.

\- `screenshots/` — Contains screenshots showing the output of each Python program.



\## Why check `in` before using `.remove()`?



Checking `in` before calling `.remove()` is safer because `.remove()` causes an error if the item is not in the list. Using `in` first allows the program to handle a missing item gracefully instead of crashing. This makes the shopping list manager more reliable and user-friendly.

