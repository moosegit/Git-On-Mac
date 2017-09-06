# Git-On-Mac
Readme file for Git-On-Mac

Today: 08/16/2017

Quick setup — if you’ve done this kind of thing before
 Set up in Desktop	or	 HTTPS  SSH
https://github.com/moosegit/Git-On-Mac.git

We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line

echo "# Git-On-Mac" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/moosegit/Git-On-Mac.git

git push -u origin master


…or push an existing repository from the command line

git remote add origin https://github.com/moosegit/Git-On-Mac.git

git push -u origin master

Mac:Git-On-Mac$ git add README.md 

Mac:Git-On-Mac$ git commit -m "First Commit"

[master (root-commit) 8ec4537] First Commit

Committer: Name  <email@address.com>
 
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 Readme.md

HOW TO BACKTRACK

generalizations

Congratulations! 

You've learned three different ways to backtrack in Git. You can use these skills to undo changes made to your Git project.

Let's take a moment to review the new commands:

git checkout HEAD filename: Discards changes in the working directory.

git reset HEAD filename: Unstages file changes in the staging area.

git reset SHA: Can be used to reset to a previous commit in your commit history.

Additionally, you learned a way to add multiple files to the staging area with a single command:

git add filename_1 filename_2
