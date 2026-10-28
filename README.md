# 🛒 CRUD de Productos - Laravel & Bootstrap

> Proyecto desarrollado para la gestión de productos, implementando el patrón Arquitectónico MVC (Modelo-Vista-Controlador) con Laravel, MySQL y Bootstrap 5.

---

## 🛠️ Tecnologías y Herramientas

<p>
  <img src="https://img.shields.io/badge/PHP-8.3-%23777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/Laravel-13-%23FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Bootstrap-5-%237952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>

---

## 📸 Vistas Previas del Sistema

| Pantalla Inicial / Listado | Formulario de Creación |
| :---: | :---: |
| ![Inicio del CRUD](img\CRUD_laravel_inicio.png) | ![Creación de Producto](img\CRUD_laravel_formulario.png) |
| *Listado general de los registros almacenados en base de datos.* | *Interfaz limpia con Bootstrap para la inserción de nuevos productos.* |

---

## ⚙️ Guía de Instalación Local

Sigue estos pasos para clonar y poner en marcha este proyecto en tu entorno local (WampServer / XAMPP):

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/crud-laravel-laboratorio.git
   ```

2. **Entrar al directorio del proyecto:**
   ```bash
   cd crud_rapido
   ```

3. **Instalar dependencias de PHP:**
   ```bash
   composer install
   ```

4. **Configurar el entorno:**
   * Copia el archivo `.env.example` y nómbralo `.env`.
   * Configura las credenciales de tu base de datos local:
     ```env
     DB_CONNECTION=mysql
     DB_HOST=127.0.0.1
     DB_PORT=3306
     DB_DATABASE=crud_rapido
     DB_USERNAME=root
     DB_PASSWORD=
     ```

5. **Ejecutar migraciones:**
   ```bash
   php artisan migrate
   ```

6. **Iniciar el servidor de desarrollo:**
   ```bash
   php artisan serve
   ```

7. **Abrir en el navegador:**
   Ingresa a [http://127.0.0.1:8000/products](http://127.0.0.1:8000/products) para ver el sistema en funcionamiento.

---

## 🔄 Flujo para actualizar el repositorio en GitHub

Para subir cualquier cambio futuro en tu código o documentación, ejecuta:

```bash
git status
git add .
git commit -m "Actualización de documentación y archivos del repositorio"
git push origin main
```