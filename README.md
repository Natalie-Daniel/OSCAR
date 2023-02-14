# Git Basics

# Prep Work
>* Step 1: First and foremost go to https://nodejs.org/en/  to download node.

>   * Click the big green button that contains the letters: LTS (the one recommended for most users)
>   * Save
>   * Open that file
>   * Complete the setup process > Finish. It will download in the background

>* Step 2: In GitHub, go to the repository you want to clone.
  
>   * Click the green Code button
>   * Download ZIP
>   * Save the file

>* Step 3: Open Visual Studio Code (or close it and restart if you had it open prior to downloading node).
 
>   * In the top left-hand corner of the screen, click File > Open Folder… > select the folder you just saved > Open
>   * At the top of the screen, select Terminal > New Terminal. 
>   * A new terminal at the bottom of the screen will pop up. All the way to the right, there is a plus sign with a drop down arrow option. Click the arrow > select 

Git Bash
>   * A Git Bash option will appear below a powershell option. Delete the powershell terminal by clicking the trashcan. 
>   * In the command line, type: npm i express. This downloads the packages you will need. 
>   * Run the command: node app.js
>   * The above command allows you to go to your web browser, type in your local host and port number (I’d start with localhost:3000), and see your app. 
>   * You are now ready to clone.





# Cloning and Navigating 

>* Step 1: Copy Repo URL and use the `git clone <Repo URL goes here>` command to create a directory for git command use. Don't include the <> when cloning.

>* Step 2: `cd directoryname` into the correct directory where your git clone created the directory. The directoryname should be the same as the clone you just created.

>* Step 3: Use `git status` to see which files have been edited and can be added for commit.





# Submitting your work
>* Step 1: `git add .` or `git add filename1 filename2 filename3` This adds your updated files to the repo. filename1,2,3 are where you should type the name of the files to add.

>* Step 2: `git status` This will check the current status of your repo, make sure all files are green (ready to be committed).

>* Step 3: `git commit -m “your message goes here”` This will commit your updated repo. Make sure to surround your message with " ".

>* Step 4: `git push` This command will push your updated code directly to the repository.




# Additional Links that might be useful
>* https://git-scm.com/docs --> Git Documentation
>* https://www.w3schools.com/git/ --> Git Tutorials
>* https://gitforwindows.org/ --> Git Download
