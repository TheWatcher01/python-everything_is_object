# Python - Everything is Object

## Description 🎯

This project is a deep dive into Python's object model, exploring how Python handles different types of objects. It focuses on understanding the distinction between immutable and mutable objects, object identifiers, aliases, and variable references.

## Learning Objectives 🎓

By the end of this project, you should be able to explain:

- What is an object
- The difference between a class and an object/instance
- The difference between immutable and mutable objects
- What is a reference
- What is an assignment
- What is an alias
- How to identify if two variables are identical
- How to identify if two variables are linked to the same object
- How to display variable identifiers
- How Python passes variables to functions

## Requirements 📋

### Python Scripts

- All files interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.8.5)
- All files should end with a new line
- First line of all files should be exactly `#!/usr/bin/python3`
- Code should use `pycodestyle` (version 2.7.*)
- All files must be executable

### `.txt` Answer Files

- Only one line
- No Shebang
- All files should end with a new line

## Files 📁

### Mandatory Tasks

- `0-answer.txt` through `28-answer.txt`: Various questions about Python objects
- `19-copy_list.py`: Function that returns a copy of a list

### Advanced Tasks

- `100-magic_string.py`: Function that returns a string "BestSchool" n times
- `101-locked_class.py`: Class with no attributes that prevents dynamic creation
- `103-line1.txt` & `103-line2.txt`: Int object creation questions
- `104-line1.txt` through `104-line5.txt`: More int object questions
- `105-line1.txt`: Memory management questions
- `106-line1.txt` through `106-line5.txt`: String object questions

## Resources 📚

- [9.10. Objects and values](https://www.openbookproject.net/thinkcs/python/english2e/ch09.html#objects-and-values)
- [9.11. Aliasing](https://www.openbookproject.net/thinkcs/python/english2e/ch09.html#aliasing)
- [Immutable vs mutable types](https://stackoverflow.com/questions/8056130/immutable-vs-mutable-types)
- [Mutation](https://www.composingprograms.com/pages/24-mutable-data.html#sequence-objects)
- [Python tuples: immutable but potentially changing](https://www.oreilly.com/radar/)

## Project Setup 🛠️

### Quick Setup

You can quickly create all the necessary files and directories using this command:

```bash
mkdir -p holbertonschool-higher_level_programming/python-everything_is_object && \
cd holbertonschool-higher_level_programming/python-everything_is_object && \
touch README.md && \
touch 0-answer.txt 1-answer.txt 2-answer.txt 3-answer.txt 4-answer.txt \
      5-answer.txt 6-answer.txt 7-answer.txt 8-answer.txt 9-answer.txt \
      10-answer.txt 11-answer.txt 12-answer.txt 13-answer.txt 14-answer.txt \
      15-answer.txt 16-answer.txt 17-answer.txt 18-answer.txt 19-copy_list.py \
      20-answer.txt 21-answer.txt 22-answer.txt 23-answer.txt 24-answer.txt \
      25-answer.txt 26-answer.txt 27-answer.txt 28-answer.txt && \
touch 100-magic_string.py 101-locked_class.py \
      103-line1.txt 103-line2.txt \
      104-line1.txt 104-line2.txt 104-line3.txt 104-line4.txt 104-line5.txt \
      105-line1.txt \
      106-line1.txt 106-line2.txt 106-line3.txt 106-line4.txt 106-line5.txt && \
echo '#!/usr/bin/python3' > 19-copy_list.py && \
echo '#!/usr/bin/python3' > 100-magic_string.py && \
echo '#!/usr/bin/python3' > 101-locked_class.py && \
chmod +x *.py
```

### What This Command Does 📋

1. Creates the project directory structure
2. Creates mandatory task files (0-28 answer files)
3. Creates Python files for mandatory tasks
4. Adds the shebang (`#!/usr/bin/python3`) to Python files
5. Makes the Python files executable

### File Structure After Setup 📂

```bash
python-everything_is_object/
├── README.md
├── 0-answer.txt through 28-answer.txt
├── 19-copy_list.py
├── 100-magic_string.py
├── 101-locked_class.py
├── 103-line1.txt, 103-line2.txt
├── 104-line1.txt through 104-line5.txt
├── 105-line1.txt
└── 106-line1.txt through 106-line5.txt
```

### After Setup Checklist ✅

- Verify all files are created
- Confirm Python files are executable:

  ```bash
  ls -l *.py
  ```

## Author ✍️

TheWatcher01

## Acknowledgments 🙏

Project provided by [Holberton School](https://www.holbertonschool.fr/)
