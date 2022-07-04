# login-with-facebook-and-gmail

First we have to create account on facebook and google as developer where we write our project name, app domain and some other things

Steps for login with gmail/google using php
Google OAuth Prerequisites

Create Google API project and get OAuth credentials.
click here Google Developers Console

Here are the steps For create a account on google developer and with the help of these steps use also create account on facebook develper 
After this click on Create New Project link for create new project.
Enter Project Name and click on Create button.
Once you have created a new project then you can see your project list on web page.
After this click on Google API logo for go to the home page.
Once you have redirected to home page then select project from the project select box.
After click on project select box, then one modal will popup and under this, you can find a list of project, so select your project.
Now from left menu, you have to click on OAuth consent screen.
Once you have click on OAuth consent screen, then one page will load, here you have to define application name and after this click on save button.
When you have to click on save button, then after page will redirect another page, and here you have to click on Create credential button, so one drop-down menu will appear and from this, you have to select OAuth client ID.
After click on OAuth client ID menu then you have redirected to another page, and here you can find different Application type.
From different Application type option, you have to select Web application. Once you have select the Web application option, then one form will appear on the web page. Here you have to define Name and you have also define Authorized redirect URIs field and lastly click on Create button.
Once you have click on create button, then you can get your Client ID and your client secret key. You have to copy both keys for future use for implement Login using Google account using PHP.
Download / Install PHP Google API client library.
copy this on CMD:- composer require google/apiclient:"^2.0"

Steps to implement Google authentication

Create / Send authentication request.
Access user data from Google.

Create Google OAuth Credentials

1: Create a new project and get the corresponding OAuth credentials using Google developer console page.

and add php code page in my website here index.php, logout,php and config.php are use of login with google 

Login with Facebook

Create Facebook App
Facebook App ID is required to use JavaScript SDK on the web application. Before getting started to implement Facebook Login with JavaScript API on the website, create an App on Facebook Developer Dashboard.

Are you want a detailed guide to creating Facebook App ID? Follow this step-by-step tutorial – How to Create Facebook App, App ID, and App Secret
Facebook Login with JavaScript
JavScript Code:
The following code initializes the JavaScript SDK to integrate the Facebook Login API.

FB.init() – Specify Facebook App ID (appId) and other SDK configurations.
FB.getLoginStatus() – Check whether the user already logged in.
fbLogin() – Open a login dialog to login with Facebook account credentials.
getFbUserData() – Fetch the user’s account data from Facebook and display profile info and login status to the user.
fbLogout() – Logout the user from their Facebook account. 

in my website index.php index1.php and login.php are use for facebook login
 

