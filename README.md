

# Diseño de Aplicaciones Web

**Nombre:** Javier Terrones Pérez  
**Matricula:** 02910455  
**Carrera:** Ingeniería en Desarrollo de Software  
**Maestro:** Mario Eduardo  

## Markdown
Markdown es un lenguaje de marcado ligero que se utiliza para dar formato al texto de manera simple y efectiva. Se usa comúnmente en archivos README para describir proyectos, proporcionar documentación y más.

## Opciones de Etiquetado
Encabezados
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
Se usan para estructurar el contenido con distintos niveles de importancia.

Texto en Negrita, Cursiva y Tachado
**Texto en negrita**  
*Texto en cursiva*  
~~Texto tachado~~  
Para resaltar palabras o frases dentro del contenido.

Listas (Ordenadas y Desordenadas)
- Elemento de lista  
- Otro elemento  

1. Primer ítem  
2. Segundo ítem  
Útiles para organizar información en formato de lista.

## Lista de comandos
**Verificar el estado del repositorio local**
git status
Muestra el estado actual del repositorio, indicando qué archivos han sido modificados o están pendientes de ser confirmados.

**Agregar archivos individuales o globalmente**
git add nombre_archivo     # Agrega un solo archivo  
git add .                  # Agrega todos los archivos modificados  
Prepara los archivos para el commit.

**Agregar comentarios al commit**
git commit -m  "Descripción del cambio realizado"

**Subir los cambios al repositorio remoto**
git push origin main
🔹 Sube los cambios confirmados (commit) a GitHub.
🔹 Si trabajas en otra rama, reemplaza main con el nombre de la rama (git push origin nombre_rama).

**Crear, cambiar y eliminar ramas**
git branch nueva_rama       # Crear una nueva rama  
git checkout nueva_rama     # Cambiar de rama  
git branch -d nombre_rama   # Eliminar una rama  
Para manejar múltiples versiones del código sin afectar la rama principal.

**Revertir cambios a un commit específico**
git reset --hard ID_commit   # Regresar a un commit eliminando cambios  
git revert ID_commit         # Crear un commit que revierte cambios anteriores  
🔹 Permite deshacer cambios en el repositorio.



