# Comandos básicos de Git

## 1️⃣ Transforma el directorio actual en un repositorio de Git
Se añade un subdirectorio de `.git` con todos los archivos necesarios del repositorio.
```bash
git init
```

---

## 2️⃣ Especifica qué archivos quieres añadir al repositorio (a staging area, staged)
Prepara los archivos modificados.
```bash
git add <archivo>
```

Para añadir todos los archivos modificados:
```bash
git add .
```

---

## 3️⃣ Confirma los cambios (a directorio git, committed)
```bash
git commit -m "Mensaje del commit"
```

---

## 4️⃣ Clona un repositorio existente
```bash
git clone <URL-del-repositorio>
```

---

## 5️⃣ Muestra el estado de los archivos
```bash
git status
```

---

## 6️⃣ Muestra estado abreviado
```bash
git status -s
```

---

## 7️⃣ Ignora archivos
Crea un archivo llamado `.gitignore` e incluye dentro los nombres o patrones de archivos que no quieras rastrear.

Ejemplo:
```
*.log
node_modules/
.DS_Store
```

---

## 8️⃣ Mostrar los cambios: líneas exactas que fueron añadidas y eliminadas  
Compara lo que tienes en tu directorio de trabajo con lo que está en el área de preparación.
```bash
git diff
```

---

## 9️⃣ Mostrar los cambios: líneas exactas que fueron añadidas y eliminadas  
Compara tus cambios **preparados** con la última instantánea confirmada.
```bash
git diff --staged
```

---

## 🔟 Confirma los cambios sin pasar por el área de preparación (directamente al repositorio)
```bash
git commit -a -m "Mensaje del commit"
```

---

## 11️⃣ Eliminar archivos del directorio de trabajo y del área de preparación
```bash
git rm <archivo>
```

---

## 12️⃣ Renombrar archivos del directorio de trabajo y del área de preparación
```bash
git mv <nombre-antiguo> <nombre-nuevo>
```

---

## 13️⃣ Muestra el historial de confirmaciones
```bash
git log
```

---

## 14️⃣ Muestra sólo las dos últimas confirmaciones indicando las diferencias introducidas en cada una
```bash
git log -p -2
```

---

## 15️⃣ Rectifica el último commit
```bash
git commit --amend
```
"# CurroPG" 
