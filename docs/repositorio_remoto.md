
---

## 📄 `repositorio_remoto.md`

```markdown
# Repositorio Remoto en GitHub

Un repositorio remoto permite almacenar el proyecto en la nube y trabajar de forma colaborativa. GitHub es una de las plataformas más utilizadas para este propósito.

## Crear un repositorio en GitHub

1. Ingresar a https://github.com
2. Iniciar sesión con una cuenta.
3. Hacer clic en **New repository**.
4. Asignar un nombre al repositorio.
5. Seleccionar si será público o privado.
6. Hacer clic en **Create repository**.

## Conectar repositorio local con repositorio remoto

Una vez creado el repositorio en GitHub, se debe enlazar con el repositorio local.

```bash
git remote add origin https://github.com/usuario/nombre-repositorio.git

git branch -M main
git push -u origin main

Comandos importantes

git remote -v → Muestra los repositorios remotos configurados.

git push → Envía los cambios al repositorio remoto.

git pull → Descarga los cambios del repositorio remoto.