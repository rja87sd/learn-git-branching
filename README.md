# learn-git-branching
## Week 7 Day 1 Assignment

![image](https://github.com/rja87sd/learn-git-branching/assets/145504216/ef255b53-38f0-46e7-ad66-9327b11dac48)

- Section 1 covered the basic commands of commit and branch, which commit changes made or make an entirely new branch, respectively.
- Section 2 covered navigationg through the different commits in a branch or moving between branches.
- Section 3 covered cherry picking and interactive rebase, which allow the dev to select specific commits to push to the main branch in a neat manner.

## Week 7 Day 2 Assignment

![image](https://github.com/rja87sd/learn-git-branching/assets/145504216/2b92c4fd-2deb-4fe0-8fc8-e4f60f2c0f43)
- A Mixed Bag: This section was the most difficult for me, as I was still somewhat unfamiliar with the syntax and the commands for git. But with some trial and error, and assistance from the instructor, I was able to grasp the concept of grabbing only 1 commit through the command line.
- Advanced Topics: This one was a lot of fun. Once I got the hang of how it works, I was able to cherry-pick the required commits and rebase them to each branch without issue.

## Week 7 Day 3 Assignment
![image](https://github.com/rja87sd/learn-git-branching/assets/145504216/28b068ca-cd3c-4040-9d79-356bba5f9107)
- Push & Pull: This section was fairly straightforward. It covered the basics of the push & pull commands, retrieving and adding data to the main branch.
- To Origin and Beyond: This section game me the most trouble out of the entire game. It covered much more advanced topics such as pushing and pulling remotely while not checked out on the main branch, resetting a commit when push was denied, etc. I had to repeat each level at least once, but luckily was able to finish them.

## Week 7 Day 4 Assignment
- On your local learn-git-branching repository, create and switch to a new branch named feature-branch.
-- Local repository did not exist. Created new branch then cloned repository to local files.

- Make some changes in a file within feature-branch but do not commit them.
-- Switched to feature-branch using git switch command. Began working in index.html.

- Locally, switch to the main branch and make different changes. Commit these changes.
-- Switched to main using git switch. Made changes and committed using git add and git commit -m

- On GitHub, navigate to the same repository and make additional changes to the main branch. Commit these changes directly on GitHub. Screenshot: Capture the GitHub commit as proof of making remote changes.
-- ![image](https://github.com/rja87sd/learn-git-branching/assets/145504216/d97a55ff-bc57-499f-8beb-90a4eb64430c)

- Switch back to feature-branch locally and stash your changes using git stash.

- Perform a rebase by executing git rebase main.

- Resolve any conflicts that arise, then continue with git rebase --continue. Screenshot: Take a screenshot showing the successful rebase completion and conflict resolution.
-- ![image](https://github.com/rja87sd/learn-git-branching/assets/145504216/d21bd8f3-0c31-41eb-aff4-d629456328c9)

- Apply your stashed changes with git stash pop.
- Resolve any conflicts and make a new commit. Screenshot: Capture the final commit in feature-branch showing the application of stashed changes.
-- ![image](https://github.com/rja87sd/learn-git-branching/assets/145504216/841844de-c4c3-4514-ae94-6ae6557965c2)

- Set your local Git to merge by default during pulls with git config pull.rebase false.

- Locally, on the main branch, make and commit some changes.
-- Switched to main branch with git switch. Made changes in VS Code.

- On GitHub, add different changes to the main branch and commit them. Screenshot: Take a screenshot of the GitHub interface showing these remote commits.
-- 
Step 7: Pull and Merge Changes (Local):

Locally, execute git pull on the main branch.
If a merge conflict occurs, resolve it and complete the merge.
Screenshot: Capture the terminal showing the successful pull and merge, including conflict resolution if applicable.
Part 3: Documentation and Submission
Compile Documentation:

Update the README.md in your learn-git-branching repository.
Include step-by-step descriptions of your actions for both parts of the assignment. Indicate clearly whether each action was performed locally or on GitHub.
Insert the screenshots at the appropriate steps to visually demonstrate your process.
Reflect on Learning:

Write a brief reflection on how these exercises have improved your understanding of managing branches, conflicts, and diverged changes in Git.
Push and Submit:

Push your updated README.md with the documentation and screenshots to GitHub.
Submit the URL of your learn-git-branching repository.
