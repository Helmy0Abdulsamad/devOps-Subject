How to make website and run into docker (beta test).

First of all you need something that you create project (depend on you like) , i create web project using math step by step :

- to add some Divide the content into sections or subheadings according to topics (e.g., Addition, Subtraction, etc.).
- Example: Include examples of questions and solutions.
- Conclusion: A summary of what has been discussed that on school.

- i create some Formulas and Symbols to Use the "Insert Equation" feature in Word or a similar tool in another application to write a mathematical formula. Make sure all symbols and notations used are well explained. then i create time out to make challange brain out 

after that i add some java and css for ui and other, once you want add some more feature what you gonna do (to git push commit in desktop github) no need to make that way just try  this way :

try Git its a version control system widely used to manage software projects. Here are the basic steps to start using Git:

1. Install Git
- Download and install Git from the official site.
- Make sure Git is installed by running the following command in the terminal:
(git --version)

2. Initialize Repository
- To start a new project, create a folder for the project, then go to that folder:
(mkdir project-name)
(cd project-name)

- Initialize Git repository:
(git init)

3. Adding Files
- Create a new file or copy an existing file into the project folder.
- Add files to the staging area:
(git add filename)
- To add all files, use:
(git add )

4. Make a Commit
- After adding files, make a commit to save changes:
(git commit -m "Commit message describing changes")

5. View Status and History
- To view the status of an existing file:
(git status)
- To view commit history:
(git log)

6. Create a Branch (Branch)
-To create a new branch:
(git branch branch-name)
- Switch to that branch:
(git checkout branch-name)
Or, you can create and switch to a new branch all at once:
(git checkout -b branch-name)

7. Merging Branches (Merge)
- Switch back to the main branch (e.g. main):
(git checkout main)
- Merge the branches you have created:
(git merge branch-name)

8. Push Changes to Remote Repository
- If you use a service like GitHub, create a new repository there.
Add remote repository:
(git remote add origin url-repo)
- Push your changes to the remote:
(git push -u origin main)

9. Taking Changes from Remote
- To retrieve the latest changes from the remote:
(git pull origin main)

once you have files inside it by use git in terminal so now you  got full folder in GitHub 
as u can see on path it will be C:\Users\helmy_ikinon\Documents\Github\Dev-Ops

After cd will be like this u wil get 

 C:\Users\helmy_ikinon\Documents\Github\Dev-Ops

once you done everthing that commit push now you able to do this as the same like usualy cause it make you update code or something that your side, after that what you gonna do once you done website now we jump into next step is docker 

whats docker about 

Docker is a tool that can help simplify the deployment process for developers who are building applications or services that run on multiple operating systems.

By creating Docker containers, you can easily launch multiple applications or services on systems such as VPS hosting or dedicated machines. Docker is also lightweight, easier to use, and has better performance compared to virtual machines.

Docker containers have all the necessary dependencies to run the application thus minimizing compatibility issues. It is important to create Docker containers from scratch for any development project launched using this open-source software.

Well, this tutorial will explain how to create a Docker container, guide you through its benefits in software development, as well as the best tips for using it.

step by step 

To build docker image by typing specific commands line in DevOp directory  C:\Users\helmy_ikinon\Documents\Github\Dev-Ops

1- Docker build -t quick-math-html

wait till everything it’s installed

after that u should push the image into docker hub repo :

Helmy Abdulsamad 651431014

2-docker push quick-math-html

After that set the port for the project:
