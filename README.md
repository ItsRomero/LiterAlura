<h1>:books: LiterAlura :books:</h1>  

# 📛 Insignias  

<div align="center">  
    <img src="https://img.shields.io/badge/Estado-Concluido-green">  
    <img src="https://img.shields.io/badge/Java-v17-blue">  
    <img src="https://img.shields.io/badge/Base%20de%20Datos-PostgreSQL-blue">  
    <img src="https://img.shields.io/badge/Framework-Spring%20Boot-blue">  
    <img src="https://img.shields.io/badge/Versión-v1.0.0-green">  
</div>  

# 📋 Índice  

- [📛 Insignias](#📛-insignias)  
- [📖 Descripción del proyecto](#📖-descripción-del-proyecto)  
- [✅ Estado del proyecto](#✅-estado-del-proyecto)  
- [🚀 Demostración de funcionalidades](#🚀-demostración-de-funcionalidades)  
    - [🔧 Funcionalidades del proyecto](#🔧-funcionalidades-del-proyecto)  
    - [📂 Uso del proyecto](#📂-uso-del-proyecto)  
- [🛠️ Tecnologías utilizadas](#🛠️-tecnologías-utilizadas)  

# 📖 Descripción del proyecto  

¡Bienvenido/a a **LiterAlura**! Esta es una aplicación en consola que permite explorar y gestionar información sobre libros y autores utilizando la API **Gutendex**. Ofrece funcionalidades como:  

- Buscar un libro ingresando su título, registrando automáticamente su información y la del autor en la base de datos.  
- Listar libros y autores registrados.  
- Consultar autores vivos en un año específico.  
- Filtrar libros según su idioma.  

Adicionalmente, cuenta con funciones para generar estadísticas sobre libros registrados, listar los 10 libros más descargados y buscar autores por nombre. Diseñada para facilitar la interacción con datos literarios, LiterAlura es ideal para explorar y analizar información de manera sencilla y práctica.  

# ✅ Estado del proyecto  

¡Proyecto completado y funcional! 🎉  

# 🚀 Demostración de funcionalidades  

## 🔧 Funcionalidades del proyecto  

1️⃣ **Conexión con la API Gutendex**  
   - Obtiene información detallada de libros y autores.  

2️⃣ **Opciones del menú principal:**  
   - Buscar un libro por título.  
   - Listar libros registrados.  
   - Listar autores registrados.  
   - Consultar autores vivos en un año.  
   - Filtrar libros por idioma.  
   - Estadísticas de descargas.  
   - Top 10 libros más descargados.  
   - Buscar autores por nombre.  
   - Salir (cerrar la aplicación).  

3️⃣ **Búsqueda y registro de libros:**  
   - Busca un libro ingresando el título (completo o parcial), muestra la información encontrada y registra los datos en la base de datos.  

4️⃣ **Estadísticas y Top 10:**  
   - Calcula descargas promedio, máximas y mínimas.  
   - Muestra el Top 10 libros más descargados.  

5️⃣ **Búsqueda de autores por nombre:**  
   - Encuentra autores por nombre completo o parcial y lista sus libros asociados.  

## 📂 Uso del proyecto  

1️⃣ **Configuración previa**  
   - Edita el archivo `application.properties` para configurar tu base de datos. Reemplaza las variables:  
     - `${DB_HOST}`  
     - `${DB_NAME}`  
     - `${DB_USER}`  
     - `${DB_PASSWORD}`  

2️⃣ **Ejecuta la aplicación**  
   - Al iniciar, verás un menú con opciones numeradas.  
   - Selecciona ingresando el número correspondiente.  

3️⃣ **Ejemplo de opciones:**  
   - **Buscar un libro:** Ingresa el título, y si no está registrado, se buscará en la API Gutendex.  
   - **Listar libros y autores:** Muestra todos los datos almacenados en la base de datos.  
   - **Filtrar por idioma:** Selecciona un código abreviado como `es` para español o `en` para inglés.  
   - **Estadísticas y Top 10:** Visualiza datos como descargas promedio o el ranking de libros más descargados.  
   - **Autores vivos en un año:** Ingresa un año y consulta los autores vivos en esa época.  

🎉 ¡Disfruta explorando datos literarios con LiterAlura! 