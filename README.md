
[![My Skills](https://skillicons.dev/icons?i=git,github)](https://skillicons.dev) Complete Git and GitHub: Beginner to Expert
--

¡Curso de **Complete Git and GitHub: Beginner to Expert**! Este curso trata sobre los conceptos básicos hasta un nivel avanzado en el uso de Git y GitHub.

## Temas abordados

- **Conceptos Clave de Git y GitHub**: Fundamentos de Git y GitHub, y cómo se utilizan en el desarrollo de software moderno.
- **Flujo de Trabajo Completo de Git**: Manejar todo el ciclo de vida de un proyecto utilizando Git, desde la creación de repositorios hasta la gestión de ramas y la fusión de cambios.
- **Creación y Manejo de Ramas**: Crear ramas, resolver conflictos y deshacer cambios, lo cual es crucial para el desarrollo colaborativo.
- **Repositorios en GitHub**: Crear y forkear repositorios en GitHub, y aprender a subir cambios locales a GitHub.

## Comandos de Git Bash

Lista de comandos esenciales de Git Bash para el control de versiones.

### 🔩 Configuración Inicial

- **Configurar tu nombre de usuario y correo electrónico**:
  ```bash
  git config --global user.name "Nombre_Usuario"
  git config --global user.email "email@example.com"
  git config --list
  ```
### 📁 Archivos

- **Comandos para acceder, ver archivos y remover**:
  ```bash
  cd "nombre_archivo"
  ls
  rm "nombre_archivo"
  rmdir "nombre_carpeta"
  ```
### 💻 Configuración de Repositorio

- **Comandos para inicializar, agregar rama**:
  ```bash
  git init
  git remote add origin <url_repositorio>
  ```
- **Comandos para agregar, commit, commit con detalle**:
  ```bash
  git add .
  git commit -m "mensaje"
  git commit -m "mensaje" -m "detalle"
  ```
- **Comandos para ver estado del repositorio**:
  ```bash
  git status
  ```
- **Comando para ver commits**:
  ```bash
  git log --oneline
  ```
- **Comando para revertir commit**:
  ```bash
  git revert "id_commit"
  ```
- **Comando para resetear commit**:
  ```bash
  git reset "id_commit"
  ```
- **Comando cambiar de rama**:
  ```bash
  git checkout "nombre_rama"
  ```
- **Comando crear y ver las ramas**:
  ```bash
  git branch test
  git branch -a
  git checkout -b test-1
  ```
- **Comando eliminar rama**:
  ```bash
  git branch -D "nombre_rama"
  ```
