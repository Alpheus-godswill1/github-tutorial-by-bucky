# What Is Git and Github

1.According to bucky, it is a program that let's you keep changes in files,folders and repositories.
* It let's you manage all version of the same exact file which is done more appropriately than a person does.

# Note

1. It's not only for programmers, it's also for graphic designers , technical writer etc ,note also anyone can make use of it.

# Get Started With Git and Github, From A Newbbie To An Expert .

1.Download git and github from the links below depending on your operating system
[Git](https://git.scm.com/downloads)
[Github](https://github.com)

## After Installing The Applications To Your Local Machine
1. Go to the git folder 
> Double click on gitbash.
>> Run ``` git --version ``` or follow the step below.
2. Run on windows  ```command line or terminal`` to see if you properly installed the applications
```git --version ```

## Config Our Username And Email 

1. Running this on ```git bash ```
>>``` git config --global user.name "Alpheus Godswill" ```
>> ``` git config --global user.email "harr789@gmail.com" ```

# To see if your setting is saved and every thing is good to go.
>```git config --list```

# To clear screen 
>>```clear```

# To view only one configuration 
>>>```git config user.email ```
>>>```git config user.name ```
>>>```git config help.format ``` etc

# To learn more on something you dont quite understand 
>> ```git help```
or to learn more on a topic singly, lets try using ```commit```
>>> ```git help commit ```

## Creating Your First Repo

1. creat a folder called ```Tuna``` on desktop
2. Run ```pwd ---present working directory ``` to know which directory you are located on you system.
3. use ```cd --- change directory ```  to navigate to ```Tuna``` folder
>>>```cd .. ``` to go back a directory or folder
>>>```cd Destop```
>>>```cd Tuna ```
>>>```git init ``` to start a git project, and keep track of the changes in this folder

### Creating Our Very First Commit
>>type ```ls``` for the list of the folder where you are in.
>> for hidden files on windows type ```dir\adh```

1. create and ```index.php file``` on your visual studio code editor 
2. write what's on your mind e.g ```hello my name is Alpheus ```
3. press ```ctr + ` ``` to pop up your visual studio code terminal
4. type ```git add . ``` keep track of the stuffs you wrote on the ```index.php file```
5. type ``` git commit -m "This is my first commit " ``` to take a snapshot of the changes you made in your ```index.php file```
6. NOTE ``` when ever you make a change on you working file or folder or directory ``` make sure to write on your terminal
```git add filename or git add . git commit -m "reason why you did the changes in the first place" ```

## How to view all your commits history
```git log ```
1. How to view commits from a particular person or programmer
```git log --author="name of person"```

### How to know better the status that are made on your file
```git status```

## How to view your Workflow 
1. Note the are three areas when working with any version control e.g git/github
````working copy > staging area > repository ```
2. 
```git add "file name"``` -> moves files to the staging area
```git commit -m "what you modified in your working area" ```-> pushes code or changes to the repository.

## How to Edit Files
1. After making changes to the file or code you are working on 
>>> ``` git status ```
>>> ``` git add . ```
>>> ``` git commit -m "what you edited in the file" ```

## How to view the changes in the files you are working on 
1. Make some changes in your working file or directory
>>> ```git status```
>>> ```git diff ``` --- is how to view the changes in the files you are working on
 
2. Note : 
>>> ```The red color signifies the changes in your repositories ```
>>> ``` The green color signifies the working directory ```
### Comparing the staging area with the repository
1. when changes are made to a file 
>>``` git add filename ``` -> sends files to the staging area 
>>````git diff ``` -> only works with the working directory
>>>```git diff --staged ``` helps you see the differences in the staging area after you have ```git add filename ``` the file.
2. when the changes are commited, it means the changes are sent to the repository .

## How to delete files 
1. The are a couple of ways to do this though .
>>``` git rm  filname ``` -> but must be added and  commited to the repository.
 
## How to rename files and move files around 
>>> I think there are 2 ways to do this. 
1. You manually change the name. 
2. go to visual studio terminal and run ```git status ```
3. run ```git add renamed file ```
4. run ```git rm "previous file that was renamed" ```
5. run ```git commit -m " I just renamed a file name " ```

## Another way to rename files

1. run ``` git mv oldnamefile.txt newnamefile.txt ```

## How to move a file to another folder
1. run ``` git mv file.txt  folder/newnamefile.txt ```
2. run ``` git status ```
3. run ``` git commit -m "renamed file and put in folder/ and changed the oldname to newnamefile.txt" ``` 


## Working with an actual projects 
1. clone the repo below by running ```git clone https..//github.com/...............```
[Gonzo](https://github.com/.......)

2. run ```git init ``` -> to initialize it .
3. run ``` git status ``` -> to check the status.
4. run ``` git add . ```
5. run ``` git commit -m "New files cloned from the gonzo website on bucky repository " 

## How to commit directly from your working copy directly to your repository
1. make any change you feel like
2. run ``` git status ``` -> to check the status. 
3. run ``` git commit -am "just made some simple changes to be able to commit directly to my repository" ```
4. Note the ```-a``` helps one skip from the working copy and the  staging area directly to the repository 

## How to undo changes to my working directory from the repository
1. run ``` git status ```
2. run ``` git checkout -- filename.attached ```

## How to unstage files
>>> please always run this command on your terminal
1. run ```git init ```
2. make some changes or editing to the code or files
3. run ```git add . ```
4. run ``` git status ```
5. run ``` git reset HEAD  nameofthefile.attached ```---> This is the unstaging command 

## Getting Old Versions Of My Projects From My Repositories
1. After making some edits on the original working copy and it tend not to fit your requirements.
2. run ```git log ```
3. make sure you get  a copy of that by running ```git checkout 01e7dba -- nameoffile.attach ```
4. run ``` git status ``
5. run ``` git commit -am " undoing kevins mistakes " ```
6. run ``` git status ```

## Learning how to use Github
1. what is github 
>>> It's a website and a product that allows you to make public projects and allows others to interact with your projects
2. First you must get an account
3. Making your first new public repository 
4. Name the repository according to what you feel
5. Make either public or private depending on the purpose 
>>>Note: private has a simple cost though.
6. Remember (BRM-> Bucky's Room Mobile)

## How to push your code to a repository on github from your local machine



















