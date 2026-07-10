# Gestor de sistemas del juego

## Objetivo

Dar a cada sistema del juego una sección separada para ver su código actual, dependencias, contratos, versiones, pruebas y publicación.

## Sistemas piloto

Inventario, equipamiento, combate, enemigos, NPC, misiones, chat, amigos, multijugador, cuentas, tiendas, economía, mapa, administración, PWA, Service Worker, actualizaciones, sonido, interfaz, guardado y sincronización.

## Pestañas por sistema

- Resumen
- Archivos
- Código
- Dependencias
- Eventos
- API
- Base de datos
- Configuración
- Pruebas
- Historial
- Versiones
- Publicar

## Reemplazo seguro

Crear una versión candidata sin borrar la activa. La nueva implementación debe conservar contratos públicos, eventos, JSON, rutas API, IPC, IDs y migraciones necesarias.

## Herramientas

- Monaco Editor
- Diff entre versiones
- Abrir en VS Code
- Lint, typecheck y pruebas
- Feature flags
- Staging
- Publicación
- Rollback de un clic
- Integración Git con ramas, commits, tags y changelog

## Arquitectura por módulo

- Contrato público
- Implementación
- UI
- Persistencia
- Sincronización
- Adaptadores
- Pruebas

## Regla

La versión anterior nunca se elimina hasta que la nueva haya sido probada, aprobada, publicada y verificada.

## Primera implementación

Usar Inventario como módulo piloto. Primero generar `INFORME_MODULO_INVENTARIO.md` detectando archivos, eventos, funciones, dependencias, estilos, conexión con servidor y datos usados.
