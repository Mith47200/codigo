# Primer día con Git y Github

Lista de comandos de git

* Para poder ver la version de Git

```bash
git --version
```

* Para configurar el correo
```bash
git config --global user.email "email"
```

* Para poder configurar el username
```bash
git config --global user.name "username"
```

* Para poder empezar a usar el control de versiones en nuestra carpeta (solo una vez por carpeta)
```bash
git init
```

* Para ver el estado de nuestros cambios
```bash
git status
```

* Agregar los archivos a la memoria de la pc
```bash
git commit -m "commit"
```


* Crea los registros de los cambios realizados
```bash
git commit -m "commit"
```

* Ver historial de commits, Git log retorna un id, para poder ver los cambios realizados en ese commit
```bash
git log
```
* Para ver esos cambios
```bash
git show (id commit)
```

* Para cambiar el nombre de owner
```bash
git branch -M nuevo nombre
```

* Para subir los cambios a Github
```bash
git push origin main
```

