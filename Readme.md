# 🛒 Proyecto: Tienda de Productos - Subida de Archivos

## 📄 Descripción
**Este proyecto consiste en la creación de un servidor básico para una tienda de productos que permite a los empleados agregar nuevos productos y adjuntar una imagen. La imagen se guarda en el servidor local y la información del producto se almacena temporalmente en un array de objetos en memoria.**

El servidor está implementado con **Express.js** y utiliza **Multer** para gestionar la subida de archivos.

## ✨ Características principales
- **Creación de productos**: Los productos se crean mediante un endpoint que acepta campos como nombre, descripción, precio e imagen.
- **Subida de imágenes**: Las imágenes se almacenan en una carpeta del servidor local, generando una URL que apunta a su ubicación.
- **Almacenamiento temporal**: Los productos se almacenan en un array de objetos en memoria.

## 🛠️ Configuración y tecnologías usadas
- **Express.js**: Para crear el servidor y gestionar las rutas.
- **Multer**: Para manejar la subida de archivos.
- **Node.js**: Como entorno de ejecución.

## 📬 Endpoints

### POST /products
Este endpoint permite la creación de un nuevo producto. Acepta los siguientes campos:

- **name** (string): Nombre del producto.
- **description** (string): Descripción del producto.
- **price** (number): Precio del producto.
- **image** (archivo): Imagen del producto (jpg, png).

#### 
```json
{
  "id": "string",
  "name": "string",
  "description": "string",
  "price": "number",
  "imageUrl": "string"
}
```

   ```js
   git clonehttps://github.com/Emiliojoa/SubirOtroArchivos.git
   ```

   **Instala las dependencias**

         NPM I 
 


