<h1>Manage files with Linxu commands </h1>



<h2>Description</h2>
In this lab, I learned how to manage and modify files in a Linux file structure. I also used the nano text editor to add text to a file.
<br />


<h2>Completed Tasks in this Lab</h2>

- <b>Creating a new directory</b> 
- <b>Removing a directory</b>
- <b>Moving a file and delete a file files</b>
- <b>Creating a file and add text using nano</b>




<h2>Environments Used </h2>

- <b>Qwiklabs</b> 

<h2>Lab walk-through:</h2>
 <h2>Task 1: Create a new directory</h2>
<p align="center">
<br/> 
(1) I used the command "mkdir logs" to create a new subdirectory called logs in the /home/analyst directory. <br/>
(2) I used the command "ls" to list the contents of the /home/analyst directory to confirm that I have successfully created the new logs subdirectory. <br/>
<img src="https://imgur.com/u8iBh9T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
 <h2>Task 2: Remove a directory</h2>
  <p align="center">
(3) I used the command "rmdir temp" to remove the /home/analyst/temp directory. <br/>
(4) I used the command "ls" to list the contents of the /home/analyst directory to confirm that I have removed the temp subdirectory. <br/>
<img src="https://imgur.com/2jeVshm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
 <h2>Task 3: Move a file</h2>
  <p align="center">
(5) I used the command "cd /home/analyst/notes" to navigate to the /home/analyst/notes directory. <br/>
(6) I used the command "mv Q3patches.txt /home/analyst/reports/" to move the Q3patches.txt file from the /home/analyst/notes directory to the /home/analyst/reports directory. <br/>
(7) I used the command "ls /home/analyst/reports" to list the contents of the /home/analyst/reports directory to confirm that I have moved the file successfully. <br/>
<img src="https://imgur.com/AJFmDll.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
 <h2>Task 4: Remove a file</h2>
  <p align="center">
(8) I used the command "rm tempnotes.txt" to remove the tempnotes.txt file from the /home/analyst/notes directory. <br/>
(9) I used the command "ls" to list the contents of the /home/analyst/notes directory to confirm that I have removed the file successfully. <br/>
<img src="https://imgur.com/6nhtqbW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
 <h2>Task 5: Create a new file</h2>
  <p align="center">
(10) I used the command "touch tasks.txt" to use the touch command to create an empty file called tasks.txt in the /home/analyst/notes directory. <br/>
(11) I used the command "ls" to list the contents of the /home/analyst/notes directory to confirm that you have created a new file. <br/>
<img src="https://imgur.com/7DMOFEM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <h2>Task 6: Edit a file</h2>
  <p align="center">
(12) I used the command "nano tasks.txt" to use the nano text editor, open the tasks.txt file that is located in the /home/analyst/notes directory. <br/>
(13) I pasted the text "  Completed tasks 1. Managed file structure in /home/analyst" in the nano editor <br/>
(14) I used the command "cat tasks.txt" to display the contents of the tasks.txt file to confirm that it contains the updated task details. <br/>
<img src="https://imgur.com/RKovfam.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
