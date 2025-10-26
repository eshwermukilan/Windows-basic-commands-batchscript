# NAME : ESHWER M
# REG NO : 212224040086
# DATE : 26-10-2025
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
<img width="654" height="301" alt="Screenshot 2025-10-26 094515" src="https://github.com/user-attachments/assets/4a091cfd-44df-42c5-bcc1-14a79a1f61fe" />

Remove the directory "my-folder"
## COMMAND AND OUTPUT
<img width="606" height="140" alt="Screenshot 2025-10-26 094559" src="https://github.com/user-attachments/assets/fdab6faf-907a-4e0f-ae77-d8d739ee1d24" />


Create the file Rose.txt
## COMMAND AND OUTPUT
<img width="654" height="371" alt="Screenshot 2025-10-26 094806" src="https://github.com/user-attachments/assets/5d76aa90-27dc-4b72-8473-fb85f92cb9bc" />

Create the file hello.txt using echo and redirection
## COMMAND AND OUTPUT
<img width="723" height="116" alt="Screenshot 2025-10-26 094906" src="https://github.com/user-attachments/assets/af64dbd3-aea0-4c55-9ed9-5f490dd6a0ff" />

Copy the file hello.txt into the file hello1.txt
## COMMAND AND OUTPUT
<img width="661" height="84" alt="Screenshot 2025-10-26 094945" src="https://github.com/user-attachments/assets/33e6b1ec-6d02-4ba1-a07f-2d3a431149ec" />

Remove the file hello1.txt
## COMMAND AND OUTPUT
<img width="563" height="202" alt="Screenshot 2025-10-26 095045" src="https://github.com/user-attachments/assets/e3362b0b-829c-4328-8b6c-bbbba5e1f831" />

List out the file hello1.txt in the current directory
## COMMAND AND OUTPUT
<img width="563" height="202" alt="Screenshot 2025-10-26 095045" src="https://github.com/user-attachments/assets/527ec275-a81b-47a6-8f2b-b2fe079a0a2e" />

List out all the associated file extensions 
## COMMAND AND OUTPUT
<img width="452" height="616" alt="Screenshot 2025-10-26 095223" src="https://github.com/user-attachments/assets/d8f63cd3-af91-4a00-a117-996437987aef" />

Compare the file hello.txt and rose.txt
## COMMAND AND OUTPUT
<img width="817" height="259" alt="Screenshot 2025-10-26 095333" src="https://github.com/user-attachments/assets/0c18ccdd-61de-4c80-8bdc-8ab8ef910281" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
## OUTPUT
<img width="572" height="154" alt="Screenshot 2025-10-26 095614" src="https://github.com/user-attachments/assets/99a8c3b4-3d1b-44bc-b83d-6b57a2f8fa9e" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.
## OUTPUT
<img width="780" height="314" alt="Screenshot 2025-10-26 095923" src="https://github.com/user-attachments/assets/d2684d4e-4069-4a45-bf2a-bb6f76af8589" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.
## OUTPUT
<img width="617" height="247" alt="Screenshot 2025-10-26 100018" src="https://github.com/user-attachments/assets/489d9fd3-5731-4b8d-9d4e-f78baddab98d" />

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):
## OUTPUT
<img width="1017" height="185" alt="Screenshot 2025-10-26 101204" src="https://github.com/user-attachments/assets/56b0fadf-aea8-41a7-bc0e-e9120b957347" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.
## OUTPUT
<img width="702" height="575" alt="Screenshot 2025-10-26 101340" src="https://github.com/user-attachments/assets/31601a28-6860-498a-bc49-5d11624ae05e" />

# RESULT:
The commands/batch files are executed successfully.

