# Plan de Implementacion del Sitio de Documentacion

## Estado Actual

Proyecto Docusaurus con TypeScript configurado exitosamente con las siguientes caracteristicas:

- Tema oscuro por defecto
- Modo solo documentacion (blog deshabilitado)
- Navegacion autogenerada desde estructura de carpetas
- Idioma configurado en espanol
- Estructura de carpetas para las 4 unidades del curso
- Secciones adicionales para Sistema Implementado y Reporte de Modificaciones

## Estructura de Carpetas Creada

```text
docs/
├── index.md (Pagina de inicio)
├── _activity-template.md (Plantilla para actividades)
├── unidad-1/
│   ├── _category_.json
│   └── index.md
├── unidad-2/
│   ├── _category_.json
│   └── index.md
├── unidad-3/
│   ├── _category_.json
│   └── index.md
├── unidad-4/
│   ├── _category_.json
│   └── index.md
├── producto-integrador/
│   ├── _category_.json
│   └── index.md
├── sistema-implementado/
│   ├── _category_.json
│   └── index.md
└── reporte-modificaciones/
    ├── _category_.json
    └── index.md
```

## Tareas Completadas

1. Inicializacion de Docusaurus con TypeScript
2. Configuracion de tema oscuro y modo docs-only
3. Creacion de estructura de carpetas para curso
4. Plantilla de actividad con secciones estandar
5. Configuracion de navegacion autogenerada
6. Commit inicial siguiendo conventional commits

## Proximos Pasos

### Unidad 1

- [ ] Actividad preliminar: Compartamos! Foro
- [ ] Actividad 1: Metodologia agil SCRUM Examen
- [ ] Actividad 2: El product backlog Tarea
- [ ] Actividad integradora: Sprint, el corazon de SCRUM Tarea

### Unidad 2

- [ ] Actividad 1: Aplicacion de SCRUM Tarea
- [ ] Actividad 2: El sprint Shedule Tarea
- [ ] Actividad integradora 2: El backlog y el spring Schedule del proyecto Tarea

### Unidad 3

- [ ] Actividad preliminar: Retomando mi primer sprint Foro
- [ ] Actividad 1: Primera fase de desarrollo, revision y ajuste de los Sprints Tarea
- [ ] Actividad 2: Segunda fase de desarrollo, revision y ajuste de los Sprints y el backlog Tarea
- [ ] Actividad 3: Tercera fase de desarrollo, revision y ajuste de los Sprints y el backlog Tarea
- [ ] Actividad integradora: Producto final U3 Tarea

### Unidad 4

- [ ] Actividad 1: Reunion de revision inicial
- [ ] Actividad 2: Reunion para revision de modificaciones Tarea

### Producto Integrador

- [ ] Producto integrador: El final del proceso Tarea

### Secciones Adicionales

- [ ] Documentar Sistema Implementado
- [ ] Completar Reporte de Modificaciones

## Flujo de Trabajo

Para cada actividad:

1. Crear archivo markdown en la carpeta de unidad correspondiente
2. Usar plantilla `_activity-template.md` como base
3. Completar las secciones: Objetivo, Instrucciones, Recomendaciones, Criterios de Evaluacion
4. Hacer commit con mensaje: `docs(unidad-N): add activity X.Y - nombre-actividad`

## Comandos Utiles

- Iniciar servidor de desarrollo: `pnpm start`
- Construir sitio para produccion: `pnpm build`
- Servir sitio de produccion: `pnpm serve`

## Convenciones de Commits

Seguimos el estandar Conventional Commits:

- `feat:` - Nueva funcionalidad
- `docs:` - Cambios en documentacion
- `fix:` - Correccion de errores
- `refactor:` - Refactorizacion de codigo
- `style:` - Cambios de formato
- `chore:` - Tareas de mantenimiento

Formato para actividades: `docs(unidad-N): add activity X.Y - descripcion-corta`
