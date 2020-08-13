# Module 2.4 Assignment

In this lesson, you learned about merge conflicts. To complete this assignment, you’ll create a `README.md` file that says “Hello World”. Copy and paste the following commands on your command line, then press Enter:

```
mkdir MergeConflict
cd MergeConflict/
git init
touch README.md
echo "echo Hello" > README.md
git add .
git commit -m "first commit on master"
git checkout -b new-branch
echo "Hello World" > README.md
git add .
git commit -m "first commit on new-branch"
git checkout master
echo "Hola" > README.md
git add .
git commit -m "second commit on master"
git merge new-branch
```

This "script" will create a merge conflict. Resolve the merge conflict so the text in `README.md` is `"Hello World"`.

## Submission
To submit this assignment, create an issue titled `Module 2.4 Assignment` in this repository. In the issue, provide a screenshot of your command line showing the commands you used to resolve the merge conflict in this assignment, then proceed to the next module.
