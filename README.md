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
# versiones
git add .
git  tag v1.0.0 
o git tag 
git commit -m "v1.0.0"
git push origin numero-versión

# Crear una rama 'backend' en Github manualmente
estar yo en mi rama 'backend' local. hacer git push -u origin backend -> subo de mi rama backend (mi ultimo commit que puede ser la versión 2) al backend remoto
git push -u origin backend -> subimos del mi rama actual y commit actual a la rama 'backend'.
git push (para segundas veces o mas )

# version 2 del backend



