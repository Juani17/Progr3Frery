# Aplicación de tareas — React y TypeScript

Proyecto académico con listado, creación, edición y eliminación de tareas. Utiliza React, TypeScript, Vite, Zustand para el estado, Axios para HTTP y SweetAlert2 para confirmaciones. La persistencia de desarrollo se simula con JSON Server y `db.json`.

## Ejecución

Requisitos: Node.js y npm.

```bash
npm install
npm run bdDev
```

En otra terminal, desde la misma carpeta:

```bash
npm run dev
```

El cliente consulta `http://localhost:3000/tareas`; el script `bdDev` configura ese puerto. Vite informa la dirección del frontend. Scripts adicionales: `npm run build`, `npm run lint` y `npm run preview`.

## Organización

`src/components/` contiene la interfaz; `src/hooks/` las operaciones sobre tareas; `src/http/` el acceso a la API; `src/store/` el estado Zustand, y `src/types/` los tipos de TypeScript.

Proyecto de aprendizaje con API simulada. JSON Server no representa un backend productivo ni incorpora autenticación para esta aplicación.
