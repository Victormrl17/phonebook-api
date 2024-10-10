# API RESTful de Agenda Telefónica

Este proyecto es una API RESTful creada con **Node.js** y **Express** para gestionar una agenda telefónica. La API permite:

- Listar todos los contactos.
- Obtener un contacto específico por ID.
- Eliminar contactos.
- Agregar nuevos contactos con validaciones.

## Tecnologías utilizadas:

- **Express**: Framework web para Node.js.
- **Morgan**: Middleware para el registro de solicitudes HTTP.
- **Cors**: Middleware para habilitar solicitudes CORS.

## Comandos:

- `npm start`: Inicia el servidor en el puerto 3001.
- `npm run dev`: Inicia el servidor con nodemon para reiniciar automáticamente en cada cambio.

## Rutas disponibles:

- `GET /api/persons`: Retorna todos los contactos.
- `GET /api/persons/:id`: Retorna un contacto por ID.
- `POST /api/persons`: Agrega un nuevo contacto.
- `DELETE /api/persons/:id`: Elimina un contacto por ID.
- `GET /info`: Muestra la cantidad de contactos y la fecha actual.
