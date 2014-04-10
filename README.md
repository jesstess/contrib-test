contrib-test
============

A scratchpad for folks in the PyCon open source tutorial

Instructions
============

1. Visit https://github.com/jesstess/contrib-test and flick the Fork
button to fork this GitHub project.

2. Create a local copy of your fork of the repository using the
following command:

        git clone https://github.com/<your username>/contrib-test

3. Using your favorite text editor, add a new file to this project.

    a) Make the name of the file your first name, then a hyphen, then a random
       number, for example `jessica-19678`.
    b) In this file, add your home town and an open source Python project you
       are interested in contributing to, for example:

       I'm from Nashville and interested in contributing to Django!

4. Commit this addition to your fork of the project using the following commands:

        git add <name of file>
        git commit -m "Added my open source interests."

5. Push your changes to the remote repository with the following command:

        git push origin HEAD:master

6. Visit the GitHub page for your fork of the project, e.g.

        https://github.com/<your username>/contrib-test

 Observe that your file is visible in the GitHub web view for the
project.

7. Click the greeen button to create a pull request for your changes. This will
take you to a page where you can review your diff and commit message. Click the
green "Create Pull Request" button, leave a comment, and click the green "Send
pull request button".

8. The owner of the project, jesstess, can now review and merge your pull
request. Wait a few minutes for this to happen.

9. Update your fork of the project to see everyone else's changes, using the
following command:

        git pull --rebase

10. Explore the changes with commands like `git log` and `git show`.
