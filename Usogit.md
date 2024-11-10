# Guía Completa de Uso Básico de Git

Esta guía proporciona una referencia rápida para los comandos esenciales de Git. Sigue estos pasos para configurar, gestionar y colaborar en repositorios Git.

---

## 1. Configuración Inicial

Antes de comenzar, configura tu nombre de usuario y correo electrónico (estos datos se almacenarán en cada commit).

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu_email@example.com"
```

Para verificar la configuración actual:

```bash
git config --list
```

---

## 2. Crear un Repositorio

Para iniciar un repositorio nuevo en el directorio actual:

```bash
git init
```

O, para clonar un repositorio existente desde una URL:

```bash
git clone <URL_DEL_REPOSITORIO>
```

---

## 3. Agregar y Guardar Cambios

Para ver el estado actual de los archivos (cuáles han sido modificados, añadidos, etc.):

```bash
git status
```

Añadir archivos al área de staging (prepararlos para el commit):

```bash
git add <nombre_del_archivo>   # Añade un archivo específico
git add .                       # Añade todos los archivos modificados
```

Guardar los cambios con un commit (asegúrate de que los archivos estén en staging):

```bash
git commit -m "Descripción breve de los cambios"
```

---

## 4. Ver el Historial de Cambios

Para ver el historial de commits:

```bash
git log
```

Ver el historial en formato breve, con una línea por cada commit:

```bash
git log --oneline
```

---

## 5. Subir y Actualizar Cambios en el Repositorio Remoto

Para obtener los últimos cambios desde el repositorio remoto (sincronizar tu rama local):

```bash
git pull origin <nombre_de_la_rama>
```

Para subir tus commits al repositorio remoto:

```bash
git push origin <nombre_de_la_rama>
```

---

## 6. Trabajar con Ramas

Crear una nueva rama:

```bash
git branch <nombre_de_la_rama>
```

Cambiar a una rama existente:

```bash
git checkout <nombre_de_la_rama>
```

Crear y cambiar a una nueva rama en un solo paso:

```bash
git checkout -b <nombre_de_la_rama>
```

Fusionar otra rama en la actual (ejemplo: fusionar `feature` en `main`):

1. Cambia a la rama donde deseas fusionar:

   ```bash
   git checkout main
   ```

2. Realiza la fusión:

   ```bash
   git merge <nombre_de_la_rama>
   ```

---

## 7. Deshacer Cambios

Para quitar un archivo del área de staging:

```bash
git reset <nombre_del_archivo>
```

Deshacer el último commit sin perder los cambios en el código:

```bash
git reset --soft HEAD~1
```

Deshacer el último commit y los cambios en el código:

```bash
git reset --hard HEAD~1
```

Revertir los cambios de un archivo al último commit:

```bash
git checkout -- <nombre_del_archivo>
```

---

## 8. Ver Cambios en los Archivos

Ver los cambios realizados en el código sin añadirlos al área de staging:

```bash
git diff
```

Ver los cambios que ya están en el área de staging:

```bash
git diff --staged
```

---

## 9. Eliminar Archivos del Repositorio

Eliminar un archivo tanto del repositorio como del sistema de archivos:

```bash
git rm <nombre_del_archivo>
git commit -m "Eliminar archivo"
```

---

## 10. Ignorar Archivos con `.gitignore`

Crear un archivo `.gitignore` para especificar archivos o carpetas que Git debe ignorar. Ejemplo:

```
# Ignorar archivos de log
*.log

# Ignorar carpeta de build
/build/
```

---

## Resumen Rápido

1. **Inicializar o clonar un repositorio**: `git init` o `git clone <URL>`
2. **Ver estado del repositorio**: `git status`
3. **Añadir archivos al área de staging**: `git add <archivo>` o `git add .`
4. **Hacer commit de los cambios**: `git commit -m "Mensaje"`
5. **Subir cambios al repositorio remoto**: `git push origin <rama>`
6. **Actualizar el repositorio local**: `git pull origin <rama>`
7. **Crear y cambiar de rama**: `git branch` y `git checkout <rama>`

---

Con estos comandos, tienes una guía completa para empezar a trabajar con Git de forma efectiva en tus proyectos.

```

--- 

Este archivo proporciona una referencia completa y organizada de los comandos esenciales de Git. Puedes copiar y pegarlo en cualquier editor Markdown para visualizarlo como un archivo `.md`.
