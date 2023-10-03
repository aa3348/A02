# How to Use GitHub and WebStorm: A Tutorial

## PART 1: Using WebStorm

1. **Downloading WebStorm**: 
   - First, download WebStorm from [here](https://www.jetbrains.com/webstorm/download/).

2. **Installing WebStorm**:
   - Run the installer and follow on-screen instructions.
   - After installation, open WebStorm.
   
3. **Integrating GitHub with WebStorm**: 
   - For **Windows**, navigate to `File > Settings`. For **Mac**, go to `WebStorm > Preferences`.
   - Select `Version Control > Git`. Make sure the path to the git.exe (or `git` for Mac) is correct. If you haven't installed Git, get it from [here](https://git-scm.com/).
   - Now, navigate to `Version Control > GitHub` and input your GitHub credentials to connect WebStorm to your GitHub account.

4. **Cloning a Repository**:
   - Choose `File > New > Project from Version Control > Git`.
   - Input the repository URL (e.g., https://github.com/yourUCID/A02) and choose a directory to clone into.
   - Click `Clone`.

5. **Making Changes**:
   - Modify the files as needed.
   - Once done, right-click the file or folder > `Git > Commit File...`.

6. **Committing Changes**:
   - Write a clear commit message (e.g., "Task: Update README.md").
   - Click `Commit`.

7. **Pushing Changes to GitHub**:
   - Right-click the project or file > `Git > Repository > Push` to synchronize the remote repository on GitHub.

---

## PART 2: Glossary 

- **Branch**: A separate line of development. You can think of it as a unique set of code changes with a unique name.
- **Clone**: A copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. 
- **Commit**: An individual change to a file (or set of files). It's like when you save a file, except with Git, every time you save it creates a unique ID allowing you to keep record of what changes were made when and by who.
- **Fetch**: Downloading commits, files, and refs from a remote repository into your local repo.
- **GIT**: An open-source distributed version control platform.
- **Github**: A platform/service that uses Git for version control and provides a place online to store backed-up, version-controlled work.
- **Merge**: Taking the changes from one branch and applying them onto another.
- **Merge Conflict**: Occurs when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file.
- **Push**: Refers to sending your committed changes to a remote repository on GitHub.com
- **Pull**: Refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy to stay up-to-date.
- **Remote**: A version of something hosted on a server, like GitHub.com.
- **Repository**: A directory or storage space where your projects can live. It can be local to a folder on your computer, or it can be a storage space on GitHub or another online host. You can keep code files, text files, image files, you name it, inside a repository.

---

## References:
- [WebStorm Documentation](https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html)
- [GitHub Guides](https://guides.github.com/)
- [Git Documentation](https://git-scm.com/doc)
