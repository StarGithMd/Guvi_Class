

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
  - [main b6433de] 02_File_Permission_Task
  - 3 files changed, 68 insertions(+), 18 deletions(-)
  - create mode 100644 02_File_Permission_Task/File_Permission_Task.md
  - create mode 100644 02_File_Permission_Task/SnapShot.jpg
  - Enumerating objects: 8, done.
  - Counting objects: 100% (8/8), done.
  - Delta compression using up to 8 threads
  - Compressing objects: 100% (6/6), done.
  - Writing objects: 100% (6/6), 132.52 KiB | 22.09 MiB/s, done.
  - Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
  - remote: Resolving deltas: 100% (1/1), completed with 1 local object.
  - To https://github.com/StarGithMd/Guvi_Class.git
  - c5415a3..b6433de  main -> main

- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ git status
  - On branch main
  - Changes to be committed:
    - (use "git restore --staged <file>..." to unstage)
        - new file:   02_File_Permission_Task/File_Permission_Task.md
        - new file:   02_File_Permission_Task/SnapShot.jpg
        - modified:   ReadMe_for_task.md

**********************************************************************************************************************

- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ ls -l
  - total 20
  - drwxrwxr-x 2 md_rustam md_rustam 4096 Apr 21 19:09 01_File_Creation_Task
  - drwxrwxr-x 2 md_rustam md_rustam 4096 Apr 21 19:49 02_File_Permission_Task
  - drwxrwxr-x 2 md_rustam md_rustam 4096 Apr 21 21:11 03_Scripting_Task
  - -rw-rw-r-- 1 md_rustam md_rustam 2744 Apr 21 19:26 ReadMe_for_task.md
  - -rw-r--r-- 1 md_rustam md_rustam   19 Apr 21 21:12 input.txt
  
- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ git add .; git commit -m "03_Scripting_Task"; git push origin main
  - [main 147f79f] 03_Scripting_Task
  - 3 files changed, 111 insertions(+)
   - create mode 100644 03_Scripting_Task/Scripting_Task.md
   - create mode 100644 03_Scripting_Task/Scripting_Task_SnapShot.jpg
   - create mode 100644 input.txt
   - Enumerating objects: 7, done.
   - Counting objects: 100% (7/7), done.
   - Delta compression using up to 8 threads
  -Compressing objects: 100% (5/5), done.
  - Writing objects: 100% (6/6), 1011.99 KiB | 29.76 MiB/s, done.
  - Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
  - remote: Resolving deltas: 100% (1/1), completed with 1 local object.
  - To https://github.com/StarGithMd/Guvi_Class.git
    - 44326d1..147f79f  main -> main
	
- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ git status
  - On branch main
  - nothing to commit, working tree clean
