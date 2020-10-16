### Configurar nombre y email del usuario

    $ git config --global user.name "Luis J. Rodriguez O."
    $ git config --global user.email "ljavierrodriguez@gmail.com"

### Crear un repositorio de git

    $ git init

### Configurar nombre y email para un proyecto particular

    $ git config user.name "Luis J. Rodriguez O."
    $ git config user.email "lrodriguez@4geeks.co"

### Saber el status de mi repositorio git

    $ git status

### Preparar archivos a guardar 

    $ git add -A
    $ git add .
    $ git add *
    $ git add <filename>

### Guardar archivos en el repositorio local

    $ git commit -m "Mensaje o Description de la tareas o modificaciones hechas"


### Restaurar Cambios hechos a un estado anterior

    $ git restore <filename>
    $ git checkout <filename>

### Listar commits hechos

    $ git log

### Regresar a un commit anterior

    $ git chekout <hash>

### Crear una nueva rama (branch)

    $ git branch <branch-name>

### Activar rama (branch)

    $ git checkout <branch-name>

### Unir cambios en ramas

    $ git merge <branch-origen> <branch-destino>