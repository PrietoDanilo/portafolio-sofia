# Proyectos personales

Espacio para organizar **alimentación, presupuestos, finanzas y deporte** en un solo lugar.
Por ahora todo es texto (Markdown) y tablas (CSV): no hay código. Los `.csv` se abren
directo en Excel o Google Sheets.

> Esta carpeta vive en una rama aparte (`claude/proyectos-personales-prep-yab52g`).
> No toca el portafolio (`index.html`, `style.css`, `images/`) ni la rama `master`.
> Cuando tengas un repositorio nuevo, se puede mover esta carpeta tal cual.

## Estructura

| Carpeta | Qué guarda | Archivos |
|---|---|---|
| `alimentacion/` | Lo que como y cómo lo preparo | `preferencias.md`, `registro-comidas.csv`, `meal-prep.md`, `recetas.md` |
| `presupuestos/` | Cuánto cuesta comer y vivir | `presupuesto-mensual.csv`, `lista-compras.csv` |
| `finanzas/` | El plan general de mi plata | `plan-financiero.md`, `metas-ahorro.csv` |
| `deporte/` | Lo que entreno | `registro-deporte.csv`, `plan-entrenamiento.md` |
| `semanal/` | La revisión que junta todo | `revision-semanal.md` |

## Reglas

- **Recetas:** en `alimentacion/recetas.md` solo se guardan recetas **ya preparadas** y con
  **confirmación** para guardarlas. Las ideas y propuestas no se anotan.

## Cómo se conectan

```
 Recetas ──► Meal prep semanal ──► Lista de compras ──► Presupuesto mensual ──► Plan financiero
                   ▲                                                                  │
                   │                                                                  ▼
 Registro deporte ─┴──────────────► Revisión semanal ◄──── Registro de comidas ◄── Metas de ahorro
```

- **Deporte → comida:** los días de entrenamiento fuerte planifico comidas con más energía/proteína.
- **Comida → plata:** cada meal prep genera una lista de compras con costo estimado; lo real va al presupuesto.
- **Plata → metas:** lo que sobra del presupuesto se mueve a las metas de ahorro.
- **Todo → revisión semanal:** una vez por semana miro las tres cosas juntas y ajusto.

## Rutina sugerida

| Cuándo | Qué hago | Dónde |
|---|---|---|
| Diario (2 min) | Anotar comidas y entrenamiento | `registro-comidas.csv`, `registro-deporte.csv` |
| Viernes/sábado | Elegir recetas y armar el meal prep | `meal-prep.md`, `recetas.md` |
| Antes de comprar | Armar lista con precios estimados | `lista-compras.csv` |
| Después de comprar | Anotar gasto real | `presupuesto-mensual.csv` |
| Domingo (15 min) | Revisión semanal | `revision-semanal.md` |
| Fin de mes | Cerrar presupuesto y mover ahorro | `plan-financiero.md`, `metas-ahorro.csv` |

## Ideas para más adelante (cuando haya programación)

- Calcular automáticamente el costo por porción de cada receta.
- Gráficos de gasto vs. presupuesto y de minutos entrenados por semana.
- Una página web simple (como el portafolio) con un panel personal.
