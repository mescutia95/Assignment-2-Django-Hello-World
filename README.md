# Assignment-2-Django-Hello-World
Getting started with making a simple stand alone Django web project.

## In this assignment your website needs to do the following:

* Display "CINS465 Hello World"
* Be submitted to GitHub correctly
  * Containerized is optional
  * Must be submitted to the correct branch
* You should be able to view the site on your local machine at http://localhost/. For more information on setting up routes in Django, please see [the documentation](https://docs.djangoproject.com/en/2.0/topics/http/urls/)

## Submitting Assignment 2

If you haven't already create your CINS465 repo through the form on my website, you'll need the GitHub Token given out in lecture to do so.

The code should be submitted to your CINS465 on a branch named **assignment2**, make sure your case is identical for your branch or I may not find/grade your submission. To do this you can do the following in your repo directory, it assumes you want to add all the code in the directory:

```
git checkout -b assignment2 #create branch and switch to it
git add -A #add all
git commit -m "Assignment 2 Submission" #Commit changes to branch
git push --set-upstream origin assignment2 #Push code up to assignment2 branch on remote
```

You should have your code setup such that when cloned in your folder it can be run directly via **python manage runserver**. If you chose to you can containerize your code via docker. If you choose to do this you should have either a **docker-compose.yml** in your root directory for me to launch your project or a **Dockerfile** in your root directory I can build a container from. 
