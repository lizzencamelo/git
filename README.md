# git
## LESSONS IN GIT
[Cloning Github repository](https://github.com/lizzencamelo/git-learning/edit/main/README.md#cloning-github-repository)  
[Opening VSCode project from local repository directory](https://github.com/lizzencamelo/git-learning/edit/main/README.md#opening-vscode-project-from-local-repository-directory)  
[Updating remote repository](https://github.com/lizzencamelo/git-learning/edit/main/README.md#updating-remote-repository)  
[Updating local repository](https://github.com/lizzencamelo/git-learning/edit/main/README.md#updating-local-repository)  
[User Configuration](https://github.com/lizzencamelo/git-learning/edit/main/README.md#user-configuration)  
[Browser Syn]()

### Cloning Github repository
i. Copy repository link from Code menu of Github repository to be cloned (*remote repository*).   
ii. Open command prompt/terminal on local.  
iii. Move to local directory where repository is to be cloned (*local repository*).     
    
     
                D:\localrepositorydirectory> 
     
    
iv. Enter command **git clone [url]**.


                D:\localrepositorydirectory> git clone https://github.com/user/repo.git
                
                
### Opening VSCode project from local repository directory.  
i. Enter commands   
  
                 D:\localrepositorydirectory> cd repo
                 D:\localrepositorydirectory\repo> cd .

### Updating remote repository
i. On making changes to local repository, we must publish the changes (*commits*) to remote repository.  
ii. Enter command **git status** to check if unpublished changes exist.   
  
                D:\localrepository\directory\repo> git status
                
iii. Enter command **git add .** to save all new changes to local machine.   
                
                 D:\localrepositorydirectory\repo> git add .
                 
iv. Enter command **git commit -m "[update message]"** to commit changes to local repository.  

                  D:\localrepositorydirectory\repo> git commit -m "UPDATE REPO"

v. Enter command **git push** to publish all local commits to GitHub.

                  D:\localrepositorydirectory\repo> git push
        
### Updating local repository
i. On making changes to remote repository, we must pull the changes to local repository.  
ii. Enter command **git pull** to update your local repository branch with all new commits from remote branch on GitHub. 

                  D:\localrepositorydirectory\repo> git pull
                  
### User Configuration 
> To configure user information for all local repositories.   

**git config --global user.name "[name]"** to set the name attached to commit transactions.

            D:\localrepositorydirectory\repo> git config --global user.name "my name"   
            
            
**git config --global user.email "[email address]"** to set the email attached to commit transactions.

            D:\localrepositorydirectory\repo> git config --global user.email "name@email"
         
### Browser syn
> Keep multiple browsers & devices in sync when building websites.
> Reflects changes in code on localhost in real time.
         
i. Open command prompt.  

            D:\localrepositorydirectory\repo> browser-sync start --server --directory --files "**/*"
            
ii. ```Ctrl + C``` to exit browser-sync connection.
  
