# Unity WebGL Build On GitHub

We need a web site to put our Unity projects, so we can play them via the web browser

I have also created a video that follows the steps below. It is available at [https://youtu.be/4AhZn6zPSsI](https://youtu.be/4AhZn6zPSsI)


1. Create a [GitHub account](https://github.com/)

2. Download [Github Desktop](https://desktop.github.com/)
   You can use command line for GitHub, but the graphical desktop is easier to use

3. Create a new public repository. Let's call it FirstGit. Make the repository public. Choose "Unity" for the .gitignore file. Choose to add a default README

4. Under Settings > Pages > Build and deployment choose /docs as the root of your publishing folder.

5. Use GitHub Desktop to clone the new repository you created to your local computer. This will copy all the files from GitHub to your local computer, creating an empty directory/

6. Create a Unity project. Let's call this project "First".

6. Create a WebGL build for your Unity project. Under "Build Settings > Player Settings" choose the "Player > Publishing Settings". Select "Compression Format" to be disabled. Select "Decompression Fallback" to be checked.


6. Move the Build folder for WebGL to be inside the "docs/" folder in the repository.

7. Commit and Push the files from your local computer to GitHub using Github Desktop

8. Check that your project can be played on the web. The URL will be something like [https://pisan385.github.io/FirstGit/firstwebgl](https://pisan385.github.io/FirstGit/firstwebgl/)

9. To test your project locally, you can start a local web server using "python3 -m http.server 7800" and then visit http://localhost:7800/ to see the local files

10. You might need to enable "Decompression Fallback" under Build Settings > Player Settings > Publishing Settings

