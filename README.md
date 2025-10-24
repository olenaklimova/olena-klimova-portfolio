# Portfolio Olena Klimova - Data Analyst

Portfolio personale professionale creato con HTML5, CSS3 (LESS), e Bootstrap 5.

## 📚 Documentazione Completa

**Leggi la documentazione completa qui:** [`PROJECT_DOCUMENTATION.md`](./PROJECT_DOCUMENTATION.md)

Questo documento contiene:
- Analisi completa dei requisiti e scelte strategiche
- Pubblico target e tone of voice (perché "community di data enthusiast")
- Architettura del codice LESS modulare
- Giustificazione completa della palette colori e scelte UX
- Struttura dettagliata di tutte le pagine
- Implementazione di FlexBox e CSS Grid
- Workflow di sviluppo e deployment
- Mappatura completa requisiti-implementazione

## 🚀 Quick Start

```bash
# 1. Installa dipendenze
npm install

# 2. Compila CSS
npm run build:css

# 3. Apri nel browser
open portfolio-personale/index.html
```

## 📂 Struttura Progetto

```
portfolio-personale/
├── index.html          # Homepage
├── cv.html            # Pagina CV
├── contatti.html      # Pagina Contatti
├── css/
│   └── main.css       # CSS compilato (1093 righe)
├── less/              # ⭐ LESS modulare
│   ├── main.less
│   ├── _variables.less    # Design system
│   ├── _base.less         # Foundation
│   ├── _layout.less       # Strutture
│   └── _components.less   # Componenti
└── assets/
    ├── icons/         # Favicon
    └── img/          # Immagini
```

## 🎨 Design System

- **Primario:** #2c5282 (Blu professionale - fiducia, competenza)
- **Accent:** #ed8936 (Arancione caldo - creatività, energia)
- **Fonts:** Lato (body) + Merriweather (headings)
- **Spacing:** Sistema 4px base (8-point grid)

**Per dettagli completi sulla scelta dei colori e UX rationale:** vedi [`PROJECT_DOCUMENTATION.md#5-design-system-e-scelte-cromatiche`](./PROJECT_DOCUMENTATION.md#5-design-system-e-scelte-cromatiche)

## 🛠️ Comandi NPM

```bash
npm run build:css      # Compila LESS → CSS
npm run watch:css      # Watch mode (auto-compile)
npm run build:css:min  # Compila + minifica
npm run build          # Build produzione
```

## ✅ Requisiti Soddisfatti

- ✅ HTML e CSS puri (LESS preprocessore)
- ✅ Bootstrap 5.3.3
- ✅ 3 pagine (Home, CV, Contatti)
- ✅ CV in formato HTML (timeline responsive)
- ✅ Form contatti con validazione
- ✅ Favicon multi-size
- ✅ Menu sticky (responsive)
- ✅ FlexBox + CSS Grid
- ✅ 100% responsive (mobile-first)
- ✅ Meta tags Open Graph

**100% dei requisiti completati**

## 📖 Per Maggiori Informazioni

Consulta [`PROJECT_DOCUMENTATION.md`](./PROJECT_DOCUMENTATION.md) per:

- **Sezione 2:** Perché ogni requisito è stato implementato in quel modo
- **Sezione 3:** Strategia del tone of voice e CTA
- **Sezione 4:** Architettura completa del codice LESS
- **Sezione 5:** Rationale completo della palette colori per UX
- **Sezione 6-10:** Implementazione dettagliata e deployment

## 🌐 Deploy

Il sito è pronto per GitHub Pages. Segui la guida completa in [`PROJECT_DOCUMENTATION.md#9-deployment-e-manutenzione`](./PROJECT_DOCUMENTATION.md#9-deployment-e-manutenzione).

## 📧 Contatti

- **LinkedIn:** [linkedin.com/in/klimovaolena](https://www.linkedin.com/in/klimovaolena/)
- **Tableau Public:** [public.tableau.com/app/profile/olena.klimova](https://public.tableau.com/app/profile/olena.klimova/vizzes)

---

**Fatto con ❤️ e LESS**

© 2025 Olena Klimova - Tutti i diritti riservati
