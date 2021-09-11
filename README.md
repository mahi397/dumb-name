# dumb-name

I forgot git basics so refreshing them here.  
Created repository on GitHub, cloned to local machine.  
Refer https://github.com/mahi397/dumdum for the other way.

## Fun facts

- add 2 spaces at the end of a line to give a line break in GitHub markdown!!

- ".git" is a hidden folder which stores all of the files that contain all changes made in the history of this repository!

- git commit -m "Message" -m "Message description!"

- git commit -am "adds & commits all in a single command!!!. Does NOT work if adding file for the first time. Use git add . for that!"


````
path-to-repo
λ git clone https://github.com/mahi397/dumb-name.git
Cloning into 'dumb-name'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
````

````
path-to-repo
λ cd dumb-name
````

- <b>Note: </b> Here it pushes to "main" not "master"

````
path-to-repo\dumb-name (main -> origin)
λ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 705 bytes | 235.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/mahi397/dumb-name.git
   4016ead..e68aeae  main -> main
````

````                                                              
path-to-repo\dumb-name (main -> origin)                    
λ git status                                                      
On branch main                                                    
Your branch is up to date with 'origin/main'.                     
                                                                  
nothing to commit, working tree clean
````

- Setting upstream!

````
path-to-repo\dumb-name (main -> origin)                    
λ git push -u origin main                                         
Enumerating objects: 5, done.                                     
Counting objects: 100% (5/5), done.                               
Delta compression using up to 4 threads                           
Compressing objects: 100% (3/3), done.                            
Writing objects: 100% (3/3), 1018 bytes | 509.00 KiB/s, done.     
Total 3 (delta 0), reused 0 (delta 0)                             
To https://github.com/mahi397/dumb-name.git                       
   e68aeae..275f3bc  main -> main                                 
Branch 'main' set up to track remote branch 'main' from 'origin'. 
````

````                                                              
path-to-repo\dumb-name (main -> origin)                    
λ git status                                                      
On branch main                                                    
Your branch is up to date with 'origin/main'.                     
                                                                  
nothing to commit, working tree clean
````