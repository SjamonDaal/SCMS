# Simple Content Management System
A simple web based content management system. don't mess it up, store all content in one system.

### Perpose
Many people and company who own multiple sites upload a image once to there core website and src from sub sites to the core website. Then they change there core website and all sub sites and applications are broken!

Fix it by managing all content in one system. seperated from all your websites!

I'm building the panel on a live website. Test it if you like to!
* site: https://media.sdhd.nl/admin/
* username: admin
* password: admin

Reminder: It's a live development enviroment. When I start working on uploading files I'll change the password and stop the demo.


### Installation Guide
1. Simply upload the files your Web Server.
2. Create a Sub Domain for the site and secure the site with SSL, something like https://media.sdhd.nl
3. Upload the database to your database server and change the configuration.php to your database settings.
4. Change the admin folder location to make it more secure :)
5. login as Admin (Password: admin) and change the default password.


### How To
Some usefull How To things

#### Change the Admin folder Location?
Open the Configuration.php and change the following value to your prefered location. Then, rename the 'admin' folder inside the web root to your prefered location.
<pre>$admin_location = 'admin';</pre>
