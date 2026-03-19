# Actividad grupal: investigación + práctica real

## Objetivo de la actividad

Que los alumnos:

- investiguen qué son las ramas
- comprendan por qué se usan
- practiquen el flujo real de colaboración
- aprendan a hacer fork, branch, commit, push y pull request
- entiendan qué hace quien revisa y acepta cambios

## Integrantes

- Matias Celis Orellana
- Monserrat Miranda
- Miussette Alfaro
- Javiera Godoy
- Sherina Ponce de Leon
- Fernando Cuevas

---

## Desarrollo

### 1. ¿Qué es una rama en Git?

Una rama (branch) es una versión independiente del proyecto que permite trabajar en cambios sin modificar directamente la rama principal.

### 2. ¿Por qué las ramas ayudan a ordenar el trabajo?

Las ramas permiten separar tareas, como nuevas funcionalidades o correcciones, facilitando que varias personas trabajen al mismo tiempo sin interferirse y manteniendo el proyecto organizado.

### 3. ¿Qué riesgo existe si todos trabajan en (main)?

El principal riesgo es corromper la versión oficial del proyecto, ya que los cambios se mezclan directamente y pueden generar errores.


### 4. ¿Qué es un branch?
Un branch(rama) en Git es simplemente una línea de trabajo independiente dentro de un mismo proyecto. En resumen, con Branch trabajamos dentro del mismo proyecto sin afectar la versión principal.

### 5. ¿Qué es un Fork?
Un fork es una copia completa de un repositorio, pero en mi propia cuenta de GiHub. En resumen, Fork es para copiar un proyecto ajeno a tu cuenta para modificarlo.

### 6.¿Cuál es la diferencia entre ambos?
Branch es una rama para trabajar dentro del mismo repositorio sin afectar main y el Fork es una copia del repositorio, es decir, es un proyecto separado que se usa cuando el repo no es tuyo.
## 🌿 ¿Qué es `main` y por qué se protege?

### 7. ¿Qué representa `main` en un proyecto?

La rama `main` es la rama principal de un repositorio. Representa la versión oficial del proyecto, es decir, el código más completo, funcional y listo para ser utilizado o entregado.

---

### 8. ¿Por qué no debería usarse para cambios directos?

No se recomienda trabajar directamente en `main` porque:
- Puede introducir errores o bugs en el proyecto
- No hay revisión previa de los cambios
- Puede afectar a otras personas que usan el código

Lo correcto es crear una nueva rama, realizar los cambios ahí y luego integrarlos mediante una revisión.

---

### 9. ¿Por qué es importante mantenerla estable?

Es importante mantener `main` estable porque:
- Es la versión que otros utilizarán
- Sirve como base confiable del proyecto
- Permite un trabajo en equipo más organizado
- Evita errores en producción

Si `main` no es estable, todo el proyecto puede verse afectado.