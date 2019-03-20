
# Unity Project On GitHub

We need a web site to put our Unity projects, so we can play them via the web browser

1. Create a [GitHub account](https://github.com/)

2. Download [Github Desktop](https://desktop.github.com/)
You can use command line for GitHub, but the graphical desktop is easier to use

3. Create a new public repository. Let's call it FirstGit

3. A special file called .gitignore (the name is dot gitignore) tells GitHub 
not to upload some unnecessary files. Create this file using the web interface, and place the contents
from [here](https://github.com/github/gitignore/blob/master/Unity.gitignore).
Having a `.gitignore` reduced the number of files from 1707 to 33 for me!

3. Create another file in the FirstGit repository called "docs/test.html",
enter "Hello World" in it and commit the file.

3. Follow the instructions on [https://pages.github.com/](https://pages.github.com/)
to create a "Project Site" (not a User or Organizational Site). 
The Github Pages in Settings should be set to "master branch/docs folder"

3. Check that test.html is accessible from the web.
The URL is under Settings > GitHub Pages of your repository. URL will be something like
[https://pisan385.github.io/FirstGit/test.html](https://pisan385.github.io/FirstGit/test.html)

4. Use GitHub Desktop clone the new repository you created.
This will copy all the files from GitHub to your local computer.

5. Create a Unity project in the repository directory you just created.
Let's call this project "First".

  - Set Edit > Project Settings > Editor > Version Control > Visible Meta Files
  - Set Edit > Project Settings > Editor > Asset Serialization > Force Text

6. Create a webGL build for your Unity project. File > Build Settings > WebGL > Build 
Save it in "docs/firstwebgl" inside your FirstGit repository

7. Commit and Push the files from your local computer to GitHub using Github Desktop

8. Check that your files are accessible on the web
