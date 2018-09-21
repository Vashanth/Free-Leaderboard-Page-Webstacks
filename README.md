# Free-Leaderboard-Page-Webstacks
<h2>WEBSTACKS TASK 2: LEADERBOARD PAGE</h2> 

**Leaderboard page done for Webstacks-SASTRA UNIVERSITY web development club. The website is done with HTML,CSS,JS and PHP**
* signup.php contains the Register block  and the first user is set as Administrator by default and the following registrations 
  will be Normal users
* Access for users to admin content is blocked and if anyone tries to access the URL the access is prevented by the use of 
  sessions where every time a user or admin logs out the session is destroyed and when one logs in the session is created
* login.php contains the login module where if an Admin logs in the page is re-directed to a page with different view and
  functions from a Normal user and it holds good for users also
* In utask.php, a user can view the tasks uploaded by the Admin and in the leaderboard.php the ranking is
  displayed and the Top 3 are distinguished  from others in the ranking position. Logout option with respective user's email 
  is also given in the navigation bar in the top along with Leaderboards and Tasks
 * Also in the leaderboard.php when a user name is clicked, the user's details are displayed as we have toggle with javascript
 * In admin.php the leaderboard is displayed along with few buttons where the admin can select to manipulate and beneath all of 
 this admin list is  also displayed. The Delete user button will lead to del.php where the user will be deleted by the given sql 
 commands. The Change Acct Type will change the account type of a Normal user to admin and it can only be done by an admin. 
 The points can also be updated by the admin and the Leaderboard rankings accordingly change to a descending order
* Admin can also  update the tasks along with due date which is done by tasklist.php and the Edit tasks conatins all present
 tasks and also contains a form below in which new tasks can be uploaded
* connection_info.php is included so  that database could connect to PHP and the database name  is uniform throughout 
  the web-page
* In all places javascript window alert is used to make the webpage more interactive and understandable in every stage
* Bootstrap  is used in various places  to make the page look good and also a CSS file styles.css is included 
 > DONE BY Vashanth and Ramvardhan
