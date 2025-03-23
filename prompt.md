Create a fully functional HTML page that displays an interactive periodic table of elements using React (via UMD), Tailwind CSS, and Babel standalone. The page must be a single `.html` file with no build step.

Requirements:
- Use React 18 and ReactDOM via UMD CDN.
- Use TailwindCSS for styling.
- Use Babel standalone for JSX transformation in-browser.
- Load JSON data from: https://rawcdn.githack.com/Bowserinator/Periodic-Table-JSON/master/PeriodicTableJSON.json
- Render a responsive grid layout based on `xpos` and `ypos`.
- Each element tile must display:
  - Symbol (large, bold)
  - Atomic number
  - Name
  - Atomic mass (rounded to 3 decimals)
- Use `min-w-[3.5rem]` and `w-full` to allow tiles to fill the grid cell while preserving a minimum width.
- Color tiles by category using Tailwind background classes.
- Include a legend with category labels and matching colors.
- Clicking an element opens a modal:
  - Max height: 90vh, scrollable
  - Closes on clicking overlay
  - Shows detailed info: name, symbol, number, mass, category, phase, summary, discovered_by, electron configuration, link to Wikipedia.
  - If `bohr_model_3d` is available, render using `<model-viewer>` with `bohr_model_image` as poster.
  - If only `bohr_model_image` exists, show it as fallback.
- Include model-viewer via:
  - `<script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>`
  - `<script nomodule src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>`
- Ensure grid is scrollable horizontally on screens smaller than 1200px using CSS media queries.