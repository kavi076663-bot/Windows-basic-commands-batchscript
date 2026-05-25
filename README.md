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
<img width="401" height="173" alt="image" src="https://github.com/user-attachments/assets/ade781bc-c276-4605-a6ed-cc8d79f00d48" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="522" height="149" alt="image" src="https://github.com/user-attachments/assets/301b0d23-1f24-4e9b-946d-cca46d3a6c62" />

Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="764" height="414" alt="image" src="https://github.com/user-attachments/assets/842a9e6d-2792-4910-b10e-c7a0ac036bd0" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="681" height="168" alt="image" src="https://github.com/user-attachments/assets/e2f2f57c-b752-4be1-97ce-3b4f80392215" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="546" height="149" alt="image" src="https://github.com/user-attachments/assets/b0a06719-b786-44e9-a707-689f5574e028" />

Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="361" height="57" alt="image" src="https://github.com/user-attachments/assets/124554a5-5d14-44a9-a294-b83b0644f386" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="548" height="170" alt="image" src="https://github.com/user-attachments/assets/e1bffeb6-0920-427c-8b6e-5a009c075d34" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="380" height="669" alt="image" src="https://github.com/user-attachments/assets/e843157e-9f1d-42b2-9274-65f6f45abbba" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="579" height="183" alt="image" src="https://github.com/user-attachments/assets/57e7e60f-c016-40b6-9205-4c97a80cb898" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="490" height="207" alt="image" src="https://github.com/user-attachments/assets/5d6b53eb-5296-4702-9fde-bfde1ba1ec53" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="558" height="170" alt="image" src="https://github.com/user-attachments/assets/597d69a0-ebab-4579-b74a-e97c0ad3354b" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="456" height="212" alt="image" src="https://github.com/user-attachments/assets/c81b0822-79b0-466d-b47f-3e6032d603fe" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="450" height="166" alt="image" src="https://github.com/user-attachments/assets/4b980b76-b85e-4c84-bf44-a4edb195470c" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="308" height="385" alt="image" src="https://github.com/user-attachments/assets/366532f0-34f5-4947-9f0f-1ba3ee861755" />


# RESULT:
The commands/batch files are executed successfully.

