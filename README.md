# Simple Content Management System
A simple web based content management system. don't mess it up, store all content in one system.

### Perpose
Many people and company who own multiple sites upload a image once to there core website and src from sub sites to the core website. Then they change there core website and all sub sites and applications are broken!

Most people are making a mess around there file infrastructure cross there websites. But when the moment comes that the are going to build a new website, hell breaks lose! websites, email signatures and applications are broken and missing images, video's or icons.

Sad.. Lets fix this! Upload your images to this web application and resolve this common issue. Don't upload content to the core webroot. Upload it secure to a  Simple Content Management System (SCMS). seperated from all your websites!

### Demo
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

### Requirements
* Your webserver needs to be online, internal use won't work.
* PHP 7.0.0 or higher
* MySQL Database Server. (Build with MariaDB 5.5.56)


### How To
Some usefull How To things

#### Change the Admin folder Location?
Open the Configuration.php and change the following value to your prefered location. Then, rename the 'admin' folder inside the web root to your prefered location.
<pre>$admin_location = 'admin';</pre>
