# 📚 Biblioteca - Spring Boot

¡Bienvenido al proyecto **Biblioteca**! 🎉

Este es un proyecto desarrollado con **Spring Boot** que permite gestionar una biblioteca de manera sencilla y eficiente. Puedes crear y administrar libros, autores, editoriales y usuarios, cada uno con funcionalidades específicas.

---

## 🚀 **Características principales**

✅ **Libros:**  
- Crear nuevos libros con sus respectivos datos.  
- Listar los libros disponibles.  

✅ **Autores:**  
- Crear autores.  
- Listar los autores registrados.  

✅ **Editoriales:**  
- Crear editoriales.  
- Listar las editoriales registradas.  

✅ **Usuarios:**  
- Registrar nuevos usuarios con roles definidos (Administrador/Usuario).  
- Asignar contraseña y foto de perfil para la autenticación.  

---

## 🛠️ **Tecnologías utilizadas**

- **Java** (JDK 17)
- **Spring Boot** (Spring Data JPA, Spring Security, Spring Web)
- **Thymeleaf** (para la vista)
- **MySQL** (base de datos relacional)
- **Maven** (gestión de dependencias)
- **Lombok** (para simplificar código)
- **Bootstrap** (para estilizar la interfaz)

---

## ⚙️ **Instalación y configuración**

1️⃣ **Clonar el repositorio:**
```bash
   git clone https://github.com/EstefanyRamirez08/Biblioteca.git
```

2️⃣ **Configurar la base de datos:**  
En el archivo `src/main/resources/application.properties`:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/biblioteca
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
spring.jpa.hibernate.ddl-auto=update
```

3️⃣ **Ejecutar la aplicación:**
```bash
   mvn spring-boot:run
```

---

## 🔒 **Roles de usuario**

- **Administrador:** Puede gestionar libros, autores, editoriales y usuarios.  
- **Usuario normal:** Solo puede consultar la lista de libros disponibles.

---

## 🖼️ **Capturas de pantalla**

📌 **Pantalla de inicio de sesión:**
![Login](https://via.placeholder.com/600x300)

📌 **Listado de libros:**
![Libros](https://via.placeholder.com/600x300)

---

## 📩 **Contacto**

Creado por **Estefany Ramírez** ✨  
📧 **Correo:** estefanyramirez1@gmail.com  
🔗 **GitHub:** [EstefanyRamirez08](https://github.com/EstefanyRamirez08)  

¡Espero que disfrutes el proyecto! 🚀✨

