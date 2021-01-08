# MySQL Admin

You can use this project to deploy a container to EYK with phpMyAdmin all setup.

1. git clone https://github.com/engineyard/mysql-admin.git
2. cd mysql-admin
3. eyk create mysqladmin
4. In the web console, click on the mysqladmin application. Go to the config tab.
5. Define a PMA_HOST env var and set the value to your database host
6. git push eyk master
7. eyk open
8. You will be prompted for the database username and password, which you can get from the Database tab in the EYK web console
