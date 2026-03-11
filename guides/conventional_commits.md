# Conventional commits

Este es un acordeón para referencia de los mensajes de _commit_ siguiendo las
prácticas de **Conventional commits**. Los títutlos de los mensajes deben 
seguir el patrón:

```
<tipo> (<alcance opcional>): <descripción>
```

## Tipos de Commit más comunes

- **feat**: Una nueva característica o funcionalidad.
  - Ejemplo: feat(auth): agregar soporte para inicio de sesión con Google
- **fix**: Corrección de un error (bug).
  - Ejemplo: fix(api): corregir fuga de memoria en consulta de usuarios
- **docs**: Cambios solo en la documentación.
  - Ejemplo: docs: actualizar instrucciones de instalación en el README
- **style**: Cambios estéticos que no afectan el código (espacios, formato, comas).
  - Ejemplo: style: corregir indentación en main.css
- **refactor**: Cambio de código que no corrige errores ni añade funciones.
  - Ejemplo: refactor: simplificar función de validación de fechas
- **perf**: Mejora de rendimiento.
  - Ejemplo: perf: optimizar consulta de base de datos para reportes
- **test**: Añadir o corregir pruebas unitarias/integración.
  - Ejemplo: test: agregar pruebas para el módulo de pagos
- **chore**: Tareas de mantenimiento (actualizar librerías, configurar herramientas).
  - Ejemplo: chore: actualizar versiones de npm
- **build**: Cambios que afectan el sistema de construcción o dependencias externas.

## Reglas de oro

- **Modo imperativo**: Usa "agregar" o "corregir" en lugar de "agregado" o "corrigió".
- **Cambios Disruptivos (Breaking Changes)**: Se indican con un ! después del 
  tipo/alcance (ej. feat!: eliminar soporte para API v1) o con BREAKING CHANGE: en el pie del mensaje.
- **Mayúsculas y Puntos**: La descripción empieza en minúscula y no lleva punto final.
- **Longitud**: Mantén el título bajo los 50 caracteres y el cuerpo (si existe) en 72.
