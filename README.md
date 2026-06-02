# Estética Digital e IA - Portafolio Grado 11

Este repositorio contiene la estructura consolidada y el código interactivo para el Portafolio Digital de la asignatura de Estética (Grado 11) del Colegio Danilo Cifuentes, integrando el modelo pedagógico ADDIE (Diseño de Recurso) y herramientas avanzadas de Inteligencia Artificial.

---

## 🚀 Guía Rápida de Git: Cómo Mantener tu GitHub Actualizado

Cada vez que hagas cambios en tus archivos locales y quieras subirlos a este repositorio en GitHub, sigue estos sencillos pasos desde tu consola de comandos en esta carpeta (`v2`):

### 1. Guardar tus cambios locales
Para preparar y empaquetar todos los archivos nuevos o modificados, ejecuta:

```bash
# 1. Preparar todos los archivos modificados
git add .

# 2. Guardar los cambios con un mensaje que describa qué hiciste
git commit -m "Escribe aquí una descripción breve de tus cambios"
```

### 2. Subir los cambios a GitHub
Una vez creado el commit local, súbelo a internet ejecutando:

```bash
# 3. Enviar los archivos a la rama principal en la nube
git push origin main
```

---

## 🛠️ Solución de Problemas Comunes

### A. Si hiciste cambios directamente en la web de GitHub
Si editaste algún archivo directamente desde la página de GitHub (como el README o descripciones), tu computadora estará "desactualizada" con respecto a la nube. Para solucionarlo antes de subir nuevos cambios, ejecuta:

```bash
# Trae y fusiona los cambios de GitHub a tu máquina local
git pull origin main --rebase
```
Luego, podrás hacer `git push origin main` normalmente.

### B. Si quieres forzar que GitHub se vea exactamente igual a tu computadora
Si por alguna razón hay conflictos y estás seguro de que tu versión local es la correcta y quieres que reemplace por completo lo que hay en GitHub (borrando cualquier historial conflictivo en la nube), ejecuta:

```bash
# Sobrescribe la versión de GitHub con tu código local
git push origin main --force
```

---

*Nota: Esta guía fue generada de manera personalizada para facilitar el flujo de trabajo continuo del proyecto.*
