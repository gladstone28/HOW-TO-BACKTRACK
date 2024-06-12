

HOW TO BACKTRACK
more git add
5 min
The hamlet repository we are working on contains five files. In Git, it’s common to change many files, add those files to the staging area, and commit them to a repository in a single commit.

For example, say you want to change the character “LARRY” to “LAERTES” in the script. The name currently appears in two files. After you change the name in both files, you could add the changed files to the staging area with:
```
git add filename_1 filename_2

```

Note the word filename above refers to the name of the file you are adding to the staging area, such as scene-3.txt.

### Instructions
Checkpoint 1 Passed
1. The code editor is open to scene-3.txt and scene-7.txt. In scene-3.txt, everywhere you see the name “LARRY” change it to “LAERTES.”

Checkpoint 2 Passed
2. Now change all instances of “LARRY” to “LAERTES” in scene-7.txt.

Checkpoint 3 Passed
3. Add the files to the staging area together using a single git command.
