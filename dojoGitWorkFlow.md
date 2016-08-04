### Dojo Github Workflow

hiya, this is a base-line guide for setting up, managing, and working within the Aug. Dojo MEAN stack git repo that can be found
[HERE.](https://github.com/danieloostra/dojo-MEAN-stack-august_2016 "Master Repo")

#### Getting Started

1. Navigate to the repo listed above. Find the "Fork" button, it should be near the top on the right, inline with the title of the repo. Click on that button and let the forking commence! Now you should have a forked version of this repo.

2. Open another tab in your browser, and navigate to your github account page, check out your repositories, you should have a repo that is named exactly like the one you just forked, (e.g. dojo-MEAN-stack-august_2016).

3. Let's begin working with this repo, there are a few sub-steps that will help up stay up-to-date with the base-master (Dan's master repo).

    - ```bash
    git clone [insert your forked .git address here]
    ```
    - Navigate into the cloned directory and configure a remote for your fork by creating an remote <i>upstream</i> using the base master .git link (i.e. Dan's master repo).
    [GO HERE TO READ MORE ABOUT CONFIGURING GIT REMOTES.](https://help.github.com/articles/configuring-a-remote-for-a-fork/)
    - When you are done with the above, you should be able to run the following command and update your local git repo with the data that is present in the base master repo (Dan's repo).
    ```bash
    git pull upstream master
    ```
    - Now add the files you'd like to send up to you remote repo to the folder created in the git clone process.
    - Once your files are settled, git add, commit, and push to your remote forked repo.
    - Finally, find and click on the option to submit a pull requst, verify that all your information is up-to-date and accurate and send it.

  4. Maintenance! Your daily routine will now include the following steps.
  ```bash
  # 1. Updating your local repo with the base master
  git pull upstream
  # 2. Adding work and locally adding/committing.
  git add . && git commit -m 'commit message here'
  #3. Updating your remote repo
  git push origin master
  #4. At the end of the day, submitting a pull request so that your code gets incorporated into the master after review.
  ```
