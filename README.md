# Python Windows Buffer Ovenflow Bad Character Finder

I originally created this script for the OSCP exam, and this helped me during my first exam.

## Usage Example

<img width="1352" alt="sample" src="https://user-images.githubusercontent.com/34600708/185750337-1a14a5ac-6bd0-402b-a1cd-02fb6f3adb04.png">

The script takes a set of good characters as an argument like below.

```bash
python3 find_bad_characters.py {good_characters} 
```

You need to extract good characters from Immunity Debugger or other debug tools.

Use the output into your python script.
