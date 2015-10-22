# GitHub Tutorial

##_by Maria Cortez_

---
# Git   vs. GitHub
 
##Git    
* Is the version Control which keeps "snapshot" of the code
* Runs in the command line  
* Basic Workflow 
    * Once we initialize git for version control in which we call it a repository
*  Edit files 
*  Add files (to the stage)
    *  We need to create the add command to just choose one 

  
## Github 
* Is when you store information up in the cloud 
    * Your computer: Local Machine in this case Cloud9 
* Runs in the command line
    *to interact with the repository and to visually see the changes bewteen the commits
* Basic workflow
* Visually tracks changes 
* Easily collaborates on files 
* Requires Git 

 ---

## Initial Setup

### Setting up Git
 1. Open up [Git hub](http://www.github.com)
 2. Under your command line Tell Git your **name** so that your commits will be label correctly. Make sure to type everything after `$`
  
   ```
    $ git config --global user.name "YOUR NAME"
```

 3. Make sure that you also let Git know your personal _Email Adress_ that will also be part of the Git commits.  Most importantly make sure that you use the same email that you use in the email settings.Your command should look something like this: 

 ``` 
     $ git config --config --global user.email "Your EMAIL ADRESS"
```

#### The next steps would be confirming with Github if you would be using **HTTPS** or **SSH**

_HTTPS: Hypertext Transfer Protocol Secure_

* Would require to ype youyr email and your password everytime you log on to github. 

_SSH: Secure Shell_

  * Provides a secure network in which requires a long password
 
---

## Repository Setup

### Steps for creating a new Repository
1. On your right hand corner on your Github page there will be a **+** click on it, and then click New Repository.  
2. Name your Repository Name _a great repository would be short and easy to remember_   
 * For example, "first-repository"  
3. You can also add a description in the description box but that is **optional**.  
4. Now Click **"Create Repository"**  

### Good Job You have successfully made a Repository for your Remote!

###   Steps for creating a Local Repository 

1. In your cloud9 or any where were your linking your Github with the SSH key
2. You would have to head to Github and on your top-right press on the icon head to settings
3. On the left sidebar click on the SSH KEY  
4. Name Your Tittle based on where you would like github to connect
 * **Tittle**: Cloud9 
5. Now head to your Cloud 9 tab 
6. click on the top-right where your settings icon is located 
7. Click on SSH Keys
8. Now you paste the SSH Keys into cloud9 
9. Go to your IDE and type in ssh -T git @github.com and type in yes to confirm 
 * _IDE:Integrated Development Enviornment_
10. Remember to always be in your workspace so it will be ``` username@github-learning:~/workspace ```
11. Type in ```git init ``` to start controlling in your directory
12. Then you would git config  --global user.name "Your Name"
13. After that you would type in git config --global user.email yourusername@yourdomain.example.com
You have officially Initialize your working repository

####Making Chnages 
* Now you are wondering how to update your files 
 * The fastest way to do so is by ``` $ git add  file1 files 2 file3``` 

  _Note: Make sure to do `git status` so that you cna get a brief summary of what you haven't added to you Repository 
  
  Your able to commit now!
  Do `git commit -m "message" ` in order to help you in the future see your changes that you have made.  
  




---

## Workflow & Commands
```git init``` is when you Initialize the local directory as a Git repository  

```git add ``` adds the files in the current directory  tracking new files and start chaning them 

``` git commit -m " text"``` is a change to a file that you save in Git in which keeps record of what changes are being made and by who depending if your pushing and pulling.  

```git clone``` is a copy of the repository that is on your computer, when cloning you are able to make changes of that file and use git to keep track of what you are doing.  

``` git push ```  is when you send a confirm change to the remote that you are connected to in this case it will be Github.  

 * If you would like to change something into your local repo  you would want to push the changes so that others would view them.  
 
```git pull  ```  is when you request changes into someone elses repository and you will propose a change to the person whom you making changes in their repository.  
``` Git status ``` will see what you have modify and then you will be able to ``` git commit ``` in which will record your snapchot into your histroy when yiu view it in Github  
___ 

___
