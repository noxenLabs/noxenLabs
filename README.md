
[![Python](https://img.shields.io/badge/Python-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/doc/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev/)
[![Nest.js](https://img.shields.io/badge/Nest.js-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)](https://docs.nestjs.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/docs/)
[![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://docs.aws.amazon.com/)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://docs.flutter.dev/)
[![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)](https://developer.android.com/studio)
[![iOS Developer](https://img.shields.io/badge/iOS%20Developer-000000?style=for-the-badge&logo=apple&logoColor=white)](https://developer.apple.com/ios/)

# 🚀 Bienvenido a Noxen Labs
Este apartado tiene como propósito definir las **reglas de trabajo** que permitirán al equipo desarrollar de forma **ordenada, escalable y mantenible**, aplicando principios **SOLID** y utilizando una arquitectura base común para todos los proyectos.  
Su objetivo es establecer un **estándar de desarrollo** que garantice consistencia, calidad y buenas prácticas en cada entrega.

---

## 📌 Reglas de Trabajo

1. **Ramas**
   - `main` → rama estable y lista para producción.
   - `develop` → rama de integración de nuevas funcionalidades.
   - `feature/{nombre}` → para nuevas funcionalidades.
   - `bugfix/{nombre}` → para correcciones.
   - `hotfix/{nombre}` → para arreglos urgentes en producción.

2. **Enlazar PR con Jira**
   - Todo Pull Request debe estar vinculado a una tarea en Jira.
   - El título del PR debe incluir el ID de la tarea entre corchetes, por ejemplo: `[JIRA-123] feat: implementar validación de login`.
   - En la descripción del PR, agregar un enlace directo a la tarea: `https://midominio.atlassian.net/browse/JIRA-123`.
   - Si el PR resuelve completamente la tarea, indicarlo con: `Resolves: JIRA-123` para que Jira actualice automáticamente el estado cuando se mergee.

3. **Commits**
   Seguir el formato [Conventional Commits](https://www.conventionalcommits.org/):
   - FEAT: agregar autenticación con Google
   - FIX: corregir error en cálculo de totales
   - BREAKING CHANGE: subir una version major de la aplicación.
4. **Pull Requests**
- Todo cambio debe ir mediante PR.
- Revisar código antes de merge.
- Incluir descripción y referencia a issues.

5. **Estándares**
- Linter activo (ESLint, Prettier).
- Tests obligatorios para nuevas funcionalidades.
- Documentar funciones y módulos clave utilizando JSDOC.
- Utilizar template para cada desarrollo base.
