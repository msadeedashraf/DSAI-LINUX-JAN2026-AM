# Linux Case Study Exam (WSL-Ubuntu)

> **Exam Instructions for Students**
> - Open book & open source.
> - Use your WSL-Ubuntu environment for testing.
> - Each section shows skill weight. Instructor will decide minimum required per section.
> - Show commands you actually ran (not just syntax).
> - Think in real-world scenarios, not just theory.

---

## Section A: Working with Files and Directories (12 Questions – 60%)

1. You downloaded a `.zip` project file into your **Downloads** directory. Write the sequence of commands to:  
   - move it into `~/projects`  
   - unzip it there  
   - and list only the top-level files/folders created.  

2. You’re in `~/documents`. Create a directory called `reports/2025/Q1`, then copy all `.txt` files from the current folder into that new directory.  

3. A log file `system.log` has grown too large. Write a command to:  
   - create a backup copy called `system.log.bak`,  
   - then show the first 30 lines of the original.  

4. Your colleague asks you to find every `.csv` file under `/mnt/c` and count how many there are. Which commands would you use?  

5. You have a folder `drafts/` with 100 files. Write one command that renames all files ending in `.draft` to end in `.txt`.  

6. In `~/projects/app/`, there’s a file `main.py`. Write commands to:  
   - find the full path of `main.py` starting from your home directory,  
   - and then show its last 20 lines.  

7. You want to see only directories (not files) in your `~/downloads` folder. Which command would you use?  

8. You accidentally deleted the file `notes.txt` but remember you copied it earlier into `/mnt/c/test-lab/`. Show the commands to:  
   - confirm the file exists there,  
   - copy it back to your home folder.  

9. You created a new directory `backup/`. Write a single command that copies all `.docx` files from `/mnt/c/Users/<YourName>/Desktop` into this folder while preserving directory structure.  

10. Your `~/projects/planit` folder has too many subfolders. Write a command to display the tree structure up to 2 levels deep.  

11. A file named `report.txt` is full of lines. Write a command to search only lines containing the word `ERROR` and save them into `error_report.txt`.  

12. You need to compare two directories `version1/` and `version2/` to find differences. Which command(s) would you use?  

---

## Section B: Using Vim Editor (3 Questions – 15%)

13. You open `config.txt` in Vim but want to:  
   - jump directly to line 50,  
   - delete 3 lines,  
   - then save and quit. Write the exact Vim commands.  

14. In Vim, you’re editing a script and want to copy 5 lines from one part of the file and paste them somewhere else. Which keystrokes/commands do you use?  

15. You want to search for the word `database` inside Vim and replace it with `DB` throughout the file. What’s the command?  

---

## Section C: Using Features within the Bash Shell (3 Questions – 15%)

16. You ran a Python script but it’s taking too long. Show how you would:  
   - run it in the background,  
   - then list all background jobs,  
   - and bring it back to the foreground.  

17. You often type `ls -lah`. Write the command to make `ll` a shortcut for this, and explain where you would save it to make it permanent across sessions.  

18. A long command failed, and you don’t want to retype it. How do you bring back the last executed command, edit it slightly, and rerun it?  

---

## Section D: Using Basic File Permissions (2 Questions – 10%)

19. You created a script `deploy.sh`, but it won’t run. What command will you use to make it executable?  

20. In `~/shared/`, you want all users to be able to **read** files, but only you should be able to **write**. Which two commands set the correct permissions?  

---
