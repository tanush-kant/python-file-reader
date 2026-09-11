# python-file-reader
A simple Python script demonstrating how to open and read text files in read-only mode.

# This code works by this demonstration example:
The script uses a `with open()` statement wrapped inside a `try-except` block. This ensures that if the file doesn't exist, the program prints a clean error message instead of crashing.

```python
try:
    with open("example", "r") as f: # Your file will come here in that example place just replace it with your file name with its format and your good to go
        print(f.read())
except Exception as e:
    print(e)
```

# Tutorial to run this code ( if you are a beginner )
1. Create a text file named `Hello` (without any extension) or change `"Hello"` in the code to your file's name (e.g., `"Hello.txt"`).
2. Place the text file in the same folder as your Python script.
3. Run the script using your terminal or IDE:
   ```bash
   python main.py
   ```

---

Author : Tanush Kant

---
