# Gestor de Libros para Biblioteca

Autor: Javier Ramírez
Fecha: marzo 2024
Versión: 1.0

## 0. Proyecto

Este proyecto incluye una plataforma de gestión de libros diseñada para una biblioteca. La aplicación web está construida utilizando el framework Django siguiendo el patrón Modelo-Vista-Templado (MVT).

## 1. Modelos

- **Libro**: Cada libro tiene un título, autor, género, año de publicación, ISBN y una sinopsis.
- **Autor**: Los autores tienen un nombre y una biografía. Pueden estar asociados con uno o más libros.
- **Género**: Los géneros representan las categorías a las que pertenecen los libros, como ficción, no ficción, ciencia ficción, etc.
- **Editoriales**: Las editoriales se componen de nombre, teléfono y sitio web.

## 2. Formularios

- **Formulario de ingreso de libros**: Permite a los administradores de la biblioteca agregar nuevos libros a la base de datos ingresando información como título, autor, género, año de publicación, ISBN y sinopsis.
- **Formulario de búsqueda de libros**: Los usuarios pueden buscar libros por título.
- **Formulario de registro**: Permite registrarse en la web. 
- **Formulario para editar perfil**: Permite modificar los datos asociados al perfil de los usuarios ya registrados. 
- **Formulario de cambio de avatar**: Permite actualizar el avatar de los usuarios ya registrados. 
- **Cambiar clave**: Permite actualizar la clave de un usuario concreto.
- **Formulario de búsqueda de libros**: Muestra los resultados de la búsqueda de libros basados en los criterios especificados por el usuario.
- **Formulario de ingreso de libros**: Formulario para que los administradores ingresen nuevos libros a la base de datos.
- **Formulario de ingreso de autores**: Formulario para que los administradores ingresen nuevos autores a la base de datos.
- **Formulario de ingreso de géneros**: Formulario para que los administradores ingresen nuevos géneros a la base de datos.
- **Formulario de ingreso de editoriales**: Formulario para que los administradores ingresen nuevas editoriales a la base de datos.

## 3. Vistas

- **Página de inicio (index)**: Página de inicio de la biblioteca. Permite acceder a las distintas secciones y formularios.
- **Página de libros**: Muestra información detallada sobre los libros registrados, incluyendo título, autor, género, año de publicación e ISBN.
- **Página de autores**: Muestra una lista de todos los autores en la base de datos.
- **Página de géneros**: Muestra una lista de todos los géneros en la base de datos.
- **Acerca de**: Contiene información del autor de la web.
- **Formulario de registro**: Permite registrarse en la web. 
- **Formulario para editar perfil**: Permite modificar los datos asociados al perfil de los usuarios ya registrados. 
- **Formulario de cambio de avatar**: Permite actualizar el avatar de los usuarios ya registrados. 
- **Cambiar clave**: Permite actualizar la clave de un usuario concreto.
- **Formulario de búsqueda de libros**: Muestra los resultados de la búsqueda de libros basados en los criterios especificados por el usuario.
- **Formulario de ingreso de libros**: Formulario para que los administradores ingresen nuevos libros a la base de datos.
- **Formulario de ingreso de autores**: Formulario para que los administradores ingresen nuevos autores a la base de datos.
- **Formulario de ingreso de géneros**: Formulario para que los administradores ingresen nuevos géneros a la base de datos.
- **Formulario de ingreso de editoriales**: Formulario para que los administradores ingresen nuevas editoriales a la base de datos.

## 4. Acceso al panel de administración:

- usuario: admin
- clave: 1234
