## Making your first Open Source Contribution :tada:


1. Get ready!
2. Create a Github account if you haven't already. Link: https://github.com/join
3. Create an issue in this repository saying something like "Add YOUR_NAME_HERE to the contributors."
4. Comment below the issue if you're willing to work on it.
5. Wait for a maintainer to assign the issue to you.
6. Meanwhile, fork this repository using the fork button.
7. Install and setup git on your machine if you haven't already. You can follow the instructions given [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
8. Clone this repository.
    ```sh
    git clone https://github.com/ajay1706/First-repo.git
    ```
9. Check into the directory
    ```sh
    cd repo_name
    ```
10. Add remote to your fork
    ```sh
    git remote add myfork your_fork_url
    ```
    Click the green clone button on your repository to find out the "your_fork_url"
11. Look for the file "Contributors.md" in the directory. Open it in any editor (notepad, sublime, vim, nano, etc) and just add your name to the end of the file.
12. Check your modifications with `git status` command.
13. Add the file to the staging
    ```sh
    git add Contributors.md
    ```
14. Commit your changes.
    ```sh
    git commit -m "Add YOUR_NAME_HERE to the contributors. Yay!"
    ```
    PS: Replace YOUR_NAME_HERE with your lovely name.
15. Push your changes to GitHub
    ```sh
    git push myfork master
    ```
16. Open your forked repository on Github, click on the "Create a Pull Request Button", and submit a Pull Request (don't forget to add the URL of the issue you created in the PR description).
17. Now sit back and relax! Some maintainers will merge your PR soon. And voila, you just made your first contribution!! :tada:
18. Once your PR is merged, feel free to close the issue you created.


**Note:** If you are stuck at any step, feel free to open up an issue in this repository describing your problem.



Now feel free to play around with Github, follow your friends, check out the different projects, see what's trending and so on.. Remember, the more you explore on your own, the better you'll learn.
