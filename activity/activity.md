# Activity

To practice a minimal modification to a Git repo, we are going to fork a repo, create a new branch, make a small modification, merge it to the master branch and push it to GitHub.

All of the above steps will be conducted from GitKraken:

1. Clone this random [GitHub repository](https://github.com/thurwitz/example-branches) example.
    - `Clone a repo` &#8594; `Clone with URL` &#8594
    - Choose a folder where the project will be locally hosted
    - Paste URL  &#8594; `Clone the repo!`
    - `Open now`
2. **Fork** it to your own GitHub
    - `REMOTE` (left-hand side panel) &#8594; + &#8594; GitHub &#8594; Fork and Add Remote
3. Create a new **branch** called `new-feature`
    - Right-click on the last commit (top commit in the tree)
    - Choose _Create branch here_ & write "new-feature".
4. **Modify the file** README.md adding "Some change made by [your-name]"
    - In the right-hand side panel click the file README.md
    - Click on `File View` (upper part of the text editor)
    - In a new line write the text
    - Press `Ctrl` + `s`
5. **Stage** & **commit** the changes in README.md
    - In the right-hand side panel click README.md and then click `Stage File`
    - In `Summary` (bottom part of the same panl) write a short descriptive message for the commit
    - Press `Commit changes to 1 file`
6. **Push** the new branch and commit to GitHub
    - `Push` (top panel buttons) &#8594; `Submit`
7. **Merge** the `new-feature` branch into `master`
    - In the tree view: drag & drop the rectangle of `new-feature` onto the `master` branch right underneath it
    - Select "Merge new-feature into master"
8. **Change branch** to `master` (checkout to `master`)
    - Option A: double-click the top commit in the tree view
    - Option B: in the top panel where it says `branch`, click and choose `master` from the drop-down menu
9. **Push** to GitHub changes to `master`
    - In the tree view: drag & drop the rectangle of the top commit `master` into `REMOTE` on the left-hand side panel, where your GitHub name is displayed
    - Drop it right onto the `master` branch
    - Select "Push master to <your-name>/master"
10. Now go to your [GitHub](https://github.com/) account to **check** that
    - The new line in README.md is displayed (in the branch `master` that is displayed by default)
    - There is a new branch available called `new-feature` (there is a button in the top part that displays a drop-down menu with all of the branches)
