# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
with open('story.txt', 'r') as file:
    count = 0 
    for line in file:
        if not line.lstrip().startswith('T'):
            count += 1  
print("Number of lines not starting with 'T':", count)
```

## Output
<img width="1832" height="210" alt="528597815-61c090f5-2197-495a-aeba-891cc48bbf23" src="https://github.com/user-attachments/assets/87c330ee-7508-4e6a-882e-fce96aab80ad" />

## Result
Thus To write a Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T'is executed successfully.
