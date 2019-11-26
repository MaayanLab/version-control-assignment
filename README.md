# version-control-assignment
A repository used for assessing your knowledge of git &amp; github

## Assignment

Please perform the following steps on your own in the order that they are stated. Please pay ensure you manually review any conflicts you experience.

- Create a fork of git@github.com:maayanlab/version-control-assignment.git
- Clone your own fork
- Create a new branch called `new-master` and perform the next steps on that branch
- Add a commit adding your name to the AUTHORS file
- Cherry pick allows you to apply a commit on HEAD that exists elsewhere.  
  The command is: `git cherry-pick <commit-hash>` where you substitute commit-hash with the commit you wish to apply.
- Cherry pick the second-to-last commit of the branch named `cherry-branch`
- Merge the branch named `problem-branch` into your branch resolving the conflicts that arise
- Push your changes to github
- Submit a pull request merging your new-master branch into the main repository’s master branch

