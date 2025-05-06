# 📚 Sistema de Gestión de Biblioteca Escolar

## 🧑‍💻 Descripción General

Esta es una aplicación web desarrollada en **PHP y HTML** que permite registrar y visualizar libros en una biblioteca escolar. Fue creada como parte del proyecto académico del curso, y utiliza sesiones para almacenar temporalmente la información sin necesidad de base de datos.

## 🛠️ Funcionalidades Implementadas

1. **Formulario de Registro de Libros**
   - Permite ingresar: título, autor, ISBN y cantidad disponible.
   - Valida que el ISBN no se repita.
   - Impide registros con campos vacíos o cantidades inválidas.

2. **Visualización de Libros Registrados**
   - Muestra en pantalla todos los libros que han sido registrados.
   - Utiliza sesiones (`$_SESSION`) para mantener la información mientras el navegador esté abierto.

3. **Separación de Archivos**
   - `index.html`: página principal de navegación.
   - `formulario.html`: formulario para ingresar libros.
   - `procesar.php`: script que recibe, valida y muestra los libros.

## 💡 Tecnologías Usadas

- **HTML5**: para el diseño de los formularios y la estructura visual.
- **PHP**: para el procesamiento del formulario, validación de datos y gestión de sesiones.
- **CSS básico (opcional)**: para una mejor presentación visual.

## 🚀 Cómo Usar la Aplicación

1. Clona o descarga el proyecto en tu servidor local (XAMPP, Laragon, etc.).
2. Coloca los archivos en una carpeta dentro de `htdocs` o `www`.
3. Abre tu navegador y visita:  
   `http://localhost/nombre_carpeta/index.html`
4. Usa el menú para:
   - Registrar un nuevo libro.
   - Ver los libros registrados.

## 📌 Notas

- Esta versión **no utiliza base de datos**, por lo que la información se borra al cerrar el navegador o sesión.
- Se puede ampliar en futuras versiones para incluir funciones como **editar, eliminar libros o prestar ejemplares**.

## 👨‍🎓 Autor

- **Sebastián**  
- Proyecto académico — Ingeniería en Sistemas  
- Entrega: Primera parte (gestión básica de libros)
"""
