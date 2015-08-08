#Steps to Committing from the Command Line

1. Fork the repo

2. [Make Sure You Have git downloaded](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

3. Configure your settings
```
$ git config --global user.name "Your Name Here"
$ git config --global user.email "your_email@example.com"
```

4. Clone the Repo
```
$ git clone https://github.com/JessicaGarson/intro_to_command_line_git.git
```

5. Go into the repo
```
$ cd intro_to_command_line_git
```

6. Add the origin
```
$ git remote add upstream https://github.com/JessicaGarson/intro_to_command_line_git.git
$ git pull upstream master
$ git push origin
```

7.  A few additional stepst to make sure you have the most current version of the repository
```
$ git fetch upstream
$ git merge upstream/master
```

8. Adding your file 
```
$ git add yourname.md
$ git commit -m "a comment"
$ git push origin master
```
