GitHub Task
CsBranch 'master' set up to track remote branch 'master' from 'origin'.

Task 1: Make a folder on your local system called GitHub_task and make a program in any language of your choice which prints the statement “Hello World!” inside said folder. Push the folder into the GitHub repository just created using the Linux command line.

For this task the following steps are used : 
1. First we make a new directory mrm_task using mkdir.
2. next we change to that directory using cd command. 
3. next we create a folder for Github_Task in which we create a c program file name hello.c. 
4. Next we run the file using cc hello.c -o hello 
5. Thus we get hello world! printed on our terminal.
6. Now for git we first configure using commands git config --global user.email
7. Our next step is initialization using git init
8. next we add our folder using git add Github_Task.
9. next we commit using git commit -m "Initial commit"
10. our main step now is to link with our github repo this is done using git remote add origin url
11. now we push it to our remote repositary using git push -u origin master
12. now we need to enter our username and for password we need to enter token key generated.
