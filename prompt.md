# 🧠 Prompt to Generate the Interactive Periodic Table Page

Create a fully functional and interactive periodic table web page using only React (via UMD), Tailwind CSS, and no build step. The page should work entirely in the browser as a standalone `.html` file.

## 💡 Requirements

- Use **React** and **ReactDOM** from CDN (UMD builds).
- Use **TailwindCSS** for all styling.
- Use **Babel standalone** in the browser to transform JSX.
- Fetch data from this JSON source:
  `https://rawcdn.githack.com/Bowserinator/Periodic-Table-JSON/master/PeriodicTableJSON.json`
- Layout the periodic table using a **CSS grid** based on the `xpos` and `ypos` properties.
- For each element, display:
  - Symbol
  - Atomic number
  - Name
  - Rounded atomic mass
- Use **colored backgrounds** to represent different categories using Tailwind classes.
- On click, show a **detailed view** with:
  - Name, Symbol, Atomic Number
  - Atomic Mass, Category, Phase
  - Summary, Discovered By, Electron Configuration
  - Bohr model image (`bohr_model_image`)
  - 3D model via `<model-viewer>` if available (`bohr_model_3d`)
- Ensure `<model-viewer>` works properly by importing it as a module.
- Include a color **legend** for all used element categories.
- The final result must work as a single self-contained `.html` file (openable via browser).

## 📊 Category Colors

Assign a unique Tailwind background color class (e.g. `bg-red-200`, `bg-blue-100`, etc.) to each element category. Do not hardcode specific colors—let the model generate a suitable set of distinct colors automatically for visual distinction.


## ✅ Output
A complete, standalone `.html` file that renders the periodic table with interactive behavior, styled via Tailwind, and enhanced with 3D visualization.
