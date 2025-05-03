# ARE:TRUST Mock API

Este repositorio contiene la base de datos mock (db.json) para la tienda online de ARE:TRUST.

## Estructura de Datos

El archivo `db.json` contiene:

- `products`: Catálogo de productos (esmeraldas, joyas)
- `products_categories`: Lista de categorías disponibles
- `categories`: Detalles de cada categoría

## Uso con My JSON Server

Este repositorio está configurado para ser utilizado con [My JSON Server](https://my-json-server.typicode.com/) para proporcionar una API REST mock:
https://my-json-server.typicode.com/kvn3toj/aretrust-mock-api


Rutas disponibles:
- `/products` - Lista todos los productos
- `/products/:id` - Obtiene un producto específico por ID
- `/categories` - Lista todas las categorías
- `/categories/:id` - Obtiene una categoría específica por ID

## Notas

- Esta API mock es solo para GET requests
- Limitada a 10KB de tamaño por My JSON Server
- Para cambios en la estructura de datos, actualizar directamente el archivo db.json
