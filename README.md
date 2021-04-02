## Instructions for Digital Stewards Assignment:

### Step 0. These instructions assume that you have already correctly set up git on your local machine and you have set up your SSH keys (so that you can connect to your GitHUB repo via SSH).

** DO NOT PROCEED UNLESS YOU HAVE DONE STEP 0**
** IF YOU NEED HELP SETTING UP, CHECK LECTURE SLIDES, ASK AN INSTRUCTOR, OR GO TO OFFICE HOURS**

### Step 1. Fork this repo by clicking the fork button on the top right of this screen.

Make sure to rename the repo to be YOUR\_GITHUB\_USERNAME.github.io

At this point, you should be able to view a copy of this website on the Internet at https://YOUR_GITHUB_USERNAME.github.io

However you might have to be patient! This may take about ~20-30 minutes to update on the GitHub servers. Until then, you can continue to the following steps.

### Step 2. Clone your copy of the repo into the directory of your choice on your local machine.

To do this, first copy the address for the repo by going to the GitHub repo and clicking the green "Code" button, clicking the SSH option, and then copying the address. The address should look something like git@github.com:YOUR\_GITHUB\_USERNAME/\YOUR\_GITHUB\_USERNAME.github.io.git

Then on your local machine, on your terminal, cd into the directory that you want this repo to be located on. After that, run this command:

	$ git clone git@github.com:YOUR\_GITHUB\_USERNAME/\YOUR\_GITHUB\_USERNAME.github.io.git

### Step 3. Open up the website on your local machine in your web browser to check that it works correctly.

There are multiple ways to do this. 

- One way is to run the command "open index.html" in your terminal when you are in the same directory as index.html. 
- Another way is to open up your computer's file browser and double click "index.html".
- Another way is to open up your computer's file browser, and open up your web browser, and drag the "index.html" file into the tab bar of your web browser.

Make sure that you are able to view this, because when you are editing your website, you want to be able to view your changes.

### Step 4. Make your first edit! 

Change the name from "Alex Smith" to your own name! 

Do this by opening index.html in your favorite text editor (e.g. nano, Sublime Text, Atom, Visual Studio Code, etc.) and navigating to the "Hero Section" (this should be around line 75 in the file).

On the line that says:
```
<h1>Alex Smith</h1>
```
Change it to say:
```
<h1>YOUR NAME</h1>
```

After this, save the file, and check out what your website looks like in your web browser (same as Step 3)! If you already have the file open in your web browser, you can just refresh the page to see the changes.

Now, if you like these changes, you should make sure this is saved on your online repo so that you don't lose it! To do this, run the following commands:

	git add index.html
	git commit -m "Updated hero section to display my own name"
	git push

*At this point the GitHub servers should be properly updated. So you should be able to view this page on the Internet at https://YOUR\_GITHUB\_USERNAME.github.io too!*

### Step 5. Make atleast 5 more changes!

For this homework assignment, your job is to make atleast 5 changes to the website. Here are some suggestions:

- Change atleast one picture (pictures are located in /assets/img/ folder)
- Change the resume to become your own
- Delete sections that you don't like 
- Update the contact information
- Update the About me section
- Update the skill section

Make sure that you are pushing these changes to your repo anytime you make a significant change that you like! That way, in case you make a mistake that you don't know how to fix, you can always go back to that version of your website!

### Step 6. Submit your final website to the course staff email.

Email the link to your website (https://YOUR\_GITHUB\_USERNAME.github.io) and a list of the changes you made to the course staff email.
