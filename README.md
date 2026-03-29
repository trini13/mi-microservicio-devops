# mi-microservicio-devops
Evaluación Parcial 1 - Ingeniería DevOps

## Estrategia de ramificación: GitFlow

Se eligió GitFlow como estrategia de ramificación porque permite organizar el trabajo en equipo de forma clara, separando el código estable (main), el desarrollo activo (develop), las nuevas funcionalidades (feature) y las correcciones urgentes (hotfix). Esta estrategia es ideal para proyectos colaborativos en la nube donde se necesita trazabilidad y control de versiones.

## Ramas del proyecto

| Rama | Propósito |
|------|-----------|
| main | Código estable listo para producción |
| develop | Integración de nuevos cambios |
| feature/agregar-endpoint | Desarrollo de nueva funcionalidad |
| hotfix/corregir-error-login | Corrección de error urgente |

## Convenciones de commits

| Prefijo | Uso |
|---------|-----|
| feat: | Nueva funcionalidad |
| fix: | Corrección de error |
| docs: | Cambios en documentación |
| hotfix: | Corrección urgente en producción |

## Flujo de trabajo

1. Se crea una rama feature desde develop
2. Se trabaja en esa rama
3. Se abre un pull request hacia develop
4. Se revisa y aprueba
5. Se hace merge a develop
6. Cuando está listo, develop se une a main