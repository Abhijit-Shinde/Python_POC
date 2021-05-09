# Python_Django_Rest_API

1. To create a virtual environment 
	'''
	$~ python3 -m venv {name_of_environment}
	'''

2. To activate the created environment
	'''
	$~ source {name_of_environment}/bin/activate
	'''
    
3. To run Django server
	'''
	$~ python manage.py runserver
	'''
    
4. If default port i.e 8000 is busy then specify the port as
	'''
        $~ python manage.py runserver {post_number}    Eg: 8001
	'''

#### Default Credentials:
  username:admin
  password:admin
  
  Dashboard available at: http://127.0.0.1:8000/admin
  
#### API Endpoints to look for
  1. http://127.0.0.1:8000/api/v1/products
  2. http://127.0.0.1:8000/api/v1/products/{id_of_the_product}
  3. http://127.0.0.1:8000/api/v1/categories
  4. http://127.0.0.1:8000/api/v1/categories/{id_of_the_category}
  
#### For Authentication consider following endpoints
  1. http://127.0.0.1:8000/auth/register/
  2. http://127.0.0.1:8000/auth/login/
