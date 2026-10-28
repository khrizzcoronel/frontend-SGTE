# SGTE — Frontend

Interfaz web del Sistema de Gestión de Trámites Estudiantiles (SGTE). Permite a estudiantes crear y consultar solicitudes, y a coordinadores y decanos revisar los trámites según su rol. Incluye inicio de sesión, registro de cuentas, notificaciones y vistas de seguimiento.

## Tecnología

Angular 21, TypeScript y Bootstrap.

## Desarrollo local

```bash
npm install
npm start
```

La interfaz se abre en `http://localhost:4200`. Necesita el backend principal en `http://localhost:8080` y el backend auxiliar de validación en `http://localhost:9090`. Las URL se configuran en `src/environments/`.

## Base de datos

Este repositorio no tiene base de datos propia. Los scripts SQL se encuentran en los repositorios `backend-SGTE` y `backend-AUX`.
