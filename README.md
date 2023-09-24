# Shell-scripting_Project

Preparation steps
A file "shellscript.sh" was first created to be able to carry out the project using the touch command on the CLI 
This was then modified using chmod command to make the file executable. The ls command was used to check the file 
The file was successdully created and the fact that the file is displayed as green indicated that the file is executable 

![Shellscript is created and made executable](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/c42902df-d15e-4ec3-8b98-2979813b7f9e)

1. DECLARING VARIABLES
   
After successfuly creating the file, the nano command was used to enter the edit mode of the file
A value "Oghare" was assigned to a variable "name" using the = operator.

![Variable assignment ](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/c85ee843-dc73-4405-b0f5-ab517142cc59)

The script was then run on the CLI and the result shown below shows that it was successful

![Variable assigned successfully ](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/4dfa7f96-fd35-43b5-9d4a-da46c74873cc)

2. CONTROL FLOW STATEMENTS
   
A control flow shellscript to retrieve and number and check the status of the number was written
The code was written with the following "if" and "elif" statments to see if the number entered was a +ve, -ve or 0 number

![Number checking script](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/6315e373-cb03-48bb-95a4-c88ef66c387a)

after the script was written, the code was run on the command line for the 3 possible scenarios and it worked just just fine as displayed in the image below 

![Working number checking ss](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/16175527-d874-4e28-8b53-b8abba84170a)

b. A for loop to print numbers from 1 to 5 as written

![For ss](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/d6c28add-34b5-4694-bf96-ff2e7216c4d7)

This was then tested on the CLi and it worked as desired. This is shown in the following image 

![Working for ss](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/6a52e8e4-eadd-463e-9f66-099331b02de5)

3. COMMAND SUBSTITUTION

A command substitution for a shellscript that displays date was carried out. The script below was used

![Date manipulation script](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/f0699772-2cda-4f5e-a4d0-cf823a70e7d7)

Upon running the script, the current date was displayed as intended

![Date manipulated ](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/1f7b6c38-9886-4592-a84b-bebf44367116)

4. INPUT AND OUTPUT

a. A shellscript to enable user enter their names was written 

![Username input ss](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/65e0ac6e-0424-47bf-8a96-adabbf1c88cd)

The username shellscript was run and it worked well 

![Username input working successfully ](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/75bc0ab5-8666-4652-a245-632176fa328d)

b. Output to a terminal 

A shellscript that sends an output to the terminal was written 

![Output ss](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/f505bf95-5ad3-4fe1-9e38-6f6c16247008)

The output "Hello World" which was input on the shellscript was displayed on the terminal as expected 

![Output working](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/6483860b-f07e-4c13-974e-67cee91734e9)

c. Output to a file 
The echo command was used to send an input to a file. In this instance "Hello World" was sent an an input from the CLI to a file index.txt
Once the command was issued, the file inex.txt was created as revealed in the photo below

![Output to a file](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/672d7fc5-5e40-4dd0-bfda-ea91f98d7c8e)

Using the nano command, index.txt file was opened and the content Hello World which was sent from the command line was inside the file as expected 

![Output to a file ss](https://github.com/oghare01/Shell-scripting_Project/assets/141191975/a92990c6-6860-4237-b1dd-35cd60eef7c4)

