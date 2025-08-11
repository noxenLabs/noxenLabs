# 🚀 Proyecto Base - Arquitectura Hexagonal / DDD

Este repositorio sirve como base para el desarrollo de aplicaciones siguiendo **Arquitectura Hexagonal** y principios de **Domain-Driven Design (DDD)**.  
Su objetivo es establecer un **estándar de trabajo** para que el equipo pueda desarrollar de forma ordenada, escalable y mantenible.

---

## 📌 Reglas de Trabajo

1. **Ramas**
   - `main` → rama estable y lista para producción.
   - `develop` → rama de integración de nuevas funcionalidades.
   - `feature/{nombre}` → para nuevas funcionalidades.
   - `bugfix/{nombre}` → para correcciones.
   - `hotfix/{nombre}` → para arreglos urgentes en producción. 

2. **Commits**
   Seguir el formato [Conventional Commits](https://www.conventionalcommits.org/):
FEAT: agregar autenticación con Google
FIX: corregir error en cálculo de totales
BREAKING CHANGE: subir una version major de la aplicación.

3. **Pull Requests**
- Todo cambio debe ir mediante PR.
- Revisar código antes de merge.
- Incluir descripción y referencia a issues.

4. **Estándares**
- Linter activo (ESLint, Prettier).
- Tests obligatorios para nuevas funcionalidades.
- Documentar funciones y módulos clave.

src/
├── application/ # Casos de uso (lógica de aplicación)
├── domain/ # Entidades y lógica de negocio pura
├── infrastructure/ # Adaptadores, repositorios, controladores, APIs
├── config/ # Configuración de la app
├── shared/ # Utilidades, helpers, constantes
├── tests/ # Pruebas unitarias e integración
└── main.ts # Punto de entrada

> 🔹 El **dominio** nunca debe depender de infraestructura.  
> 🔹 Los casos de uso coordinan la lógica de negocio con adaptadores externos.  

---

## 📖 Guía Rápida para Contribuir

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/usuario/repositorio.git
