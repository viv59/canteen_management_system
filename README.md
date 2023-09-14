# Canteen Management System #

Canteen Management System is used to place the food orders by users directly to canteen manager online.

	Initial steps to follow :
		
		- Create a folder named sslcms in directory c/xampp/htdocs/ and add all the files provided in it.

	To load the database :
        
       	- Run url : http:/localhost/sslcms/init.php on localhost to create sample database in your system.
	  	- Also you can delete created database by running url : http:/localhost/sslcms/outit.php
      	
	Runnig the project :
		
      	- Run url : http:/localhost/sslcms/home.php it will direct you to home page of cms project.
		- Home page will popup showing to login/register as user or login/register as admin.
	
		- If you are admin :

			- Firstly admin need to register himself on the portal.(register_admin.php)
			- After registration admin will be redirected to admin login page where he can login to main page with his/her registered credentials.(login_admin.php)
			- On admin main page Admin can add/change items to menu in "ADD ITEM TO MENU"/"CHANGE MENU ITEMS" section.(main_admin.php)
			- Admin can also see menu in "MENU" section.
			- Once the user paid for order they have placed, it will be shown in "ORDERS PLACED BY USERS"
			- After admins approval for delivery of order placed by user, admin can update delivery status in "ORDERS DELIVERED" section.(deliver.php,delivered.php)
			- Once done Admin can logout from admin main page on clicking 'Go to home page' button.(by java)
		
		- If you are user : 

			- Firstly users need to register him/her self on the portal.(register.php)
			- After registration user will be redirected to user login page where he can login to main page with his/her registered credentials.(login.php)
			- On user main page user can order items in "PLACE ORDERS" section, user need to select items from provided menu and click on 'order' button.(order.php,orderd.php)
			- After ordering user can edit quantity of items or can delete items user ordered and need to pay by clicking on 'pay' button where user has option to pay by upi or cash.(pay.php,payyed.php) 
			- After order is delivered it will be updated in "USER DELIVERED ITEMS" section.
			- User can logout from user page on clicking 'Go to home page' button.(by java).
