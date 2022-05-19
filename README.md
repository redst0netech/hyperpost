![hyperpost logo](http://insider.forzasoft.ml/hp.png)
# hyperpost (name subject to change)
Hyperpost is a Twitter-like social network.

## WE ARE AWARE THAT OUR HOSTING ACCOUNT HAS BEEN DELETED. FULL REWRITE SOON.

# Selfhosting
### WARNING: AT THIS POINT HYPERPOST IS NOT READY FOR SELFHOSTING
## Requirements
To selfhost Hyperpost, you'll need:
- MySQL and Apache (XAMPP comes with both of these, although similar software could be used)
- IP forwarding setup on your router (otherwise you will only be able to view it on localhost)
- Windows (recommended) or Linux

## How to setup
First, install XAMPP (or similar software). When done, open the control panel for the program (not Windows control panel), then start Apache and MySQL. Next, clone the source code from this respository, and extract it. Then move the files to htdocs (or whatever folder your web server uses). Now, import the hyperpost-clean.sql file into your SQL database using PHPMyAdmin. Edit the config.php file if you need to, but if you are hosting it on your PC you shouldn't have to. Finally, if everything was done correctly, you should now have a functioning Hyperpost instance! Keep in mind there may be bugs and other problems due to hyperpost still being in early stages of development, so, if you need help or notice a bug, create a new issue in this repo.

## Why restart development?
The old codebase was HORRIBLE. Therefore, we are restarting it with the following things:
- New DB Structure
- New UI
- More Features
- Actually having the ability to post
- and more (probably)....

