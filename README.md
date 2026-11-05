# Hello World

A small first Python program. It prints a name, a line of stars and a welcome message.

## What's in this folder

| File     | What it does                                      |
| -------- | ------------------------------------------------- |
| `app.py` | Prints three lines of text to the terminal.       |

## Requirements

- Python 3 ([download](https://www.python.org/downloads/))

On Windows, tick **"Add python.exe to PATH"** when you install. If typing `python` opens the Microsoft Store, Python isn't installed yet, or the Store shortcut is getting in the way. You can turn that shortcut off in **Settings → Apps → Advanced app settings → App execution aliases**.

Check that Python is installed:

```sh
python --version
```

## Run it

Open a terminal in this folder and run:

```sh
python app.py
```

On Windows you can also use the Python launcher:

```sh
py app.py
```

## Expected output

```
Debopam M 
**********
Welcome to the world of Python
```

## How it works

```python
print ("Debopam M ")                       # print a piece of text
print ("*" * 10)                           # repeat "*" 10 times
print ("Welcome to the world of Python")
```

- `print(...)` writes text to the screen.
- Multiplying a string by a number (`"*" * 10`) repeats it that many times.

## Ideas to try next

- Change the name to your own.
- Change `10` to a different number to make the line of stars longer or shorter.
- Ask for the user's name with `name = input("Your name: ")` and print it.
