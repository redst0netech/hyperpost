![hyperpost logo](http://insider.forzasoft.ml/hp.png)
# hyperpost (name subject to change)
Hyperpost is a Twitter-like social network.

# Selfhosting requirements
To selfhost Hyperpost, you'll need:
- MySQL and Apache (XAMPP comes with both of these, although similar software could be used)
- IP forwarding setup on your router (otherwise you will only be able to view it on localhost)
- Windows (recommended) or Linux

# How to setup
Start Apache and MySQL. Clone the source code from this respository. Extract it and move the files to the htdocs (or whatever folder your web server uses). Now, import the hyperpost-clean.sql file into your SQL database. Edit the config.php file if you need to. If everything was done correctly, you should now have a functioning Hyperpost instance!

# Why restart development?
The old codebase was HORRIBLE. Therefore, we are restarting it with the following things:
- New DB Structure
- New UI
- More Features
- Actually having the ability to post
- and more (probably)....

