Git Branches
When working on a project, especially as a team, you want to work on features independently, so they never affect anyone else's work. Git offers us branches to keep our current work away from a teams common codebase until completion.

A branch lets you split from the main line of development. The new branch shares a part of its commit history with the main branch. At a certain commit the new branch branches off and the commit histories differ.



The teams common codebase is typically kept in the "main" branch. If you work on a new feature you:

create a new feature branch and work on that new branch.
commit your work on the new branch - the main branch is not effected.
finish work on the new feature, test the new functionality and have other developers review your work.
merge your feature branch into the main branch, so all your work is included in the main branch.
Naming branches
It is good practice to use short descriptive names for your feature branches, e.g. "contact-form". We recommend using hyphens as separators as they make the name more comfortable to read.

Git branch commands
command	functionality
git switch -c <branchname>	create a new branch and switch to it
git switch <branchname>	switch branches
git branch	list your branches
git branch -a	list all branches (local and remote)
git branch -d <branchname>	delete a branch
