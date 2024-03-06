First I created a README file and during saving it after clicking commit changes, I clicked 'Create a new branch for this commit and start a pull request' and named the new branch Temp.
Then I clicked on Create pull request to save it.
Now for merging the branch, I opened git bash and used git checkout master.
Then I used git branch to see the branches and it did not show Temp so I used git remote update and it showed that the new branch is added.
To merge the branch I used git merge origin/Temp --allow-unrelated-histories which opened a unix window wherein I had to put my commit message but I couldn't figure out how to save it so I closed Gitbash and opened it again.
Then I used git commit -m "merging temp". Then I tried to merge again using git merge and it said already updated.
