<h1>Item catalog</h1>
This project is a RESTful web application utilizing the Flask framework which accesses a SQL database that populates categories and their items. OAuth2 provides authentication for further CRUD functionality on the application. Currently OAuth2 is implemented for Google Accounts.
<h2>How to Run Project</h2>
<ul>
  <li> clone or downlad the repo on your  virtual machine and vagrant </li>
  <li> Run python database_setup.py to create the DB </li>
  <li> Run python project.py by vagrant </li>
  <li> open your webbrowser and visit http://localhost:8000 </li>
  
 </ul>
<h> How to Run <h>
 . Install VirtualBox and Vagrant

 . Run vagrant and go to ' /vagrant '
  
 . Initialize the database

 . Populate the database with some initial data

 . Launch application

 . Open the browser and go to http://localhost:8000

<h>Using Google APIs Console<h>

1- Go to your app's page in the Google APIs Console — https://console.developers.google.com/apis
  
2- Choose Credentials from the menu on the left.

3- Create an OAuth Client ID.

4- choose Web application.

5- You will then be able to get the client ID and client secret.

6- put your client secret.json on prjoect path 
