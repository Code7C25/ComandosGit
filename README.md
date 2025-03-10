# 10 Comandos de Git Que Todo Desarrollador Debería Saber

Git es esencial para cualquier desarrollador, especialmente en equipos. Aquí te comparto 10 comandos fundamentales que deberías conocer para trabajar eficientemente con Git.

## 1. git clone

Clona un repositorio remoto y lo copia en tu máquina local.  
```bash
git clone https://link-con-nombre-del-repositorio
```  
**Ejemplo:**  
```bash
git clone https://github.com/usuario/proyecto.git
```

## 2. git branch

Crea, lista o elimina ramas.  
- Crear una nueva rama:  
  ```bash
  git branch nombre-de-la-rama
  ```  
- Subir una nueva rama al remoto:  
  ```bash
  git push origin nombre-de-la-rama
  ```  
- Eliminar una rama:  
  ```bash
  git branch -d nombre-de-la-rama
  ```

## 3. git checkout

Cambia entre ramas o crea una nueva y muévete a ella.  
- Cambiar a una rama existente:  
  ```bash
  git checkout nombre-de-la-rama
  ```  
- Crear una nueva rama y cambiarte a ella:  
  ```bash
  git checkout -b nueva-rama
  ```

## 4. git status

Muestra el estado actual de los archivos y la rama.  
```bash
git status
```

## 5. git add

Prepara cambios para el próximo commit.  
- Añadir un archivo específico:  
  ```bash
  git add archivo
  ```  
- Añadir todos los archivos:  
  ```bash
  git add -A
  ```

## 6. git commit

Guarda los cambios localmente con un mensaje descriptivo.  
```bash
git commit -m "Descripción de los cambios"
```

## 7. git push

Sube tus cambios confirmados al repositorio remoto.  
```bash
git push origin nombre-de-la-rama
```  
Si es una rama nueva, usa:  
```bash
git push --set-upstream origin nombre-de-la-rama
```

## 8. git pull

Actualiza tu repositorio local con los últimos cambios del remoto.  
```bash
git pull origin nombre-de-la-rama
```

## 9. git revert

Deshace un commit sin eliminar el historial. Usa el hash del commit a revertir.  
- Revertir un commit:  
  ```bash
  git revert <hash-del-commit>
  ```

## 10. git merge

Fusiona una rama con la rama principal.  
- Cambiar a la rama principal (dev o master):  
  ```bash
  git checkout dev
  ```  
- Fusionar la rama de desarrollo:  
  ```bash
  git merge nombre-de-la-rama
  ```
