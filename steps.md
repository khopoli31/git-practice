**step-1 : Create a practice project**

mkdir git-practice
cd git-practice
git init
----------------------------------------------------------

**Step 2 — Create your first file**

notepad README.md

If prompted to create the file, choose Yes. Add this text:

    # Git Practice

    I am learning Git step by step.
--------------------------------------------------------------

**Step 5 — Check the file's status**

git status
------------------------------------------------------------

**Step 6 — Stage your file**

git add README.md
--------------------------------------------------------

**step 8 -Check again:**

git status
---------------------------------------------------------

**Step 9 — Make your first commit**

git commit -m "Add README file"
-----------------------------------------------------------

**step 10 - You can inspect it with Now view your history:**

git log --oneline
---------------------------------------------------------
---------------------------------------------------------
**Lesson 2: Modify a file and create another commit**
------------------------------------------------------------
------------------------------------------------------------

**Step 1 — Modify your README**

Open README.md in VS Code and add this line:
I am learning Git by practising commands.

---------------------------------------------

**Step 2 — See exactly what changed**

git diff
--------------------------------------------------------------
--------------------------------------------------------------
**What you've learned**

- git status — checks the state of your files.
- git diff — shows unstaged changes.
- git add — stages changes.
- git commit — saves staged changes in your local repository.
- git log --oneline — displays your commit history.
---------------------------------------------------------------
---------------------------------------------------------------


