Te Lo Vendo

	Te Lo Vendo es una página de comercio electrónico, en su barra de navegación cuenta con una pestaña de “Categorías” en la que encontraras todo lo que necesitas. También tiene una sección de “Registro” para nuevos usuarios y otra de “Inicio de Sesión”
Funcionalidades principales
•	Registro y autenticación de usuarios: Los usuarios pueden registrarse en la plataforma para acceder a funcionalidades personalizadas, como ver su historial de compras y ventas, guardar productos en su lista de deseos y realizar seguimiento de pedidos.
•	Listado de productos: Los vendedores pueden crear y administrar listados de productos. Pueden proporcionar detalles del producto, imágenes, precios y cantidades disponibles.
La página esta creada con Python y usando el framework Django. 
Para poder levantar la aplicación en un servidor local:
Requisitos previos: Asegúrate de tener Python y Django instalados en tu sistema.
	Creación del ambiente virtual: python -m venv “nombre de tu ambiente virtual”
	Instalación de Django por consola: pip install django
Crear un super usuario: Debes crear un super usuario siguiendo las indicaciones que aparezcan al ejecutar la siguiente línea en tu consola
	python manage.py createsuperuser
Ejecutar el servidor local: Inicia un servidor local de desarrollo con el siguiente comando:
	Python manage.py runserver
Acceder a la aplicación: Puedes acceder a la aplicación con el link que sale an la consola después de iniciar el servidor, o ir a tu navegador e ingresar ‘http://localhost:8000/index’ en la sección de la url
Panel de administración: Puedes gestionar el sitio desde el panel de administración ingresando por la ruta `http://localhost:8000/admin` y luego usando las credenciales del super usuario que creaste anteriormente.

Y ya estas listo para probar  todas las funcionalidades que te ofrece “Te Lo Vendo”

