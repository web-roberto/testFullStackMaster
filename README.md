# subir a una rama ya existente (del FTM por ejemplo)
git remote add origin https://github.com/web-roberto/testFullStackMaster.git
git branch -M main
git push -u origin main
## subir segundas veces al repositorio
add .
git commit -m "nombre"
git push
# para bajar de la rama a mi directorio
git pull
# git commit -m "feat: add backend first version"
# Descargar a local una rama remota que no es la principal
git checkout --track -b rama-remota origin/rama-remota


