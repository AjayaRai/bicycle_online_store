# bicycle_online_store

This project is an online bike store that has two main parts, which includes:
- customer part where customer can view bicycles and it's details as shown below:<br><img src="https://github.com/AjayaRai/bicycle_online_store/blob/main/images/view_bicycles_user.png" alt="drawing" width="400"/>
- second part involve admin area where an admin have to login, and they can do (CRUD operations via website), as shown below:<br><img src="https://github.com/AjayaRai/bicycle_online_store/blob/main/images/view_bicycles_admin.png" alt="drawing" width="400"/><br>Furthermore, the admin can also add, edit or delete (CRUD) other admins:<br><img src="https://github.com/AjayaRai/bicycle_online_store/blob/main/images/view_admins.png" alt="drawing" width="400"/>

## Steps to run the program
1. Download the WAMP server in your local machine from [here](https://sourceforge.net/projects/wampserver/), and install it, then click on the icon to run it
2. Open the directory folder by clicking on the <b>www directory</b>, as shown on the image below:<br><img src="https://github.com/AjayaRai/bicycle_online_store/blob/main/images/mySql_console.png" alt="drawing" width="400"/>
3. In the <b>www</b> folder, git clone this repo
4. Then from the image shown above, click on the <b>MySQL console</b>
5. On the console, type <b>GRANT ALL PRIVILEGES ON chain_gang.*TO 'webuser'@'localhost' IDENTIFIED BY '123456';</b>
6. Create a new Database via console, by typing <b>CREATE DATABASE chain_gang;</b>
7. Then, type <b>USE chain_gang;</b>
8. Copy the [chain_gang.sql](https://github.com/AjayaRai/bicycle_online_store/blob/main/chain_gang/chain_gang.sql) content, and paste it into the console
9. Finally, click [here](http://localhost/bicycle_online_store/chain_gang/public/) to see the client page OR click [here](http://localhost/bicycle_online_store/chain_gang/public/staff/) to view the admin page where you have to login as <b>userName: raiaj123</b>, <b>password: Password£1234</b>
