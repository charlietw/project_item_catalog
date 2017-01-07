# Meals Catalog
For project 4 of Udacity's Full Stack Nanodegree


1. In order to run this application, you will first need to install some software to your local machine:
  1. [Vagrant] (https://www.vagrantup.com/)
  2. [VM] (https://www.virtualbox.org/)
2. Once these applications have been successfully installed (for further information/troubleshooting, view the relevant support sections of the software websites), download this repository to your local machine, ensuring the folder structure remains intact.  
3. In a command terminal, change directory ('cd') to the folder you downloaded the files to and type 'vagrant up'. This may take several minutes to complete, so be patient.
4. Once this has been completed, type 'vagrant ssh', then 'cd' again to '/vagrant/catalog'.
5. Now we need to set up the database. You can do this by typing 'python database_setup.py'.
5. From there you can run 'python project.py'. By default this will then run on port 5000. 
6. Navigate to http://localhost:5000/login to login using your Google account (if you had set the project to run on a different port then change 5000 to that port).
7. There are several JSON endpoints included in this application. For full routes and hyperlink construction view the project.py file (lines 199-222). To start with, try http://localhost:5000/meals/JSON to view all of the meals and http://localhost:5000/suppliers/JSON to view all of the suppliers.
8. Once you have finished with the application, type 'ctrl + c' in the cmd window, then type 'vagrant halt' to gracefully shut down the virtual machine without losing any data.

Note: Lines 23-196 of project.py (relating to third party authentication) have been adapted from [this repo] (https://github.com/udacity/ud330), found in the instructor's notes as part of Udacity's Full Stack Nanodegree.
