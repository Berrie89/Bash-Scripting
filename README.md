# Bash-Scripting
Bash script is a sequence of commands or instructions that are executed by the shell program line by line. Bash scripting allows you to automate repititive tasks and processes.
## Objective
The objective of this project is to create a bash script that generates a multiplication table for a number entered by the user. For this project I used loops, user input and conditional logic. 
## Project Description
I wrote a bash script that will prompt a user to enter a number and ask if they want the full multiplication table from 1 to 10 or a partial table within a specified range. If they choose partial, they will be prompted to enter the start and end number. Based on the user's response, the script will display the corresponding multiplication table.
## Project Implementation
User input number: I used the echo keyword to prompt the user to enter a number, then the read command to assign a variable to the information provided by the user.
Conditional logic: I used the if-else statement to ask if the user wants a full or partial table. 
Use of Loop: I used both the C-style and list style for loop to implement the logic to generate the multiplication table. Find screenshot below:
![full table](https://github.com/user-attachments/assets/018661c2-a1bb-4c00-ba54-679d7d5a540d)

![partial table](https://github.com/user-attachments/assets/203cadcb-167c-4ab1-88cf-a87231d560c8)

Input Validation: I ensured the users enter valid numbers for the multiplication table and the specified range. If incorrect range is entered the user receives an error message and default to a full multiplication table. Find screenshot below:

![error message](https://github.com/user-attachments/assets/1e3519c6-bcfc-4a56-a5c3-fcac80f00409)

## Bash Script
C-Style for loop.

![Screenshot 2024-11-22 193256](https://github.com/user-attachments/assets/edf0e403-740e-4527-8204-ea5bbbf397fd)

List-Style for loop.

![Screenshot 2024-11-22 203010](https://github.com/user-attachments/assets/467d9852-34a1-4caf-b9df-f9d378b44c6c)


