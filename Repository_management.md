# Manage local and remote repository
Github gives you the option of having remote and local repository that can be managed through command line interface(best way)
Let us dive right into the tutorial
### Create a remote repository
1. Open your browser and go to your github account
2. Create a repository by clicking the plus sign that is located at the right top corner
3. give the repository a relevant name to your project ie first_repository
4. You do not have to create a readme.md file for now

### Create a local repository
1. Firstly you will need to have git in your computer
2. You need to configure your local repository(we do this only once)
   Type the following
   ```
   git config --global user.name "user_name"
   git config --global user.email "user_email"
   ```
where, user_name and user_email stands for your user name and email used on github

3. You can now open the terminal and type the following commands
   ```
   git init first_repository
   ```
4. This will create a folder that you should add all your files
    Then enter in the git repository
    ```
    cd first_repository
    ```
5.  You can now add all your files in this folder and make a README.md file
6. Add files For commiting
   ```
   git add -A
   ``` 
This adds all of the files at once but you can change -A to a specific file name and add them one after the other.
example 
   ```
   git add hello.html
   ```
7. Commit the changes you made 
   ```
   git commit -m "first repository"
   ```
   The words in the quotation are comments for your changes
8. Type the following command to link to your remote repository
   ```
   git remote add origin https://github.com/user_name/first_repository.git
   ```
9. Push your changes to your remote repository 
   ```
   git push -u origin master
   ```
10. If their is a conlict ie there is added files in the remote repository that you do not then you have to pull the changes then push
```
git pull
```
then 
```
git push
```
11. If you encounter another merging conflic like.
..* [fatal: refusing to merge unrelated histories](https://github.com/jhon-swai/Github-management-basics/blob/master/Solving_merge_conflicts.md)



   
