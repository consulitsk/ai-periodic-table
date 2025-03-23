# 🧪 Interactive Periodic Table (LLM Experiment)

Tento projekt je výsledkom experimentu so zameraním na generovanie kompletnej interaktívnej webovej stránky **iba pomocou generatívneho LLM agenta (ChatGPT)** – bez manučného programovania.

Cieľom bolo overiť, do akej miery je možné zadať iba jednoduché požiadavky a nechať LLM vygenerovať:

- štruktúru aplikácie (HTML, JS, CSS)
- logiku práce s dátami
- dizajn (TailwindCSS)
- interaktivitu (React, JSX)
- 3D vizualizácie (model-viewer)

---

## 🔍 Funkcie

- **Plná periodická tabuľka** prvkov s údajmi načítanými zo zdroja JSON.
- **Zvýraznenie kategórií** pomocou farebného rozlíšenia.
- **Detailný pohľad** na každý prvok vrátane:
  - názvu, symbolu, čísla
  - hmotnosti, fázy, kategórie
  - zhrnutia, objaviteľa a konfigurácie elektrónov
  - obrázka Bohr modelu
  - **3D modelu atómu** cez `<model-viewer>`
- **UI bez buildovania** – funguje ako čistý `.html` súbor.

---

## 📦 Technológie

| Technológia      | Použitie                                 |
|------------------|-------------------------------------------|
| React (UMD)      | Interaktivita (bez bundlerov)             |
| TailwindCSS      | Štýlovanie rozloženia a prvkov            |
| Babel Standalone | JSX transformácia v prehliadači           |
| model-viewer     | Zobrazenie 3D modelov prvkov              |
| PeriodicTableJSON| Dátový zdroj chemických prvkov            |

---

## 🚀 Spustenie

1. Stiahni alebo naklonuj tento repozitár.
2. Otvor súbor [`index.html`](./index.html) v bežnom prehliadači.
3. Hotovo – stránka je plne funkčná bez nutnosti buildovania.

---

## 🧠 Motivácia

Tento projekt vznikol ako **demonštrácia možností LLM nástrojov** pre automatizované generovanie UI komponentov, vizualizácií a logiky bez manuálneho kódovania. Využíva verejne dostupné dátové zdroje a moderné web technológie v čistej HTML forme.

---

## 📚 Zdroje

- [Bowserinator/Periodic-Table-JSON](https://github.com/Bowserinator/Periodic-Table-JSON)
- [model-viewer](https://modelviewer.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- [React UMD Builds](https://reactjs.org/docs/cdn-links.html)

---

## ⚠️ Upozornenie

Tento projekt slúži len na experimentálne účely. Neobsahuje optimalizácie, testy ani pokročilé zabezpečenie.

---

## 💡 Možnosti rozšírenia

- Vyhľadávanie a filtrovanie podľa kategórie/skupiny
- Podpora viacerých jazykov
- Export do PDF
- Napojenie na AI/LLM dotazovanie (napr. „ktorý prvok je najľahší kov?“)

---

> Vygenerované s pomocou ChatGPT – od nuly až po plne funkčnú aplikáciu ✨
