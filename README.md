## Ejercicio 1
### Clonacion



```
git clone enlace
```

### Creacion de fichero y zona de intercambio temporal

```
sudo nano .txt

git add .

git commit -m "MensajeCommit"
```

### Ramas 
```
git branch nombreRama

```
#### Cambiar Rama
```
git checkout nombreRama
```

### Comprobacion de la rama actual
```
git branch -v
```


### Fusion de Rama
IMPORTANTE: estar en la rama principal
```
git merge nombreRama
```

### Historial

```
git log

git log --graph --all
```

### Estado del Repositorio

```
git status
```

## VSCODE

### Crear y cambiar rama
En branches, con el repositorio señalado, se le da al + que aparece a la derecha de branches.

Y para cambiar de rama, en Branches, selecciona el repositorio, se abre y la rama que queremos cambiar se le da boton derecho y Switch branch u otra manera es abajo a la izquierda donde aparece main se le da y se selecciona la rama

### Fusionar ramas

En la categoria BRANCHES, se le da a la rama que se quiere fusionar, boton derecho y la opcion merge into (segunda Opcion).

### Añadir cambios y confirmar
En source control, en el repositorio al haber cambios se le da al + que aparece y luego se hace un commit con un mensaje.

### Publicar 
En source control despues del commit aparece la opcion Publish Branch

### Actualizar
En source control, al realizar cambios despues de publicar y hacer el añadido de los cambios en la zona temporal y el commit, aparecera la opcion de sync change