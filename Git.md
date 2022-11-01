# ¿Cómo es el flujo de Git?

## Archivos y Estados de Archivos

### Unstages
Cambios sin llevar a stage.
Basta con hacer un cambio en algún archivo para crearlo.


### Stages
Cambios en stages, esperando por ser llevados a un commit.
Hay que añadirlo al stage con el comando git add.

Puede ser
```bash
git add . # Para todos los archivos unstages
git add nombre.archivo # Para un archivo en específico
git add folder/ # Para todos los archivos dentro de una carpeta específica.
```

### Stash
Puedes aprenderlo luego.

## Commits
Cambios registrados en la rama.
Necesita tener cambios en stage para crear un commit.

```bash
git commit -m "type: Description or Title"
```

## Branches
Secciones específicas del proyecto que contienen varios commits.

Se pueden crear cuantas quieras con el nombre que quieras, pero es mejor siempre mantener una clasificación en tus ramas, por ejemplo, yo utilizo los prefijos:

```
bugfix/branch-name
feature/branch-name
perf/branch-name
```

## ¿Cómo saber en qué rama estamos ubicados?

```bash
git branch
```

La rama en verde es en la que estás ubicado.

## ¿Cómo cambiar el nombre de mi rama?

```bash
git switch master # Ubicarse en la rama master.
git branch -M main # Cambiar el nombre de la rama a main.
```

## ¿Cómo subir mis commits al repositorio?

```bash
git push -u origin main # Para la primera vez.
git push origin branch-name # Para las siguientes veces.
```

## ¿Cómo recibo los cambios de mis compañeros?

### Para recibir las ramas creadas o eliminadas por tus compañeros.

```bash
git fetch -p # Trae todas las ramas que no tengas.
```

### Para recibir los cambios de una rama.

```bash
git pull origin main
```
