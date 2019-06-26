# 2381_Homepage
Colonel By's Kernel Bye VEX EDR teams' official homepage (2019-2020 season).


# Setup: 
1. Install git https://git-scm.com/
2. Create a local file on your computer
3. Right click within the folder, click GITBASH HERE
4. In the console,  `git clone https://github.com/2381-robotics/2381-robotics.git`

# Workflow
### Before You Start Coding
1. In the repository on Github, navigate to the `<Issues>` tab
2. If there is something here that is not assigned to anyone and you would like to work on, click on it and skip to step 5.
3. Otherwise, create a New Issue and give it a title and a brief description.  Under Label tab on the right, select an appropriate label.
5. Under the Projects section below Labels, click 2381 Website Code. 
2. On the right, under the `<Assignees>` tab, select yourself.
3. Navigate to the 2381 Website Project in the Projects Tab. Move the issue you selected from  `<To Do>` over to `<Open>`.
3. Navigate back to <>Code in Github, create a new branch and call it the name of the feature you are developing (I.E. Navbar or Community Page etc.)
4. On your local file explorer, go to the 2381-website file and GITBASH there
5. Create a new branch by using the command `git branch <local branch name>` (NOTE: this local branch is a different thing than the branch you created in the cloud, and will be denoted as `<local branch name>` as opposed to `<cloud branch name>` )
6. Navigate to the branch you created with `git checkout <local branch name>`
7. Update your local files with `git pull origin <cloud branch name>`
8. Do your work (Code the actual shit)

### After Coding
##### Do this after each time you finish something and after everytime you leave your computer to go do something else. Treat this like a CTRL+S.
1. Open GITBASH in the 2381-website file
2. `git add .` This adds all of the changes you made into the local git
3. `git commit ` This will open your default text editor (Probably Notepad)
4. In the text editor add a commit messages detailing the changes that you have made. This is so that other people will be able to understand the shit you just did. The way this will be formatted is: 
     1.   First Line : One sentence summary of changes you have made i.e. (Fixed the scrolling bug + added image files)
     2.   Lines after that : In depth explanation to how did it. This should be able to be understood by other programmers who need revise and change/fix your code in the future. I.E. (Found conflicting style classes for div element, created new div ID to resolve it with width, height, position properties)
5. Now all you have to do is send your changes to the cloud with `git push origin <cloud branch name>`
*Note* This process should happen several times per project, just like you save an english essay several times before you finish it.

### After Finishing A Feature / Project
1. Make sure that the finished code/ latest version of your code is in the cloud branch
2. In Github, in your branch, click Open Pull Request
3. If it isn't already, change Base Repository to 2381-Website
4. Make sure the base branch is Master and the compare branch is `<Cloud Branch Name>`
5. Under `<Leave A Comment>`, list the changes that you have made, go into detail where necessary
6. Click `<Create Pull Request>`
*NOTE:* A Pull Request is completely different from a Pull, and should be called a Merge Request if Github wasn't a small Indie games company. A Pull Request is you saying "Hey, I think I have my shit together and my code is good now, can we merge this into the good copy?". This lets your team check through your code, understand wtf is going on, and make sure your shit isn't spaghetti. Everyone needs to read through everyone else's Pull Requests so that you know whats going on. **IT IS EXPECTED FOR EVERYONE TO LEAVE A COMMENT ON ALL PULL REQUESTS SHOWING THAT YOU HAVE READ THROUGH THE CODE. IMA WHIP PEOPLE WHO DONT READ THEIR SHIT - YOU HAVE BEEN WARNED**




