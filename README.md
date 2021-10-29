# project
<h1>Apps map</h1>

	~/
		|-- run.py
		|-- config.py
		|__ /env                            # Virtual Environment
		|__ /app                            # Our Application Module

			 |-- __init__.py                #here will be registered all blueprints
			 |-- /mod_auth                  # Our first module, mod_auth
				 |-- __init__.py            #local blueprints
				 |-- controllers.py
				 |-- models.py
				 |-- forms.py
			 |-- /admin                     # Our first module, mod_auth
				 |-- __init__.py            #local blueprints
				 |-- controllers.py
				 |-- models.py
				 |-- forms.py

			 |-- /site
				 |-- __init__.py            #local blueprints
				 |-- controllers.py
				 |-- models.py
				 |-- forms.py

			 |-- /errors
				 |-- __init__.py            #local blueprints
				 |-- controllers.py         #all about functions

			 |__ /templates
				 |__ /errors
					|-- 404.html
				 |__ /auth
					 |-- signin.html
					 |-- register.html
				 |-- base.html
				 |__ /admin
					 |-- base.html
				 |__ /site
					 |-- index.html

			 |__ /static
