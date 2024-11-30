<!-- Banner Section -->
<img src="assets/banner.png" title="Banner Image" width="1920px" height="400px" >

<!-- List of Content -->
## __List OF Content__
---
### 01. File System Navigation   
    
<!-- Sub content of File system navigation -->
   - ### List of content of the Home directory ( [VIEW](#List-of-content-of-the-Home-directory) )

   - ### Change Directory ( [VIEW](#Change-directory) )   

   - ### Find Bash Executable ( [VIEW](#Find-Bash-Executable) ) 

   - ### Find Current SHELL ( [VIEW](#Find-Current-SHELL) )

<br>

 <!-- Sub content of File system navigation -->
### __List of content of the Home directory__

<p>Command: ls and ls -a | Type ls then we can see list of content in Home directory and type ls -a then show all of hidden content as well </p>

    cd ~ | pwd | ls | ls -a 
   
<img src="assets/listOfContent.png" title="List of content">

### __Change Directory__

<p>Command: pwd, cd /var/log | Check current directory and got var/log directory and list of content</p>

     pwd | cd /var/log | ls

<img src="assets/changeToVar.png" title="List of content in var-log">

### __Find Bash Executable__

<p>Command: pwd, which bash | check display the path of bash executable using "which"</p>

     pwd | which bash
    
<img src="assets/which-bash.png" title="Which-Bash">   

### __Find Current SHELL__

<p>Command: echo $SHELL | This command show which SHELL currently running</p>

<p>Command: echo $0 | Another way to find SHELL | This command two types of result 1. is (bash)-> It means Current SHELL, are not login SHELL and 2. is (-bash)-> It means current SHELL, are login SHELL</p>

<img src="assets/find-shell.png" title="Echo-Shell">  

