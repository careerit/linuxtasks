## Taks-1 

### Difficulty: Medium

List all the steps you perform in a notepad or Notepadd++

- Copy the below script and save it as a file named `taskscript1` on your vim editor
```
#!/bin/bash

echo "This script creates multiple directories and file"

echo "Create 3 directories called test1, test2, test3"

mkdir test{1..3}

cd ./test1

touch java{1..5..2}
 
cd ..

cd ./test2

touch python{1..5..2}
touch java{5..10..3}

cd ./test3

touch go{1..5..2}
touch python{6..10..2}

```


- Now make this file executable using `chmod` command
- run the script file : `./taskscript1`
- Check if three directories are created under the current directory with the names test1, test2, test3
- Now use `find` command to find all the Pyhton files in all the three directories
