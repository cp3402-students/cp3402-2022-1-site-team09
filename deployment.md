Setting up the local enviroment:

1. Clone the GitHub repo into the project folder.
2. Open command prompt, change the directory to VVV folder using command line "folder name".
3. Run Varying-Vagrant-Vagrants (VVV) using the command line using the command vagrant up.
4. After the site is set up, export the content from the live site via Wordpress's exporting tool.
5. Log into the backend of WordPress, then import all the files using WordPress's import funciton.

Commiting theme to GitHub:

1. Log into the backend of WordPress using command line.
2. To find any unversioned files, use git status.
3. To add additional files, use git add (file path).
4. Along with own commit messages, use "-m "commit message"
5. To push to GitHub, use git push origin master.

Merging with staging site:

1. For the desired branch you wish to merge into, click on the a2 repository then press branches->new pull request.
2. To merge from: local to staging deployment, merge from compare:master to base:staging.
3. From staging
4. 
5.    


Yet to include:


how we use our staging site to test before pushing to the main site
include things such as how we manage everything eg moving files across and back ups as well as version control






















