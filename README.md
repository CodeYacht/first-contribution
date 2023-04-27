![first-contribution](https://user-images.githubusercontent.com/91791257/234664400-33701a2e-4538-44dd-b4f7-66a88fb8a395.gif)

## How to Contribute?

1. Fork the project:

- Click the gray <kbd>Fork</kbd> button at the top right of this page. This creates your copy of the project and saves it as a new repository in your GitHub account

2. Create a New Branch:

- On your new repository's page, click the gray main button in the upper left to reveal a dropdown menu.
- Enter the name of your new branch in the text box. (Branch names usually refer to what is being changed. Example: nameAdd).
  -Click on Create branch <new branch name>, which will automatically take you to your new branch. You can make edits on the main branch, but this may cause issues down the line. The best practice is to create a new branch for each separate issue you work on. That way your main branch remains in sync with Organisation's main branch.

3. Edit:

- Now go to the `Contributors` directory and click on `Add file` button and in the drop down menu select `Create new file`.
- Name the file as `<your-github-username>.md` and fill up deatails as the example shown below:
```md
Name: [Your Name](https://github.com/<your_github_username>)

[Twitter](https://twitter.com/username) | [GitHub](https://github.com/username) | [LinkedIn](https://linkedin.com/in/username)

Description: I'm <Your Name>.
```

- You can look at [**Rupesh's Profile**](https://github.com/Code-Yacht/first-contribution/contributors/rupeshexe.md) as an example
- Scroll down and add a commit message as `added <your-github-username>.md`  and click on the green button saying "Commit Changes". Make sure you have selected the branch you have created.

4. Raise a Pull Request:

- Click `Pull Requests` (which is the third option at the top of this page after the options `Code` and `Issues`).
- Click the green New Pull Request button.
- Click on your head repository's `compare` dropdown, and switch branches from your 'main' branch to `<new-branch-name>`.
- Finally, click the green `Create Pull Request` button. Great job! You did it!

You can ask questions by raising an [issue](https://github.com/Code-Yacht/first-contribution/issues/new).

### Option 2. Complete this process on your computer (locally)

1. Fork the project:

- Click the gray <kbd>Fork</kbd> button at the top right of this page. This creates your copy of the project and saves it as a new repository in your GitHub account

2. Clone this project on your computer:

- Go to your profile. You will find forked repo named **_first-contribution_**. go to the repo by clicking on it.
- Click on the green Code button, then either the HTTPS or SSH option, and, click the icon to copy the URL. Now you have a copy of the project. Thus, you can play around with it locally on your computer.

- Run the following commands into a terminal window (Command Prompt, Powershell, Terminal, Bash, ZSH). Do this to download the forked copy of this repository to your computer.

```bash
  git clone https://github.com/YOUR_GITHUB_USERNAME/first-contribution.git
```

- Switch to the cloned folder. You can paste this command into the same terminal window.

```bash
  cd first-contribution
```

3. Create a new branch:

- Your username would make a good branch because it's unique.

```bash
  git checkout -b <name-of-new-branch>
```

4. Edit:

- Open the `Contributors` folder.
```bash
  cd contributors
```

- now create a new file named `<your-github-username>.md` using this command:
```bash
  touch <your-github-username>.md
```

- And add your details. Like this:
```md
Name: [Your Name](https://github.com/<your_github_username>)

[Twitter](https://twitter.com/username) | [GitHub](https://github.com/username) | [LinkedIn](https://linkedin.com/in/username)

Description: I'm <Your Name>.
```

5. Stage your changes:

```bash
  git add .
```

6. Commit the changes:

```bash
  git commit -m "Add <your-github-username>.md"
```

- Check the status of your repository.

```bash
  git status
```

- The response should be like this:

```bash
On branch <name-of-your-branch>
nothing to commit, working tree clean
```

7. Pushing your repository to GitHub:

```bash
  git push origin <name-of-your-branch>
```

or

```bash
  git branch -M main
  git push -u origin main
```

8. Raise a Pull Request:

- On the GitHub website, navigate to your forked repo - on the top of the files section, you'll notice a new section containing a `Compare & Pull Request` button!

- Click on that button, this will load a new page, Do not make any changes in the selected values of the branches (do so only if needed), and click the green `Create Pull Request` button.
  Note: A pull request allows us to merge your changes with the original project repo.

- Your pull request will be reviewed and then eventually merged.

Hurray! You successfully made your first contribution! 🎉
