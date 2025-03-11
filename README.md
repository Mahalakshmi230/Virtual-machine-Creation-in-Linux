 # VIRTUAL MACHINE CREATION IN LINUX
## AIM
To Install Virtualbox / VMware Workstation with different flavours of linux.
## PROBLEM STATEMENT 
Manually executing basic Linux tasks like file management, navigation, and arithmetic operations can be inefficient. This experiment aims to automate these tasks using Bash scripting, including:

1. Displaying the current directory, files, and system date.
2. Reading and displaying file contents.
3. Performing basic arithmetic operations.

## ALGORITHM
 ### Steps 1:
 Open the terminal in Kali Linux.
 ### Steps 2: 
 Use basic Linux commands to navigate and manage files.
 ### Steps 3:
 Create a Bash script using Mousepad.
 ### Steps 4:
 Write a script that performs arithmetic operations and reads a file.
 ### Steps 5:
 Make the script executable.
 ### Step 6:
 Run the script and observe the output.
## COMMANDS
# Execute Basic Linux Commands in the Terminal
# Check the Current Working Directory
pwd

# Create a New Directory
mkdir my_experiment

# Navigate into the Directory
cd my_experiment

# List the Files in the Directory
ls

# Write Some Text into the File
echo "Hello, this is a test file." > myfile.txt

# Read the File Contents
cat myfile.txt

# Get the Current Date and Time
date

# Writing a Bash Script in Mousepad
Open Mousepad
mousepad myscript.sh &

# Write the Bash Script

#!/bin/bash 

echo "Current Directory:"
pwd

echo "Files in this directory:"
ls

echo "Current Date and Time:"
date

read -p "Enter first number: " num1

read -p "Enter second number: " num2

sum=$((num1 + num2))

diff=$((num1 - num2))

prod=$((num1 * num2))

quot=$((num1 / num2))

rem=$((num1 % num2))

echo "Sum: $sum"

echo "Difference: $diff"

echo "Product: $prod"

echo "Quotient: $quot"

echo "Remainder: $rem"


# Make the Script Executable
chmod +x myscript.sh

# Run the Script
./myscript.sh

## OUTPUT

### REG NUMBER: 212223230116
### NAME: Mahalakshmi R

 ![419296131-c8cefd3c-b7b5-48fa-a2f6-85db776cf094](https://github.com/user-attachments/assets/7ba1ffe9-c6c4-4f5c-b812-bbf9509c43c0)

![421258284-cc481926-bcfc-4901-b74d-7f5c76beabd5](https://github.com/user-attachments/assets/69728a6d-76da-420c-a1df-522a868a81e7)

![421258755-ddc08a53-e155-4a5c-afa4-d4a9429696d3](https://github.com/user-attachments/assets/8552a4dd-2054-48a2-ab11-95d674b608ca)

![417051518-bdb5a52e-f093-4767-9cb1-0c4ffc8fe11f](https://github.com/user-attachments/assets/04f0146e-08cd-435d-aedb-799ce0c169d1)

## RESULT
Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.
  


