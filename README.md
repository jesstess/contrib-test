contrib-test
============

A scratchpad for folks in the PyCon open source tutorial.

Instructions
============

1. Visit https://github.com/jesstess/contrib-test and flick the Fork
button to fork this GitHub project.

2. Create a local copy of your fork of the repository using the
following command:

        git clone https://github.com/<your username>/contrib-test

3. Add the upstream for the original project: 

        cd contrib-test
        git remote add upstream https://github.com/jesstess/contrib-test

4. Using your favorite text editor, add a new file to this project.

    a) Make the name of the file your first name, then a hyphen, then a random
       number, for example `jessica-19678`.
    b) In this file, add your home town and an open source Python project you
       are interested in contributing to, for example:

       I'm from Nashville and interested in contributing to Django!

5. Commit this addition to your fork of the project using the following commands:

        git add <name of file>
        git commit -m "Added my open source interests."

6. Push your changes to the remote repository with the following command:

        git push origin master

7. Visit the GitHub page for your fork of the project, e.g.

        https://github.com/<your username>/contrib-test

 Observe that your file is visible in the GitHub web view for the
project.

8. Click the greeen button to create a pull request for your changes. This will
take you to a page where you can review your diff and commit message. Click the
green "Create Pull Request" button, leave a comment, and click the green "Send
pull request button".

9. The owner of the project, jesstess, can now review and merge your pull
request. Wait a few minutes for this to happen.

10.  Once the pull request has been merged, you need to update your version of the project.
Refresh from the upstream so that you can pull down the changes :

         git fetch upstream

11. Merge the changes with your copy of the repository :

         git merge upstream/master

    NOTE: See https://help.github.com/articles/fork-a-repo for "What is the difference between fetch and pull"

12. Push changes to your github fork :

         git push origin master 

13. Explore the changes with commands like `git log` and `git show`.
