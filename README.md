# ReciclaTech · Node.js

Aplicación web para gestionar materiales reciclables, inventario y ventas, con estadísticas y generación de reportes PDF.

Esta implementación utiliza **Node.js, Express y SQLite**. La implementación con PHP y MySQL se encuentra en [ReciclaTech](https://github.com/Andres76798/ReciclaTech).

## Funcionalidades

- Registro, consulta, edición y eliminación de materiales.
- Consulta del peso total disponible en inventario.
- Registro, edición y eliminación de ventas.
- Resumen de ingresos y estadísticas por material.
- Exportación de reportes de ventas a PDF con PDFKit.

## Ejecución local

Necesitas Node.js y npm.

```bash
git clone https://github.com/Andres76798/ReciclaTech11.git
cd ReciclaTech11
npm install
npm start
```

Abre `http://localhost:3000/`. El servidor está configurado para escuchar en el puerto 3000.

## Estructura

| Ruta | Contenido |
| --- | --- |
| `server.js` | Servidor Express y rutas de la API |
| `db.js` | Acceso y configuración de SQLite |
| `public/` | Interfaz web y recursos estáticos |
| `reportes/` | Reportes PDF generados |
| `database.db` | Archivo de base de datos SQLite |

## Notas de desarrollo

- El comando `npm test` es un marcador de posición; todavía no hay una suite de pruebas configurada.
- El repositorio incluye una base SQLite. Para pruebas locales, utiliza datos de ejemplo y conserva una copia antes de modificarla.
