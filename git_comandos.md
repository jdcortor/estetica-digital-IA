# Guía de Comandos Git - Portafolio Estética Digital

Utiliza estos comandos en tu terminal de comandos (dentro de la carpeta `v2`) para subir y mantener al día tu repositorio de GitHub:

---

## 📌 1. Subir cambios diarios (Normal)

Ejecuta estos tres comandos en orden cuando hagas cualquier modificación en tus páginas locales y desees verlas reflejadas en GitHub:

```powershell
# Paso 1: Preparar todos los archivos modificados
git add .

# Paso 2: Guardar los cambios localmente con un mensaje descriptivo
git commit -m "Descripción corta de lo que modificaste"

# Paso 3: Subir los cambios a tu repositorio en GitHub
git push origin main
```

---

## 📌 2. Resolver problemas si editaste archivos en la web de GitHub

Si modificaste algún archivo directamente desde la página web de GitHub, tu computadora local no estará al día. Para solucionarlo y sincronizar antes de subir nuevos cambios, ejecuta:

```powershell
# Trae las actualizaciones de GitHub y las combina de forma limpia con tu trabajo local
git pull origin main --rebase
```
*Luego de esto, puedes ejecutar el comando `git push origin main` de forma normal.*

---

## 📌 3. Forzar actualización (Sobrescribir GitHub)

Si tienes conflictos al subir archivos y quieres que el contenido de tu computadora **sobrescriba por completo** lo que hay en GitHub (es decir, hacer que GitHub se vea exactamente igual a tu carpeta local, ignorando historiales viejos), ejecuta:

```powershell
# Sobrescribe de forma forzada tu repositorio en GitHub con tus archivos locales
git push origin main --force
```
