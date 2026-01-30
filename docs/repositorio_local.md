
---

## 📄 `repositorio_local.md`

```markdown
# Creación de un Repositorio Local con Git

Git es un sistema de control de versiones que permite registrar los cambios realizados en un proyecto. Un repositorio local es aquel que se encuentra en nuestra computadora.

## Inicializar un repositorio local

Para crear un repositorio local se deben seguir los siguientes pasos:

1. Abrir la consola.
2. Ubicarse en la carpeta del proyecto.
3. Ejecutar el comando de inicialización de Git.

```bash
git init

git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"

Flujo básico de trabajo en Git

git status → Muestra el estado de los archivos.

git add . → Agrega todos los archivos al área de preparación.

git commit -m "Mensaje del commit" → Guarda los cambios en el repositorio.