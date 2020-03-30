# ProyectoFinal-McDonald-s
Proyecto Final de Programación con interfaz Gráfica 
Realizado por Marifel Vanessa C.I:27.659.619  Angel Romero C.I:28.278.045 David Moro C.I:28.189.215

------------------------------------------------------------------------------------------------------
  Se buscaba realizar un programa mediante interfaz gráfica que permitiera el registro de dos usuarios distintos, donde dichos usuarios cumplieran diferentes funciones. Debido a esto se ha decido trabajar con la liberia de python tkinter (GUI) libreia que permite trabajar interfacez gráficas. Debido a que se utilizado una base de datos se tuvo que importa las libreia sqlite3 



  El programa consiste en una base de datos para McDonald's que le permita al usuario ver la comida que ofrece o está disponible, el programa puede ser utilizado tanto por compradores como también por el administrador o empleados del sitio, dándole funciones al administrador de modificar, agregar y eliminar toda la mercancía o productos que se encuentran disponibles para la venta.

Modulos que conforma el programa:

* Menú principal: Este es el principal del programa, en este módulo el usuario se registra, inicia sesión o puede leer la información del lugar, además de que es el centro para llevarlos a los otros módulos

* Menú de administrador/editar: En este módulo el administrador podrá observar los productos disponibles en la base de datos, además de agregar, eliminar, y modificar la mercancía.

* Menú de cliente: este módulo permite al cliente luego de introducir su nombre de usuario y su contraseña ver la lista de mercancía disponible y su precio.

* Información: Acá se muestra la información del lugar, en donde se ubica y sus redes sociales.

  Para ingresar en el menú de cliente, se debe registrar, poner un nombre de usuario y su contraseña, al hacer esto sus datos serán guardados en un archivo y podrá iniciar sesión.

  Para ingresar al menú de administrador debe iniciar sesión con la contraseña "admin" y el usuario "admin" en minúsculasEl programa consiste en una base de datos para McDonald's que le permita al usuario ver la comida que ofrece o está disponible, el programa puede ser utilizado tanto por compradores como también por el administrador o empleados del sitio, dándole funciones al administrador de modificar, agregar y eliminar toda la mercancía o productos que se encuentran disponibles para la venta.

  Se crearon dos metodos que poseian Dos ventanas diferentes una que entra al usuario comun al menu del Mcdonald´s y otra que llevaba al usuario administrador al Registro de Comida creado con mediante una base de datos, el usario y clave para poder acceder a dicha funcion fueron establecidos como "admin". A su vez si un usuario se registra esta se guardara en un archivo de texto donde reflera todos los usuarios guardados que se hayan establecido.
  Para correr el Programa se ha Establecido un archivo principal llamado main.py utilizandose un  import subprocess para la union del programa.  

  
