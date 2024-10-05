# Hoja de Trucos de Git Bash

**Autor: Vilma Ponce**

## Introducción

Esta hoja de trucos contiene 100 comandos comunes de Git Bash, organizados desde lo básico hasta lo avanzado. Cada comando tiene una breve descripción para facilitar su comprensión y uso.

### ¿Qué es Git, Bash y Git Bash?

- **Git**: Un sistema de control de versiones distribuido.
- **Bash**: Un intérprete de línea de comandos.
- **Git Bash**: Una aplicación que proporciona una capa de emulación de Bash para ejecutar comandos Git en Windows.

## Comandos Básicos

- `git init`  
  Inicializa un nuevo repositorio Git.
  
- `git config --global user.name "<nombre>"`  
  Configura tu nombre de usuario a nivel global.

- `git config --global user.email "<email>"`  
  Configura tu correo electrónico a nivel global.

- `git status`  
  Verifica el estado de tu repositorio.

- `git add <archivo>`  
  Añade un archivo específico al área de preparación (staging).

- `git add .`  
  Añade todos los archivos modificados al área de preparación.

- `git commit -m "mensaje"`  
  Crea una nueva confirmación con un mensaje descriptivo.

- `git log`  
  Muestra el historial de confirmaciones del repositorio.

- `git log --oneline`  
  Muestra el historial de confirmaciones en una sola línea por commit.

- `git branch`  
  Lista todas las ramas en el repositorio.

- `git checkout <rama>`  
  Cambia a una rama existente.

- `git merge <rama>`  
  Fusiona una rama con la actual.

- `git clone <URL>`  
  Clona un repositorio remoto a tu máquina local.

## Comandos Intermedios

- `git pull`  
  Descarga los últimos cambios del repositorio remoto y los fusiona con la rama actual.

- `git push`  
  Sube los cambios locales al repositorio remoto.

- `git stash`  
  Guarda temporalmente los cambios no confirmados.

- `git stash pop`  
  Aplica los cambios guardados con `stash` y los elimina de la pila de stashes.

- `git reset <archivo>`  
  Quita un archivo del área de preparación (staging).

- `git reset --hard <commit>`  
  Restablece el repositorio al estado de una confirmación específica, eliminando cambios locales.

## Comandos Avanzados

- `git rebase <rama>`  
  Reaplica las confirmaciones de una rama en otra base.

- `git cherry-pick <commit>`  
  Aplica una confirmación específica en la rama actual.

- `git bisect`  
  Utiliza la búsqueda binaria para encontrar un commit que introdujo un bug.

- `git tag <nombre>`  
  Crea una etiqueta en un commit específico.

- `git reflog`  
  Muestra el historial de los comandos ejecutados en el repositorio.

## Trabajando con Ramas

- `git branch <nombre>`  
  Crea una nueva rama.

- `git branch -d <nombre>`  
  Elimina una rama local.

- `git branch -r`  
  Muestra las ramas remotas.

- `git checkout -b <nombre>`  
  Crea y cambia a una nueva rama.

## Trabajando con Remotos

- `git remote -v`  
  Muestra los remotos configurados.

- `git remote add <nombre> <URL>`  
  Añade un nuevo remoto.

- `git fetch <remoto>`  
  Descarga los objetos y referencias del repositorio remoto.

- `git push <remoto> <rama>`  
  Sube una rama específica al remoto.

## Manejo de Conflictos

- `git merge --abort`  
  Cancela una fusión en curso y regresa al estado anterior.

- `git mergetool`  
  Inicia la herramienta de resolución de conflictos.

- `git diff`  
  Muestra las diferencias entre el área de trabajo y el área de preparación.

- `git diff <rama>`  
  Compara dos ramas.

## Final

Este documento proporciona un recorrido rápido por los comandos más importantes de Git Bash. ¡Sigue explorando y practicando para convertirte en un experto!

