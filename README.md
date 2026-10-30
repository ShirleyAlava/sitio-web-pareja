# sitio-web-pareja

Sitio web desarrollado únicamente con HTML como parte de la **Práctica 2: Versionamiento de Aplicaciones** de la asignatura *Fundamentos de Sistemas Web* (NRC 32802, periodo 202651), Universidad de las Fuerzas Armadas ESPE.

## Objetivo

Aplicar técnicas de versionamiento con Git y GitHub para gestionar los cambios del código fuente, facilitar el desarrollo colaborativo y mantener un historial organizado de modificaciones.

## Integrantes

| Integrante | Rama de funcionalidad | Funcionalidad |
| --- | --- | --- |
| Shirley Stefania Alava Muñoz | `feature-shirley` | Página principal y navegación entre páginas |
| Alexis Bastidas | `feature-alexis` | Página secundaria "Sobre nosotros" (tabla y listas) |

## Funcionalidades implementadas

- Página de inicio con presentación del proyecto, lista de integrantes y tabla de contenido.
- Menú de navegación presente en todas las páginas.
- Página "Sobre nosotros" con tabla de integrantes, lista ordenada de objetivos y lista de tecnologías.
- Página "Pasatiempos" con lista y tabla.

## Estructura de archivos

```
sitio-web-pareja/
├── index.html
├── sobre-nosotros.html
├── pasatiempos.html
└── README.md
```

## Estructura de ramas

| Rama | Propósito |
| --- | --- |
| `main` | Producción: versión final aprobada |
| `pruebas` | Validación de las funcionalidades integradas |
| `desarrollo` | Integración de las funcionalidades individuales |
| `feature-shirley` | Funcionalidad de Shirley |
| `feature-alexis` | Funcionalidad de Alexis |

Flujo: `feature-*` → `desarrollo` → `pruebas` → `main`.

## Cómo visualizar el sitio

1. Clonar el repositorio: `git clone https://github.com/ShirleyAlava/sitio-web-pareja.git`
2. Abrir la carpeta `sitio-web-pareja`.
3. Abrir `index.html` con un navegador web.

## Comandos Git utilizados

`git init`, `git branch -M main`, `git add`, `git commit`, `git remote add`, `git push`, `git switch`, `git switch -c`, `git pull`, `git merge`, `git status`, `git log --oneline --graph --all`, `git branch -a`, `git remote -v`.

## Protección de la rama main

Se configuró una regla en GitHub (Settings → Branches) que exige Pull Request con al menos una aprobación antes de integrar cambios en `main`, bloqueando los push directos.

Prueba de proteccion.