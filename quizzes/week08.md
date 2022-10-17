# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
It collects all the required dependencies for the program.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
Most likely the same level as the topmost main files so it can load the proper dependencies with the program.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
Seems to be npm run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
env (environment) files
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
Seems there is a command line input with some different arguments that can be put in, but basically: "heroku logs" using heroku CLI.  Can also be seen from the dashboard.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Using git to push to heroku master.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Updates can be made and tested without affecting the production site.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code review should happen before any merging of branches.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merge
```