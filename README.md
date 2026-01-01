# Proyecto de Control de Versiones con Git

## Descripción del Proyecto

Este proyecto es un sistema de gestión de notas académicas desarrollado como práctica para el control de versiones con Git. Permite crear, organizar y consultar notas de diferentes asignaturas.

## Estructura del Proyecto

```
proyecto-notas/
├── README.md
├── doc-notas.txt
├── index.html
└── imagenes/
    ├── Foto_Perfil.jpg
    ├── Foto_general.jpg
    └── Foto_varias.jpg
```

## Objetivos de Aprendizaje

- Gestión de repositorio local
- Uso del staging area
- Creación de commits descriptivos
- Navegación por el historial de versiones
- Trabajo con ramas (branching)
- Fusión de ramas (merging)
- Resolución de conflictos
- Etiquetado de versiones
- Conexión con repositorio remoto (opcional)

## Requisitos Previos

- Git instalado en el sistema
- Terminal de comandos
- Editor de texto

## Configuración Inicial

1. Inicializar el repositorio:
```bash
git init
```

2. Configurar identidad de Git:
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu.email@ejemplo.com"
```

## Comandos Principales Utilizados

### Gestión básica
- `git init` - Inicializar repositorio
- `git status` - Ver estado del repositorio
- `git add <archivo>` - Añadir archivos al staging area
- `git commit -m "mensaje"` - Confirmar cambios

### Historial
- `git log` - Ver historial completo
- `git log --oneline` - Ver historial resumido
- `git log --graph --all` - Ver historial gráfico

### Navegación
- `git checkout <commit/rama>` - Cambiar a otra versión/rama
- `git checkout -b <nombre-rama>` - Crear y cambiar a nueva rama

### Ramas
- `git branch` - Listar ramas
- `git branch <nombre>` - Crear rama
- `git merge <rama>` - Fusionar rama

### Etiquetas
- `git tag <nombre>` - Crear etiqueta
- `git tag -a <nombre> -m "mensaje"` - Crear etiqueta anotada

### Remoto (opcional)
- `git remote add origin <url>` - Conectar repositorio remoto
- `git push -u origin main` - Subir cambios
- `git pull` - Descargar cambios

## Versiones

- **v0.1** - Estructura inicial del proyecto
- **v1.0** - Primera versión estable

## Autor

Rosalina Alonso Marañón

## Fecha

01/01/2026

## Licencia

Proyecto educativo 