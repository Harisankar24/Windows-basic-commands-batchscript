# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT

<img width="1043" height="457" alt="image" src="https://github.com/user-attachments/assets/dfa8c75d-6527-484d-90c7-3205265ff1b0" />


## COMMAND AND OUTPUT


Create the file Rose.txt
<img width="1040" height="441" alt="image" src="https://github.com/user-attachments/assets/c16c02b1-094b-446e-8027-0c7518fe760d" />


## COMMAND AND OUTPUT

<img width="1040" height="133" alt="image" src="https://github.com/user-attachments/assets/1314f04c-0373-4f9c-9053-66f945ccb568" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="1035" height="172" alt="image" src="https://github.com/user-attachments/assets/dd36a001-d4b6-4f35-a1c8-6ae6c7e05a3b" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="758" height="990" alt="image" src="https://github.com/user-attachments/assets/052f6421-0751-4c17-95f4-c900a44ecf39" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="983" height="278" alt="image" src="https://github.com/user-attachments/assets/86d73c27-5fab-414e-b6a5-3ec4a196b5be" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="692" height="886" alt="image" src="https://github.com/user-attachments/assets/fa8d7f13-8fa9-4f11-92cc-e7b5dfd96843" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="582" height="76" alt="image" src="https://github.com/user-attachments/assets/12a32314-94d4-4fa6-8e5f-d1448755687e" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="587" height="212" alt="image" src="https://github.com/user-attachments/assets/84a33141-5ee5-4369-9b42-222e5a03a680" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="610" height="180" alt="image" src="https://github.com/user-attachments/assets/1acde753-3a98-4ccd-8c8c-015ff60daabc" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="582" height="93" alt="image" src="https://github.com/user-attachments/assets/f5e35849-e439-47f1-ac7c-ca8ab3441da6" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="629" height="372" alt="image" src="https://github.com/user-attachments/assets/98cee996-ba29-4321-aaf9-cfd807f18319" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

![Uploading image.png…]()


# RESULT:
The commands/batch files are executed successfully.

