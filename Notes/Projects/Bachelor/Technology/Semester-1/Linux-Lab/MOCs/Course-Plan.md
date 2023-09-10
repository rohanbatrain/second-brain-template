## Lab2 (Practice some basic commands on Linux)
---

i. Basic Navigation Commands: Teach essential commands for navigating the file system, such as:

* ls (list): Display the contents of a directory.
* cd (change directory): Move between directories.
* pwd (print working directory): Show the current directory.
* mkdir (make directory): Create new directories.
* rmdir (remove directory): Remove empty directories.

ii. File Operations: Introduce fundamental file operations using the following commands:

* touch: Create new files.
* cp (copy): Copy files and directories.
* mv (move): Move or rename files and directories.
* rm (remove): Delete files and directories.

iii. File Viewing and Editing: Introduce commands for viewing and editing files, such as:

* cat: Display file contents.
* less or more: View files with pagination.
* head and tail: Show the beginning or end of a file.
* nano or vim: Basic text editors.

iv. User Management: Discuss commands for user management tasks, including:

* whoami: Display the current user.
* who: Show users currently logged in.
* passwd: Change the password for the current user.
* sudo (superuser do): Execute commands with administrative privileges.

v. System Information: Introduce commands for gathering system information, such as:
* uname: Display system information.
* df (disk free): Show disk space usage.
* top or htop: Monitor system processes.
* history: View command history.


## Lab3 (Files and Directories commands 1)
---

i. Working with Files:
* touch: Create an empty file or update the access/modify timestamps of an existingfile.
* cp: Copy files and directories.
* mv: Move or rename files and directories.
* rm: Remove files and directories.
* cat: Concatenate and display the contents of a file.
* less: Display the contents of a file one page at a time.
* head: Display the first few lines of a file.
* tail: Display the last few lines of a file.

ii. File Permissions and Ownership:

* Explain the ls -l command to display detailed file information, including
permissions and ownership.
* Discuss the three sets of permissions: owner, group, and others.
* Explain the chmod command to modify file permissions.
* Discuss the chown and chgrp commands to change file ownership and group.


iii. Advanced File and Directory Operations:

* find: Search for files and directories based on various criteria.
* grep: Search for specific patterns within files.
* tar: Archive files and directories into a single file.
* gzip/gunzip: Compress and decompress files.
* ln: Create hard and symbolic links.

## Lab 4: Shell Programing
---
i. Write a simple shell script that prints "Hello, World!" when executed.
ii. Create a script that prompts the user to enter their name and then displays a personalized greeting.
iii. Write a script that takes two numbers as input and performs various arithmetic operations like addition, subtraction, multiplication, and division.
iv. Create a script that asks the user to enter their age and displays a message based on whether they are eligible to vote or not.

## Lab 5: Shell Programming
---
i. Write a script that takes a number as input and checks whether it is a prime number or not.
ii. Write a script that calculates the sum of the digits of a given number.
iii. Create a script that checks whether a given number is an Armstrong number or not.

## Lab 6: Shell Programming
---
i. Write a script that checks whether a given number is a palindrome or not. A palindrome number reads the same backward as forward.
ii. Write a script that calculates the greatest common divisor (GCD) and the least common multiple (LCM) of two given numbers.
iii. Create a script that takes multiple numbers as input and sorts them in ascending or descending order.

## Lab 7: Shell Programming
---
i. Write a script that takes a filename as input and checks if it exists. If the file exists, display its content; otherwise, prompt the user to create the file.
ii. Create a script that prints the numbers from 1 to 10 using a loop.
iii. Write a script that takes a filename as a command line argument and counts the number of lines, words, and characters in that file.
iv. Create a script that defines a function to calculate the factorial of a given number and call that function with different inputs.

## Lab 8: Shell Programming
---
i. Write a script that checks the file permissions of a given file and displays whether it is readable, writable, or executable by the current user.
ii. Create a script that prompts the user to enter a string and then performs operations like string length, string concatenation, and string comparison.
iii. Write a script that searches for a specific pattern in a given file and displays the matching lines.
iv. Create a script that displays various system information like the current date and time, logged-in users, system uptime, etc.

## Lab 9: Shell Programming
---
i. Write a script that renames all files in a directory by adding a prefix or suffix to the filenames.
ii. Create a script that searches for files in a specified directory and its subdirectories, based on certain criteria like file extension or file size.
iii. Write a script that generates the Fibonacci series up to a given number, using loops or recursive functions.

## Lab 10: Shell Programming
---
i. Write a script that takes a string as input and calculates its length.
ii. Create a script that takes a string as input and prints its reverse.
iii. Write a script that prompts the user to enter two strings and concatenates them together.

## Lab11: Shell Programming
---
i. Write a script that takes a sentence as input and splits it into individual words.
ii. Create a script that checks whether a given string is a palindrome or not.

## Lab12: Building a Rule-Based Expert System using Shell Scripting
---

Objective: The objective of this lab exercise is to build a simple rule-based expert system using shell scripting. The expert system will provide recommendations based on a set of predefined rules.

Instructions:
1. Create a shell script named "expert_system.sh".
2. Implement a set of rules using conditional statements (if-elif-else) within the script.
3.  Each rule should check for specific conditions and provide a corresponding recommendation.

#### Example rules
---
	 * If the user is experiencing fever, recommend taking a fever reducer medication.
	 * If the user has a sore throat, recommend gargling with warm saltwater.
	 * If the user has a cough and congestion, recommend drinking warm fluids and taking cough syrup.
	 * Feel free to add more rules based on your desired expert system topic.

####  Instructions
---
	* Prompt the user to input their symptoms.
	* Based on the user's input, evaluate the rules one by one and display the appropriate recommendation(s) for the symptoms identified.
	* If none of the rules match the user's symptoms, provide a general recommendation or message.
	* Test the expert system by running the script and providing different sets of symptoms to observe the recommendations.
	* Modify the rules or add new rules as needed to refine the expert system's behavior.
	* Document the logic and rules implemented in the script, along with any modifications or additions made.
	* Write a summary report discussing the challenges faced, observations made, and improvements that can be made to enhance the expert system's functionality.