# Hello, world!

Your first Python program. It displays a greeting in the terminal.

## The code

```python
# This displays a greeting in your terminal.
print("Hello, world!")
```

- A line starting with `#` is a comment: a note for people reading the code. Python ignores it.
- `print(...)` displays something in the terminal.
- `"Hello, world!"` is a string, which means text inside quotation marks.
- `.py` tells you the file contains Python code.

## Run it on your computer

1. Install Python 3 from https://www.python.org/downloads/ if you do not have it yet. On Windows, enable the option to add Python to PATH if offered.
2. On this repository page, select **Code > Download ZIP**, then extract the ZIP file.
3. Open a terminal in the extracted folder. A terminal is an app where you type commands: PowerShell on Windows, or Terminal on macOS/Linux.
4. Run one of these commands:

Windows:

```powershell
py hello.py
```

macOS or Linux:

```sh
python3 hello.py
```

You should see:

```text
Hello, world!
```

If `py` is unavailable on Windows, try `python hello.py`.

## Try a change

Open `hello.py` in a text editor, replace `Hello, world!` with your own greeting, save the file, and run it again.

## How GitHub fits in

- A **repository** is your project folder on GitHub.
- A **commit** is a saved change in the project history. Select the repository commits link to see how these files were added.
- GitHub stores and shares the code. Viewing `hello.py` on GitHub does not run it; Python runs it on your computer when you enter the command above.

This program needs Python 3 and no extra packages.
