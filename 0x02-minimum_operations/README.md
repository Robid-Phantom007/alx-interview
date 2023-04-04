# 0x02. Minimum Operations
For this interview practice algorithm, there is a text file with a single character. The text editor can only execute two operations: Copy All and Paste.

## Requirements :page_with_curl:
* Allowed editors: vi, vim, emacs
* All your files will be interpreted/compiled on Ubuntu 14.04 LTS using python3 (version 3.4.3)
* All your files should end with a new line
* The first line of all your files should be exactly #!/usr/bin/python3
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should be documented
* Your code should use the PEP 8 style (version 1.7.x)
* All your files must be executable

## Task :heavy_check_mark:
[0. Minimum Operations](/0x03-minimum_operations/0-minoperations.py)
* Given a number `n`, write a method that calculates the fewest number of operation needed to result in exactly `n` characters in the file.
  * Example: `n` = 9
    * C => Copy All => Paste => CC => Paste => CCC => Copy All => Paste => CCCCCC => Paste => CCCCCCCCC
    * Number of operations = 6
  * `n` is the number of times the character should be repeated.
  * returns the fewest number of operations needed or 0 if n is impossible
