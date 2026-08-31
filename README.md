# 🎬 Cine Financiero BanCoppel

Sitio web estático de la experiencia **Cine Financiero** del stand BanCoppel — kiosko interactivo de 10 pantallas donde los usuarios toman decisiones financieras y construyen "su propia película".

## 📋 Flujo de pantallas

| # | Pantalla | Descripción |
|---|---|---|
| 1 | `01_bienvenida.html` | Splash + carrusel de las 4 estaciones |
| 2 | `02_decision1.html` | **Escena 1/3 — Emergencias** (A/B/C) |
| 3 | `03_decision1_resultado.html` | Decisión 1 registrada + consecuencia + countdown 5s |
| 4 | `04_decision2.html` | **Escena 2/3 — Inversión** (A/B/C) |
| 5 | `05_decision2_resultado.html` | Decisión 2 registrada + countdown |
| 6 | `06_decision3.html` | **Escena 3/3 — Metas** (A/B/C) |
| 7 | `07_decision3_resultado.html` | **¡CORTE!** 3/3 decisiones registradas |
| 8 | `08_produccion.html` | Producción — confirma para producir |
| 9 | `09_pelicula_lista.html` | ¡Tu película está en producción! |
| 10 | `10_encuesta.html` | Encuesta final con 5 preguntas |

## 🚀 Cómo navegar

Cada click lleva a la siguiente pantalla según el flujo definido. La primera pantalla siempre es `01_bienvenida.html` (también accesible desde `index.html`).

## 🎨 Sistema de diseño

Paleta corporativa BanCoppel:
- 🔵 **Azul corporativo:** `#003DA5`
- 🟡 **Amarillo:** `#FFC72C`
- ⚪ **Blanco:** `#FFFFFF`
- 🔘 **Grises:** `#F4F6FA` a `#4A5568`

Tipografía: `-apple-system, "Segoe UI"` (sistema).

## 📦 Despliegue

El sitio está publicado en **GitHub Pages**:
👉 https://aguitech.github.io/bancoppel/

## 📁 Estructura

```
bancoppel/
├── index.html                    # Redirige a la primera pantalla
├── 01_bienvenida.html
├── 02_decision1.html
├── 03_decision1_resultado.html
├── 04_decision2.html
├── 05_decision2_resultado.html
├── 06_decision3.html
├── 07_decision3_resultado.html
├── 08_produccion.html
├── 09_pelicula_lista.html
├── 10_encuesta.html
├── assets/
│   ├── styles.css               # Estilos compartidos
│   └── referencias/              # Pantallas de referencia (no usadas en runtime)
└── README.md
```

## 🛠️ Desarrollo local

```bash
# Opción 1: Abrir directamente
open index.html

# Opción 2: Servidor local
python3 -m http.server 8000
# Abre http://localhost:8000
```

---

**BanCoppel · Afore Coppel · Cine Financiero 2026**
