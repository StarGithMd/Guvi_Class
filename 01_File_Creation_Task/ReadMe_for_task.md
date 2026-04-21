

### Advanced Linux Commands (File Creation Task):
- https://docs.google.com/document/d/1DE33CLw58HI1wOKju-Hzu4g-44gLzCENf5WBb9X5KrI/edit

#### Techstacks needs to be used: 
- Shell (AWS, Gitbash, WSL, Vbox)

#### How do I submit my work?
- Push all your work files to GitHub (O/P screenshot images must).
- Submit your URLs in the portal.

#### Terms and Conditions?
- You agree to not share this confidential document with anyone. 
- You agree to open-source your code (it may even look good on your profile!). Do not mention our company’s name anywhere in the code.
- We will never use your source code under any circumstances for any commercial purposes; this is just a basic assessment task. 

- NOTE: Any violation of Terms and conditions is strictly prohibited. You are bound to adhere to it.

#### Task Description:
#### 01_Q. Create a directory called ""my_folder"", navigate into it, and create a file named ""my_file.txt"" with some text. Then, create another file named ""another_file.txt"" with some text. Concatenate the content of ""another_file.txt"" to ""my_file.txt"" and display the updated content. Finally, list all files and directories in the current directory.

#### 02_Q. Create 20 files with .txt extensions and rename the first 5 files to .yml extension and Print the latest created top 5 files among the total no of files".

**************************************************************************************************************

#### Opened bash shell on my laptop and perfomed assigned task on it and pushed it on GitHub repository.
#### To complete the task activity, observed the following points and perform the suggested steps.
- [A] Create a directory called "my_folder"
  - mkdir mkdir my_folder; cd my_folder
  
- [B] Create a file named "my_file.txt" with some test.
  - echo "This is the first file." > my_file.txt
  
- [C] create another file named "another_file.txt" with some text
  - echo "This is the second file." > another_file.txt
  
- [D] Concatenate the content of "another_file.txt" to "my_file.txt"
  - cat another_file.txt >> my_file.txt
  
- [E] Display the updated contents, list the files and directory
  - cat my_file.txt
  - ls -R; ls -l
  
- [F] Create 20 files with .txt and rename first 5 files to .yml extension
  - touch my_folder/file-{1..20}.txt; for i in {1..5}; do mv file$i.txt file$i.yml; done
  
- [G] Print the latest created top 5 files among the total no of files
  - ls -R
  - ls -lt | head -5
  
  
 **************************************************************************************************************
  
- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ ls -l
  - total 8
  - drwxrwxr-x 2 md_rustam md_rustam 4096 Apr 21 19:09 01_File_Creation_Task
  - -rw-rw-r-- 1 md_rustam md_rustam 2837 Apr 21 19:06 ReadMe_for_task.md

- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ git add .; git commit -m "01_File_Creation_Task"
  - [main 68535ab] 01_File_Creation_Task
  - 2 files changed, 49 insertions(+)
  - create mode 100644 01_File_Creation_Task/ReadMe_for_task.md
  - create mode 100644 01_File_Creation_Task/SnapShot.jpg
  
- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ git push origin main
  - Enumerating objects: 6, done.
  - Counting objects: 100% (6/6), done.
  - Delta compression using up to 8 threads
  - Compressing objects: 100% (5/5), done.
  - Writing objects: 100% (5/5), 531.21 KiB | 31.25 MiB/s, done.
  - Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
  - To https://github.com/StarGithMd/Guvi_Class.git
  - 5e10c29..68535ab  main -> main
  
- md_rustam@DESKTOP-CPK0PUB:~/Guvi_DevOps$ git status
  - On branch main
  - nothing to commit, working tree clean
