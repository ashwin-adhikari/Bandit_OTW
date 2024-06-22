**Hint:**<br>
There is a git repository at ```ssh://bandit29-git@localhost/home/bandit29-git/repo``` via the port 2220. The password for the user bandit29-git is the same as for the user bandit29.

> Clone the repository and find the password for the next level.

**Solution:**<br>
- Clone the repo following the steps as in pervious levels.
![alt text](image.png)
- As in the previous levels we get a README.md file
![alt text](image-1.png)
- Check the log, we can only see two commits but more branches
![alt text](image-2.png)
- Check all the branches using ```git branch -a```, we can see several detatched branches
![alt text](image-3.png)
- checkout each branch using ```git checkout``` 
![alt text](image-4.png)
- Now read README.md file to obtain the password
![alt text](image-5.png)

