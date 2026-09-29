# InventarioWeb
Sistema de inventario para tienda de ropa (local + redes sociales). Proyecto Fullstack 2 Duoc UC.

## Stack
- frontend/: React + Vite, pruebas con Vitest (unitarias) y Playwright (aceptación)
- backend/: microservicios Spring Boot (Java 21, Maven), MySQL
- Monorepo

## Foco del negocio
Registrar clientes compradores: quién compra, qué y cuánto.
Una venta puede involucrar varios clientes con la misma dirección de despacho.

## Docs
- Requisitos: docs/ERS.md
- Mockups: docs/mockups/

## Reglas
- Código y commits en español
- Cada requisito del ERS (RF-XX) debe tener al menos una prueba que lo referencie
- No avanzar a un servicio nuevo sin tests pasando