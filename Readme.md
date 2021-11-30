## After de GIT

### Para descargar e instalar git podemos visitar [este enlace](https://git-scm.com/downloads)

#### Una vez descargamos e instalamos Git, lo siguiente es registrar el usuario con el que queremos trabajar.

#### Para esto abrimos la consola de comandos bash y ejecutamos el siguiente comando: `git config --global user.name "Nombre"` y luego con el comando: `git config --global user.email "Su correo"`, se ejecuta con --global para no tener que escribir el comando en cada una de las carpetas de nuestro computador.

#### Luego podemos verificar que se haya registrado correctamente: `git config --list`

#### Una vez resgistrados, creamos la carpeta en algun lugar de nuestra computadora para comenzar con el versionado.

# Tenemos que estar 100% seguros de que el directorio de trabajo está en la carpeta correcta.

#### Una vez creada la carpeta, podemos empezar a trabajar con el comando `git init`

#### Este comando nos crea un archivo `.git` en la carpeta que estamos trabajando. Por lo general no lo podemos ver porque es un archivo oculto.

#### Una vez creado el archivo `.git`, podemos empezar a trabajar con el comando `git add` y agregar los archivos que queremos versionar. Podemos agregar todos los archivos que queremos versionar con el comando `git add .` o bien podemos agregar uno o varios archivos con el comando `git add file1.txt file2.txt`

#### Una vez agregados los archivos, podemos hacer un `git status` para verificar que los archivos están correctamente agregados.

#### Luego podemos hacer un `git commit -m "primer commit"` para registrar el cambio.

#### Una vez registrado el cambio, podemos hacer un `git status` para verificar que el cambio se ha registrado correctamente.

#### Podemos visualizar el historial de cambios con el comando `git log`.

#### Creamos una segunda rama con el comando `git branch segunda-rama`.

#### Con el comando `git branch -l` podemos ver las ramas que tenemos.

#### Con el comando `git checkout segunda-rama` podemos cambiar de rama.

#### Con el comando `git merge master` podemos unir la rama master con la rama segunda-rama.

#### Si queremos volver a un commit en particular, podemos hacer un `git checkout id-commit `
