#Ferretería Tico — Inventario Web
Integrantes:
- Navarrete Hernández Laura Itzel
- Patiño Nicasio Diego

---

## Descripción

Sistema de gestión de inventario para la ferretería "Tico". Permite registrar, editar,
eliminar y consultar productos. Conectado a PostgreSQL en Supabase mediante la API REST
automática. Desplegado como sitio estático en GitHub Pages.

## Estructura de archivos

```
ferreteria-tico/
├── index.html          ← Aplicación principal (CRUD inventario)
├── landing.html        ← Página informativa (GitHub Pages)
├── supabase_setup.sql  ← Script SQL para crear tablas y datos
└── README.md           ← Este archivo
```

---

## Funcionalidades

- ✅ Ver inventario completo con estadísticas
- ✅ Buscar productos por nombre o marca
- ✅ Filtrar por categoría
- ✅ Agregar nuevos productos
- ✅ Editar productos existentes
- ✅ Eliminar productos
- ✅ Alerta visual de stock bajo (< 5 unidades)
- ✅ Modo demo (sin BD, datos en memoria)

---

## Stack tecnológico

| Capa | Tecnología |
|---|---|
| Frontend | HTML5 · CSS3 · JavaScript ES6+ |
| Base de datos | PostgreSQL (Supabase) |
| Hosting | GitHub Pages |
| API | Supabase REST API (automática) |
| Fonts | Google Fonts (Bebas Neue, DM Sans) |

---
