# FSND-LinuxServerConfig
Project 6 (Linux Server Configuration) of Udacity Full Stack Nanodegree

This is the final project for Udacity's FSND. It's all about setting up a Linux Server and hosting our previous Item Catalog (Project 4) Application.

## IP + URL

http://54.204.197.81

http://54.204.197.81.xip.io (for login access)

## Software Installed

This project required software and python packages to be installed. Here is a rundown of some the major ones:
-Git\
-VirtualEnv\
-PostgreSQL\
-Pip for Python\
-Flask\
-SQL-Alchemy\
-Flask-Bootstrap\
-OAuth\
-Mod_WSGI

## Configurations

-I updated packages with sudo apt-get update and sudo apt-get upgrade.\
-I used SSH-Keygen to create a new public/private key for the user named 'grader'.\
-I made sure root remote SSH access was disabled.\
-I installed a Virtual Environment for all python related software and tasks.\
-I set up the firewall for ports 80, 123, and 2200.\
-Made sure local timezone was UTC.\
-Configured PostgreSQL for the application, and created a new user named 'catalog' with limited privileges to database named 'greatbooks' for the Flask App.\
-Configured the wsgi file to host the flask application.

## Third-party links and resources used for assistance

Resources used for Linux:

https://www.linux.com/learn/linux-101-updating-your-system
https://askubuntu.com/questions/222348/what-does-sudo-apt-get-update-do\
-For Updating the System

https://www.godaddy.com/help/changing-the-ssh-port-for-your-linux-server-7306
http://www.linuxlookup.com/howto/change_default_ssh_port\
-For changing SSH port

https://stackoverflow.com/questions/46028907/how-do-i-connect-to-a-new-amazon-lightsail-instance-from-my-mac?rq=1\
-Connecting to Lightsail Instance from Terminal

https://unix.stackexchange.com/questions/210228/add-a-user-wthout-password-but-with-ssh-and-public-key
https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys--2
https://www.digitalocean.com/community/questions/ubuntu-16-04-creating-new-user-and-adding-ssh-keys
-Adding User with SSH-Keygen

https://www.godaddy.com/help/remove-a-linux-user-19158
-Deleting user

https://askubuntu.com/questions/281074/can-i-set-my-user-account-to-have-no-password
-Remove password from sudo user

https://mediatemple.net/community/products/dv/204643810/how-do-i-disable-ssh-login-for-the-root-user
-Disable root login

https://blog.bigbinary.com/2016/01/23/configure-postgresql-to-allow-remote-connection.html
https://stackoverflow.com/questions/1287067/unable-to-connect-postgresql-to-remote-database-using-pgadmin
-Disable remote connections on PSQL

https://www.ntchosting.com/encyclopedia/databases/postgresql/create-user/
-Creating user and adding/revoking privileges on PSQL

https://unix.stackexchange.com/questions/201666/command-to-list-postgresql-user-accounts
-List PSQL users

https://davidegan.me/hide-git-repos-on-public-sites/
-Hiding a git repo

https://stackoverflow.com/questions/49836676/error-after-upgrading-pip-cannot-import-name-main
-Help reinstalling pip

https://www.cyberciti.biz/faq/move-a-directory-linux-command/
-Help moving files around with Linux

https://www.howtoforge.com/tutorial/ufw-uncomplicated-firewall-on-ubuntu-15-04/
-Deleting connections on UFW

https://www.codementor.io/dushyantbgs/deploying-a-flask-application-to-aws-gnva38cf0
https://www.datasciencebytes.com/bytes/2015/02/28/using-flask-to-answer-sql-queries/
https://medium.com/@rodkey/deploying-a-flask-application-on-aws-a72daba6bb80
https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xvii-deployment-on-linux
https://vishnut.me/blog/ec2-flask-apache-setup.html
-Deploying Flask App + Integrating SQL

https://www.digitalocean.com/community/tutorials/how-to-use-roles-and-manage-grant-permissions-in-postgresql-on-a-vps--2
-Modifying roles and privileges for PSQL user

https://stackoverflow.com/questions/42683478/typeerror-the-json-object-must-be-str-not-bytes/42683509
-Decoding a JSON object for Python3

https://realpython.com/flask-by-example-part-2-postgres-sqlalchemy-and-alembic/
https://blog.theodo.fr/2017/03/developping-a-flask-web-app-with-a-postresql-database-making-all-the-possible-errors/
https://vsupalov.com/flask-sqlalchemy-postgres/
-Flask, SQLAlchemy, Postgres

https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps#step-one%E2%80%94-install-and-enable-mod_wsgi
-Amazing overall guide on Flask and Ubuntu from Digital Ocean

## Concluding Thoughts

This was a fun project about Linux servers. What I like most is the trial-and-error aspect. It took me a while to get this up and running, but I feel the experience will make it easier and quicker for me to do it the next time I do it.
