
<!--1. 
   ```sh
   
   ``` -->
   # GIT 
   ## OneTimeSetup before proceeding with GIT 
   <br>
   <br>
   
## Just after fresh installation


```sh
git config--global user.name <"username">
```

```sh 
git config --global user.email <"valid email address">
```
```sh
 git config --list git config
```
<br>

## Basic's
#### 1. Change path to current  
```sh
cd <file ko path>
```
#### 2. Initialize local repository.
```sh
git init
 ```

#### 3. Git Add (to make changes be staged/selected for commit)
##### All file at once
```sh
git add . 
```
##### or

```sh
git add particular file path
```
#### 4.Commit the changes to local repo
```sh
git commit -m "  "
```
#####  for eg: added new file,v1.1,inital-build.
<br>
<br>



## For branching 
#### 1. Check branches of the repository
```sh
  git branch 
  ```

#### 2. To rename branch to main
```sh
  git branch -m main 
  ```

#### 3. To delete branch 
```sh
  git branch -D <name of the branch to be deleted> 
```

#### 4. To merge branches 
```sh
  git merge <name of the branch to be merged> 
```
 
##### If merged and still file of merged branch doesnt appear in the default/main branch
```sh
git pull  
```

##### &
```sh
     git push origin main branch.
```
<br>
<br> 

## For Connecting local repo to GitHub
#### 1. Add remote 
```sh
git remote add origin <linkof repository>
```

 #### 2. Check remote 
```sh
git remote --v
```
<br>
<br>


## Version Control
#### 1. Check all time commits of the repository 
###### shows all commits done with their respective uniquehash values
```sh
  git log --oneline
  ```

#### 2. Revert to previous commit
```sh
 git checkout uniquehash value(to revert to the previous commit done,i.e version_control)
  ```


