# python-file-reader
A simple Python script demonstrating how to open and read text files in read-only mode.

# This code works by this demonstration example:
The script uses a `with open()` statement wrapped inside a `try` block. This ensures that if the file doesn't exist, the program prints a clean error message instead of crashing so basically if you want to make more like these you can make and if the first one crashes so, at least the 2nd one gives the result without any errors thats why that `try:` is there.

```python
try:
    with open("Hello.txt", "r") as f: # Your file will come here in that example place just replace it with your file name with its format and your good to go
        print(f.read())
except Exception as e:
    print(e)
```

# Tutorial to run this code ( if you are a beginner )
1. Create a text file named `Hello` (without any extension) or change `"Hello"` in the code to your file's name (e.g., `"Hello.txt"`).
2. Place the text file in the same folder as your Python script and yes you can cut it or just drag it there.
3. Run the script using your terminal or vs code ( which i have used ) or any other IDE :
   ```bash
   Python Main.py
   ```

---

Author : Tanush Kant

---
