# Module 2.4 Assignment

In this assignment, you will be asked to resolve a merge conflict. We want to create a `README.md` that says `"Hello World"`. 

Copy and paste these commands on your command line and press `return`:

```
mkdir MergeConflict
cd MergeConflict/
git init
touch README.md
echo "echo Hello" > README.md
git add .
git commit -m"first commit on master"
git checkout -b new-branch
echo "Hello World" > README.md
git add .
git commit -m"first commit on new-branch"
git checkout master
echo "Hola" > README.md
git add .
git commit -m"second commit on master"
git merge new-branch
```

This "script" will create a merge conflict. Resolve the merge conflict so the text in `README.md` is `"Hello World"`.

Take a screenshot of your command line showing that you have resolved the merge conflict
and upload your screenshot to a new Issue titled `Module 2.4 Assignment`. 
