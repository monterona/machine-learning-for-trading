1. Para trabajar normalmente:
Abres VS Code, trabajas en monterona y guardas tus cambios:
```
git add .
git commit -m "Mis ejercicios"
git push
```
2. Cuando quieras recibir las actualizaciones del autor:
Con tus cambios guardados en commits, ejecutas desde el directorio del repositorio:
```
git fetch origin
git switch main
git pull --ff-only
git switch monterona
git merge main
```
Y listo. Si aparecen conflictos, VS Code te ayudará a resolverlos.
