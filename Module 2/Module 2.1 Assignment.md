# Module 2.1 Assignment

In this lesson, you learned how to create a remote repository from scratch. But what happens if you want to create a local version of a remote repository that already exists? Now, if a repository already exists, and it already has code that you want, you can actually copy it to your local machine using the command `git clone` followed by the Repository URL.  

In this assignment, you’ll learn how to clone a repository on GitHub to your local machine, allowing you to manage and edit files locally. To complete this assignment, follow the instructions below:

1. Navigate to the main page of this repository on GitHub. Click the green button that says `Code` then copy the URL by clicking the gray clipboard icon. (**here is an example screenshot of the original repository; you will clone your own repository**)
 
     ![GIF demonstrating how to copy a remote URL](https://user-images.githubusercontent.com/2359538/107465091-36aaec80-6b27-11eb-8c04-fcc055dbaa0d.png)

2. On the command line, type `git clone` along with the URL you copied earlier, then press Enter.  
```
$ git clone https://github.com/YOUR-REPOSITORY.git
```

3. After the repository has successfully cloned to your machine, type `ls` in your terminal to view the newly cloned repository in your machine’s directory.

## Submission
To submit this assignment, create an issue titled `Module 2.1 Assignment` in this repository. In the issue, provide a screenshot of your command line showing the commands you used to complete this assignment, then proceed to the next section in this module.
