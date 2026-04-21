

### Advanced Linux Commands	(File Permission Task): 
- https://docs.google.com/document/d/1nmbC9-RJLwcEViPgsntaU3rHiJMneDfXsEOyYqw0Z1c/edit?tab=t.0

#### Techstacks needs to be used: 
- Shell (AWS, Gitbash, WSL, Vbox)

#### How do I submit my work? #
- Push all your work files to GitHub (O/P screenshot images must).
- Submit your URLs in the portal.

#### Terms and Conditions: 
- You agree to not share this confidential document with anyone. 
- You agree to open-source your code (it may even look good on your profile!). Do not mention our company’s name anywhere in the code.
- We will never use your source code under any circumstances for any commercial purposes; this is just a basic assessment task. 

- NOTE: Any violation of Terms and conditions is strictly prohibited. You are bound to adhere to it.

#### Task Description: 
#### 01_Q. Create a file with .txt extension (/home/demo.txt). Change the permission set of that file, so that any user can read it, group can read/write & owner can read/write/execute it.



#### Opened bash shell on my laptop and perfomed the assigned task on it and pushed it on GitHub repository.
#### To complete the task activity, observed the following points and perform the suggested steps.
- [A] Create file unter the path: 
  - $ touch /home/demo.txt
- [B] User can read, Group can read/write and owner can read/write/excute: 
  - $ chmod 764 /home/demo.txt
- [C] List the file permission:
  - $ pwd; ls -l

*******************************************************************************************************************************
- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ ls -l 02_File_Permission_Task/
  - total 140
  - -rw-rw-r-- 1 md_rustam md_rustam   1623 Apr 21 19:51 File_Permission_Task.md
  - -rw-rw-r-- 1 md_rustam md_rustam 138761 Apr 21 19:47 SnapShot.jpg

- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ git add .; git commit -m "02_File_Permission_Task"; git push origin main
  - Everything up-to-date
  - Everything up-to-date

- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ git status
  - On branch main
  - Changes to be committed:
    - (use "git restore --staged <file>..." to unstage)
        - new file:   02_File_Permission_Task/File_Permission_Task.md
        - new file:   02_File_Permission_Task/SnapShot.jpg
        - modified:   ReadMe_for_task.md
