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

<img width="406" height="92" alt="509694709-1c345a2a-9060-45e4-a215-f9d4cfb38407" src="https://github.com/user-attachments/assets/74110813-d88a-4991-a427-3634186e55df" />

## COMMAND AND OUTPUT

<img width="411" height="103" alt="509694760-bc699d3a-6d62-4ede-b3ff-788bd1f051ae" src="https://github.com/user-attachments/assets/918cfc50-3931-4aed-a785-17881e957d94" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="650" height="418" alt="509694866-ff199288-70ee-47eb-8b8f-3e6192a87fe9" src="https://github.com/user-attachments/assets/506372cb-cbf3-4890-bf5f-d0c0f6c5792b" />

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection


<img width="600" height="162" alt="509694929-75889be9-9423-4015-b98a-c0bb30ccf4b3" src="https://github.com/user-attachments/assets/ba89fb07-a873-4eb2-84a4-c02c796191d8" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="532" height="90" alt="509697788-00add913-4703-4528-8c5b-b0e9934a6bbe" src="https://github.com/user-attachments/assets/a68b4777-be25-4da7-98a6-0689cd516273" />

## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="439" height="81" alt="509698046-3c47a492-d5fa-4b52-9634-61f11eb48d8b" src="https://github.com/user-attachments/assets/8cfe1198-6bcc-4155-b356-43abcca8bf9a" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="532" height="90" alt="509697788-00add913-4703-4528-8c5b-b0e9934a6bbe" src="https://github.com/user-attachments/assets/bc1e532f-29e5-4df2-ae45-bce1a80ab2bb" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="678" height="776" alt="509698269-79f58c54-1297-44c0-9146-c6c73fc92f62" src="https://github.com/user-attachments/assets/ed6a8cd7-50c1-4f68-a74d-70e039ed4db5" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="678" height="776" alt="509698269-79f58c54-1297-44c0-9146-c6c73fc92f62" src="https://github.com/user-attachments/assets/e8bc5061-4c4b-48d4-8657-32be574b5428" />

## COMMAND AND OUTPUT

<img width="604" height="236" alt="509698372-a42b926a-3e25-4e68-9b5b-9ee25e4145ad" src="https://github.com/user-attachments/assets/4ed35868-b665-4960-8a51-0e7dd70b0837" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".



<img width="551" height="156" alt="509698474-0d3155f8-bed9-4dc7-a088-caac4212e058" src="https://github.com/user-attachments/assets/926129b0-7435-482c-b681-d386c7b2b64b" />

## OUTPUT

<img width="551" height="156" alt="509698474-0d3155f8-bed9-4dc7-a088-caac4212e058" src="https://github.com/user-attachments/assets/cb94c744-3fc9-42ab-a2ab-2d7eb826516a" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="600" height="211" alt="509698575-ab5efe92-3f77-4f4e-bf37-9c309c8eeff0" src="https://github.com/user-attachments/assets/da39a1fb-3ab5-4898-a6ba-deae4e11dfcc" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="539" height="206" alt="509698629-b1a7d906-40a7-4ee0-a773-a23cbca09810" src="https://github.com/user-attachments/assets/ec0ca58f-4e61-4fdf-a0eb-c599ac580eab" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="491" height="145" alt="509698711-c0b8fea5-2735-4e7a-80fc-4ad72798a367" src="https://github.com/user-attachments/assets/69511103-d1d5-4b4f-b09b-73f92bd12ddd" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.




# RESULT:
The commands/batch files are executed successfully.

