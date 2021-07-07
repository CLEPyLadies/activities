# activities

Template for activity repos

## Organizer Instructions

Intended usage for this template repo:

1. Open [the activities repo](https://github.com/CLEPyLadies/activities) on GitHub (in a browser)
2. Clone this locally if you have not already done so.
3. Select "Use this template" to create a new activity repo
    - Owner: CLEPyLadies
    - Repository name: At your discretion
    - Description: Please add something
    - Public (not private)
    - Do _not_ select "Include all branches"
    - Confirm "Create repository from template"
4. Delete the following files from your new repo:
    - `activities/`
    - `.gitmodules`
5. Add participant instructions to the `README.md` file in your new repo
    - See [this Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for Markdown help.
6. Add participant code and/or solutions to your new repo
7. Navigate to your local clone of the activities repo in a terminal & run the following commands:
    - `cd activities`
    - `git submodule add <paste url for your new repo>`
    - `git add ../.gitmodules <new repo name>`
    - `git commit -m "Include new activity <new repo name> as submodule"`
    - `git push origin master`
