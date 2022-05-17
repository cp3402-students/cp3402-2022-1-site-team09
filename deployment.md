Setup Local Environment (Please go over and feel to change stepds accordingly)

Lines with # need reviewing/completion.

Setting up local host:

Clone the local host into the project folder.
Clone the GitHub folder repo inside the local host into the public folder.
Run Varying-Vagrant-Vagrants (VVV) using the command line.
After the site is completed, export the content from the live site via Wordpress's exporting tool.
Lastly, import files using Wordpress's


Using the default WPDistillery from https://github.com/lindsaymarkward/WPDistillery, a local environment was created with vagrant. This local environment was copied to a github repo; https://github.com/jc463628/Default-Local-Host, to allow everyone to have the same starting files in case anyone had problems with their local host. The main github repo (cp3402-2021-site-cp3402-2021-team16) was cloned into this local host directory with the folder named 'public'.

To setup your own local host:

Clone the Default-Local-Host into any project folder you want.
Clone the main github 'public' folder repo inside the Default-Local-Host into a folder called 'public'.
Run 'vagrant up' command.
Once site is set up, export content from live site using the Wordpress default export tool.
Import files into the local host through wp-admin.


Open command prompt or another terminal program (Git-Bash, PuTTY, etc)
In the terminal, enter: git clone https://github.com/cp3402-students/env-cp3402-2019-team21.git projectname (where projectname is the name of the folder that the repo will be cloned to)
Enter cd projectname This changes the current directory to the project folder
Enter vagrant up You should be inside the folder with the VagrantFile (you can check with ls -lah). This boots the virtual machine and creates a new install of WordPress. It will typically take a while on first time setup. If the install fails, go here: Troubleshooting.
Search 192.168.33.10 in a browser and it should load a blank copy of wordpress.
Login to the Admin Panel with username: admin | password: admin
Go to Plugins > Installed Plugins then Activate WP Sync DB, GitHub Updater and WP Sync DB Media Files plugins
Go to Tools > Migrate DB. Click pull and paste in this key:
All information should fill out automatically. At the bottom, click Migrate DB. It will ask you to login again. This time, you need to use the staging site credentials which are:











