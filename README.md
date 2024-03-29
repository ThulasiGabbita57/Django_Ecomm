# Django_Ecomm

### Project Structure: 
	Root Folder: Django_Ecomm 
					Django Code:	govesty_ecomm 
					Vue code:	govesty_ecomm_vue 
					
					
### Steps to run in local: 

	To Install and setup Django environment (Open root folder in IDE and run below commands in local terminal)
	
		• pip install django
		• pip install django-rest-framework
		• pip install django-cors-headers
		• pip install djoser
		• pip install pillow	
		
		To run, From terminal root folder, go to "govesty_ecomm" directory/folder and use command: "python manage.py runserver" 


	To Install and setup Vue environment, open another terminal and run below commands
	
		Prerequisite: Node.js should be installed and available in local machine
		• npm install -g @vue/cli
		
		From terminal root folder naviagte to "govesty_ecomm_vue" folder and run below commands
		• npm install axios
		• npm install bulma
		
		To run, use command "npm run serve"
		

Now navigate to the local/network app running path received from IDE terminal:

 App running at:
  - Local:   http://localhost:8080/
  - Network: http://10.0.0.182:8080/

### Functionalities available:
* Signup
* Login
* Categories (Men and Women)
* Latest Products
* View details for each product
* Cart button
* Add items to cart from product page
* Add or remove items in cart
* Price and quantity of items in cart
* Log out
* My account (Only Logout functionality implemented for now)
* Search
* Checkout page
* Shipping details
  
