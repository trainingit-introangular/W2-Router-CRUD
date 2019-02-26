# W2-Router-CRUD
Práctica para el sprint de la segunda semana, correspondiente a los temas **2-SPA** y **3-Data**.

## Objetivos

- Funcionalidad básica para mantener proyectos.

- Usar distintas rutas y cargarlas de manera dinámica.

- Formulario para recogida de datos

- Tabla para presentación

## Requisitos previos

- Partir de la funcionalidad de la aplicación de la práctica 1.


## Tareas

- [ ] use _dummyData_ from **environment.ts** _see resources below_
- [ ] create **HomeModule** with lazy loading
- [ ] Create **HomeComponent**
- [ ] Enable routing [HomeComponent](/)
- [ ] Show _Number of projects_ in [HomeComponent](/)
- [ ] create **ProjectsModule** with lazy loading
- [ ] Create **ProjectsComponent**
- [ ] Enable routing [ProjectsComponent](/projects)
- [ ] Show _List of projects_ in [ProjectsComponent](/projects)
- [ ] Create **EditorProjectComponent**
- [ ] Enable routing [EditorProjectComponent](/projects/:id)
- [ ] Show _Project with for current id_ in [EditorProjectComponent](/projects/:id)
- [ ] Create **NewProjectComponent**
- [ ] Enable routing [NewProjectComponent](/projects/new)
- [ ] Show _form to create a new project_ in [NewProjectComponent](/projects/new)
- [ ] Push new project in **environment**


## Recursos

Usa estos datos como punto de partida.

```typescript
export const environment = {
  appName: 'your practice election',
  production: false,
  projects: [
    { id: 0, name: 'Learn Angular' },
    { id: 1, name: 'Develop My Dream app' },
    { id: 2, name: 'Travel around the world' },
    { id: 3, name: 'Clean my room' }
  ]
};
```

Puedes importarlo en dónde lo necesites usando algo como...

```typescript
import { environment } from '../../environments/environment';
...

let projects = environment.projects;

...

```

> Recomendación: Seguir los guiones de las lecciones 2 y 3.