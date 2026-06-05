# Tadeva GAP — Gestión de Buenas Prácticas Agrícolas

**Campaña 2026–2027 | Tabacos del Valle**

Aplicación web para la gestión agronómica de productores tabacaleros. Funciona como archivo HTML autocontenido — sin servidor, sin instalación, sin conexión a internet.

---

## Cómo usar

### En notebook / PC
1. Descargá `index.html`
2. Abrilo con **Chrome**, **Edge** o **Firefox**
3. ¡Listo!

### En celular (Android / iPhone)
1. Descargá `index.html` (por WhatsApp, email o Google Drive)
2. Abrilo con **Chrome**
3. Para instalarlo como app: menú **⋮ → Agregar a pantalla de inicio**

---

## Funcionalidades

### Pantalla principal
- Logo Tadeva con acceso directo a las 6 etapas
- Botón **Buscar productor** para retomar visitas de productores ya contratados
- Contador de productores contratados en la campaña

### 6 Etapas del proceso

| Etapa | Descripción |
|-------|-------------|
| 1. Contratación | Alta de productor, cupo, superficie cupificada, georreferenciación |
| 2. Almácigo | Tenencia de tierra, tipos de almácigo, variedades de semilla |
| 3. Plantación | Datos de trasplante, fertilización |
| 4. Cultivo | Sanidad, enfermedades, plagas |
| 5. Cosecha | Estufas (Virginia) / Tendales (Burley) |
| 6. Clasificado | Tipo de clasificación, capacitaciones |

### Características técnicas
- **384 productores** cargados desde base de datos real (campaña 2026-2027)
- Tipos de tabaco: **Virginia**, **Virginia Orgánico**, **Burley**
- Provincias: **Jujuy**, **Salta**, **Tucumán**
- **Georreferenciación GPS** obligatoria en cada etapa
- Visitas a campo ilimitadas por etapa y productor
- Técnicos: Ossola Javier / Berruezo Mauricio / Martinez Luis
- Datos persistidos en `localStorage` del navegador
- Selección automática de tipo de tabaco según productor contratado

---

## Estructura del proyecto

```
tadeva-gap/
├── index.html      ← App completa (autocontenida, logo embebido)
└── README.md       ← Este archivo
```

---

## GitHub Pages (opcional)

Para publicar la app en línea gratis con GitHub Pages:

1. Ir a **Settings** del repositorio
2. Sección **Pages**
3. Source: **Deploy from a branch**
4. Branch: `main` / carpeta: `/ (root)`
5. Guardar → la app queda disponible en `https://[usuario].github.io/tadeva-gap/`

---

## Versión

- **v1.0** — Campaña 2026-2027
- Desarrollado para **Tadeva — Tabacos del Valle**
