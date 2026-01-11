# Git Architecture

## Estructura del Repositorio

El repositorio sigue una estructura organizada para separar código fuente,
documentación y configuraciones del proyecto.

- docs/
  - architecture/
    - git-architecture.md
- src/
- tests
  - integration
  - unit
- README.md
- CONTRIBUTING.md
- gitinore

## Estrategia de Branching

Se utiliza una estrategia basada en ramas simples:

- main: rama principal y estable.
- feature/*: nuevas funcionalidades.
- fix/*: correcciones de errores.
- docs/*: cambios en documentación.

Toda contribución debe realizarse mediante Pull Request hacia `main`.

## Políticas de Commits

El proyecto utiliza **Conventional Commits** para mantener un historial claro.

Formato:

`<tipo>(scope): <descripción>`

### Tipos permitidos
- feat: nueva funcionalidad
- fix: corrección de errores
- docs: cambios en documentación
- style: formato, sin cambios de lógica
- refactor: refactorización de código
- test: pruebas
- chore: tareas de mantenimiento

## Firma de Commits

Todos los commits deben:
- Estar firmados con **GPG**
- Mostrar el estado **Verified** en GitHub
