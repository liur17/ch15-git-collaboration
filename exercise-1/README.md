# Exercise-1
In this exercise, you'll practice creating a repository, adding collaborators, and integrating the work of others through `merging`. You should work in groups of two or more.

## Set up

To set up the repository, take the following steps:

- **Person 1** should create a new repository on GitHub with a `README.md` file.
- **Person 1** should add **Person 2** as a collaborator to the repository on GitHub
- **Person 1** should then create two issues on GitHub: _edit README.md_ and _create exercise.R_
- **Person 1 and Person 2** should _both_ clone the repository to their machine

## Simultaneous Contribution

Here, we'll see how multiple people contributing to the same project can prevent individuals from pushing to GitHub:

- **Person 1** should edit the `README.md` file by adding a line that describes the project
THIS IS A SUPER FUN EXERCISE
This is a FUN exercise!!

- **Person 1** should then `add` and `commit` those changes, then push those changes up to GitHub (make sure to close issue 1 with a commit message)
- **Person 2** should then create a _new file_ called `exercise.R`, and add a line of code to that file (whatever you want: `x <- 1`).
- **Person 2** should then `add` and `commit` their changes, and attempt pushing up to GitHub (make sure to close issue 2 with a commit message)

At this point, GitHub should prevent **Person 2** from pushing because they are not working on top of the most recent commit to the project.

## Merging
In order to push their changes up to GitHub, **Person 2** will have to `pull` in the most recent changes and `merge` them with their own commit.

- **Person 2** should pull and rebase changes from GitHub (i.e., `git pull origin master --no-edit`). This should work smoothly because **Person 1** and **Person 2** did not edit the same line of the same file
- **Person 2** should now be able to push their (integrated) changes up to GitHub.

This exercise is a simple example of using merging _without_ conflict. To practice encountering conflict, see [exercise-2](../exercise-2).
