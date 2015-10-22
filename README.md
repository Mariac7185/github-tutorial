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
11. 
  




---

## Workflow & Commands


___
