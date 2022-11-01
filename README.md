# CRUD Learn

## API de este CRUD

Todas las rutas deben empezar por /api/v1/.

- get (GET)
  Debe entregar todos los documentos de tareas.
- get/:id (GET)
  Debe entregar un documento conforme al id enviado por parámetro de ruta.
- create (POST)
  Crear un documento.
- update (PUT)
  Actualizar un documento
- remove/:id (DELETE)
  Eliminar un documento con el id enviado por parámetro de ruta.

## En este proyecto utilizamos Commits Convencionales

[Conventionals Commits](https://www.conventionalcommits.org/en/v1.0.0/)

### Tipos de commits

build: Cambios en el proyecto, dependencias, configuraciones...
feat: Nueva feature.
fix: Reparación de un bug.
docs: Documentación, como README, CHANGELOG...
style: Mejora del código siguiendo reglas de un Linter, sin cambiar el funcionamiento.
