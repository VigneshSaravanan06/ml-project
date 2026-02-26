Stage 3: Collaborative Workflow
Scenario

My teammate updated predict.py and README.md on GitHub.
At the same time, I modified utils.py and created a new file called config.py in my local repository.

Step 1: Save My Local Changes

Before pulling my teammate’s updates, I first commit my changes so nothing gets lost.

git add utils.py config.py
git commit -m "Update utils and add config file"

This saves my work safely in my local repository.

Step 2: Get Latest Changes from GitHub

Next, I pull the latest updates from GitHub.

git pull origin main

This downloads my teammate’s changes and merges them with my local code.

Step 3: Push Everything Back to GitHub

After everything is updated and merged, I push the final version back to GitHub.

git push origin main

Now the remote repository has both my changes and my teammate’s updates.
