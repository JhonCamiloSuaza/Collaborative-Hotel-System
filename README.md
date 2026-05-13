# Hotel System - PostgreSQL Database

Proyecto colaborativo de base de datos para el sistema hotelero.

---

## 🚀 REGLA DE ORO PARA LA SUBIDA

Para asegurar la integridad del proyecto, todos los integrantes deben seguir esta instrucción:

> **"Si la HU indica una CARPETA (termina en `/`), se debe subir la carpeta con TODO su contenido (archivos .sql y .yaml). Si indica un ARCHIVO específico, se sube solo ese archivo."**

---

## 📋 Estructura del Proyecto

- `entregables/estructura-base-datos/`: Estructura ejecutable con PostgreSQL y Liquibase.
- `docs/architecture/model-data/`: Documentos de análisis técnico (ES/EN).
- `tablero_azure_trello_clickup.csv`: Tablero oficial de seguimiento y responsabilidades.
- `.gitignore`: Excluye archivos locales y carpetas de coordinación interna.

## 🗺️ Mapeo de Entregas (HUs)

| Área | Historias de Usuario | Responsable Principal |
|---|---|---|
| **Estructura e Infraestructura** | HU-01 a HU-06 | Jhon Camilo Suaza Sanchez |
| **Modelado de Dominios (Tablas)** | HU-07 a HU-12 | Danna Valentina Barrios |
| **Lógica, Vistas y Seguridad** | HU-13 a HU-16, HU-21, HU-23 | juan Pablo Gomez Perdomo |
| **Datos, Roles y Transacciones (DML, DCL, TCL)** | HU-17, HU-18, HU-19, HU-20, HU-22 | Johan Steven Rodriguez Charr |

## ⚙️ Configuración de Liquibase

El punto de entrada principal es:
`entregables/estructura-base-datos/changelog/changelog-master.yaml`

Este archivo incluye los changelogs maestros de cada nivel:
1. `01_ddl/changelog-master.yaml`
2. `02_dml/changelog-master.yaml`
3. `03_dcl/changelog-master.yaml`
4. `04_tcl/changelog-master.yaml`

## 🌊 Flujo de Trabajo (Git Flow)

El trabajo debe seguir estrictamente este flujo de ramas:
`feature/HU-XX -> dev -> qa -> main`

**Está prohibido trabajar directamente en la rama `main`.**

---
