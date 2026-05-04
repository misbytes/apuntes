## Comandos git

- Inicializar repositorio local:
```bash
git init
```

- Agrega los cambios a staging area en local:
```bash
git add .
```

- Commit de los cambios en local:
```bash
git commit -m 'mensaje para el commit'
```
	
- Configuracion de username:
```bash
git config user.name usernamex
```

- Configuracion de mail:
```bash
git config user.email user@mail.com
```

- Almacenamiento de credenciales en local:
```bash
git config --global credential.helper store
```

- Se realiza el pase a master o main en Github:
```bash
git push -u origin master
```

- Sirve para renombrar la rama principal a main (antes se llamaba master y puede traer conflictos). Lo mejor es llamarlo igual que como figura en el repositorio definitivo (En este caso github):
```bash
git branch -m main
```
	
- Muestra en una línea los commit realizados (con esto veo el id de la version):
```bash
git log --oneline
```


