Command Chosen: `grep`

Source: `man grep` in java and this [link](https://www.geeksforgeeks.org/grep-command-in-unixlinux/)

Example 1: `-l`

1.1 - `./technical/911report`
![image](https://github.com/DirectJava/cs15l-Lab3/assets/122843554/be5361f8-f4b3-41f1-bb4f-895992978d29)

This command line chooses the text file name within `911report` that has the keyword `<character or word>` that's been typed in.

1.2 - `./technical/biomed`
![image](https://github.com/DirectJava/cs15l-Lab3/assets/122843554/25085be4-630b-4dbd-b5b6-c261f9869cb5)

This time, it searches the files that contains either the file name or any letters being inputted in the argument.

Example 2: `c` 

2.1 - `./technical/911report`
![image](https://github.com/DirectJava/cs15l-Lab3/assets/122843554/94796247-e2f4-408d-9176-e38478ccf8d0)

In `911report`, `-c` only prints how many lines that matches the word `experience` and `to`.

2.2 - `./technical/biomed`
![image](https://github.com/DirectJava/cs15l-Lab3/assets/122843554/bdc07376-4b36-4e9d-bcde-e13175604a4e)

Once again, `-c` only prints the number of lines that matches a particular string in the argument. In this case, it counts how many times the words `bio` and `medical` appears in `chapter1.txt`

Example 3: `-v`

3.1 - `./technical/911report`
![image](https://github.com/DirectJava/cs15l-Lab3/assets/122843554/105f3084-e2f7-45da-a0e5-3f036fc85b03)

The `-v` command only returns lines in a file that don't have the specific word in the argument. In this scenario, `v` only select lines in `chapter1.txt` that doesn't contain the word `experience`.

3.2 - `./technical/biomed`
![image](https://github.com/DirectJava/cs15l-Lab3/assets/122843554/add6487a-f31a-4dc9-b55e-b73446d00088)

Once again, `v` returns lines that doesn't have a particular word in `biomed`, `1471-2148-2-8.txt`.


Example 4: `-o`

4.1 - `./technical/911report`
![image](https://github.com/DirectJava/cs15l-Lab3/assets/122843554/3977b273-8710-4b35-9635-9e61d3389409)

When `-o` is typed and the word `experience` is being added as an argument, java will return the word `experience` every time it sees one. 

4.2 - `./technical/biomed`
![image](https://github.com/DirectJava/cs15l-Lab3/assets/122843554/d2b1fa25-d9fc-4afe-b728-2a43cbc9a3c4)

Instead of using `911report`, I put in the word `except` while referencing to the `biomed` file. When I run the command, it prints `except` multiple times as a result from successfully finding those words in a particular biomed file.

