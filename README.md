Informe
==========


Aplicación web creada para la consulta de base de datos de la droguería FarmaSoft.

FLUJO DEL PROGRAMA:
-------------------
El sistema cuenta con una página inicio y un menú para acceder a la cuenta o la creación del mismo. Una vez ingresado, el usuario tiene la posibilidad de cambiar su contraseña desde su perfil y la posibilidad de cerrar sesión. atreves del menú podrás acceder y hacer diferentes consultas al sistema y visualizar la base de datos de la empresa.

ESTRUCTURA DE LA INFORMACION:
-----------------------------
Consta de dos archivos CSV en donde contiene los datos de la base de datos y los nombres de usuarios con sus respectivas contraseñas.
La aplicación consta de distintos archivos .py (app.py, archivo.py, forms.py pruebas.py), en la carpeta templates están contenidos los archivos .html (para la visualización del programa) y dentro de la carpeta static que contiene la hoja de estilo.

UTILIZACION EL PROGRAMA:
------------------------
Atreves de la página de inicio el usuario se puede logearse (Ingresar) o si no tiene cuenta, puede crear uno (Registrarse), las opciones son visibles desde el menú superior.
Una vez que allá accedido se redirecciona a nueva página, en esta se visualizará otro menú, en donde el usuario podrá realizar distintas consultas.
Las consultas le permitirán al usuario a visualizar la base de datos de la empresa, hacer búsqueda de clientes por productos, búsqueda de productos por clientes, ver los mejores clientes y los productos más vendidos.
Se ha actualizado una nueva funcionalidad, ahora todas las consultas inclusive la base de datos de la empresa pueden ser descargados, con la extensión .csv, se guardara como (Resultados_Y-M-D_H:M:S)
Actualización del menú superior tiene la opción de entrar en su perfil, para realizar cambios en su información personal, en este caso cambiar la contraseña de su cuenta usuario.
El programa también cuenta con la opción de salir del sistema.


CLASES UTILIZADAS:
------------------
En el programa se utilizan siete clases; dos clases son utilizadas para el login (RegistrarForm) y registración del usuario (LoginForm), dos clases para la búsqueda de clientes (Consulta_Cliente) y búsqueda de productos (Consulta_Producto), dos clases para la excepción (CSVError) y para validar los errores del archivo (validarCSV) y una clase para cambiar la contraseña de la cuenta usuario (Nueva_Contraseña).


