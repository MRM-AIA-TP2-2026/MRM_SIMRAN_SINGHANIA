Task 4 and Task 5 
Create a branch called Temp and push a README file called Task_3.md containing a brief description of task 4 and 5 mentioning all Git commands used during the process 
Merge branch Temp with the main branch .Push a README file called Task_4_5.md containg the brief description of task 4 and 5 mentioning all Git commands used during the process.


Steps to be followed:
1. git branch Temp to create branch
2. git checkout Temp to change to that branch
3. to create a readme file we use nano Task_3.md
4. git add Task_3.md
5. git commit -m "Added READMED file"
6. git push origin master

for Task5 :
1. Since the files were in master branch so we merge it to our main branch using git merge main
2. git commit -m "Merged master into main"
3. git push origin main
4. now we delete the remote master branch since it is not needed by git push origin --delete master
5. now we delete local master branch by using git branch -D master
6. git merge Temp
7. git add .
8. git commit -m "Resolved merge conflicts and merged Temp into main"
9. git push origin main
10. now we again create read me file 
11. and follow the steps of adding then commiting and finally pushing.
