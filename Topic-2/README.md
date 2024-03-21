## Creating and Merging Branches 

<hr />

**a. Create a new branch named "feature-branch". Switch to the "master" branch. Merge the "feature-branch" into "master".** 


```bash
git checkout -b feature-branch
```

```bash
git add .
```

```bash
git commit -m "<message>"
```

```bash
git checkout master
```

```bash
git merge feature-branch
```

<hr />

**b. Write the command to stash your changes switch branches and then apply the stashed changes.**

```bash
git stash
```

```bash
git checkout new-branch
```

```bash
git stash apply
```
