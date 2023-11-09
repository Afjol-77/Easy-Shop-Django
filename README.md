# Easy-Shop-Django

* An eCommerce application built with Python Django Framework. <br> <br>
[Live App](https://pr1.pythonanywhere.com/)

![screenshot](https://github.com/Afjol-77/Easy-Shop-Django/blob/main/media/photos/screenshot.png?raw=true)

<br>

---

### Features: 
* Custom user model, categories and products, Carts
* Incrementing, Decrementing and removing cart items
* Unlimited Product image gallery
* Orders, Paypal Payment Gateway 
* After-order functionalities such as reduce the quantify of sold products
* Send the order received email, clearing the cart 
* Order completion page as well as generating an invoice for the order
* Review and Rating system with the interactive rating stars that even allows you to rate a half-star rating
### User Account Functionalities:
* Send confirmation mail after sign up
* On account dashboard, user can edit his profile inforamtion, profile pictures, change his account password
* Also manage his orders and much more <br>

<br>

## How to run this app on your machine? <br>
### 1. Extract and open the project, then install the requirements.txt using pip
```
pip install -r requirements.txt
```
### 2. Rename the .env-sample to .env , move it to 'easyshop' directory. Your .env file will be like this
```
SECRET_KEY=
DEBUG=
EMAIL_HOST=
EMAIL_PORT=
EMAIL_HOST_USER=
EMAIL_HOST_PASSWORD=
EMAIL_USE_TLS=
```

### 3. For migrations, type this on your terminal
```
python manage.py makemigrations
python manage.py migrate
```

### 4. Run the server using the following command
```
python manage.py runserver
```

Your Django project is **LIVE** now on your localhost. <br>
Open your browser and type **127.0.0.1:8000** on address bar.<br>
<br>
___
### THANK YOU!
