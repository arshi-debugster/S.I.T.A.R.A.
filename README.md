# S.I.T.A.R.A. – Water-Aware AI Workload Routing

React + Vite + Tailwind + react-leaflet + recharts + javascript-lp-solver.

## Run in VS Code
1. Install Node.js 18+ from https://nodejs.org
2. Open this folder in VS Code (File > Open Folder)
3. Open terminal (Ctrl + `) and run:

   npm install
   npm run dev

4. Open the URL shown (usually http://localhost:5173)

## Structure
- src/data.js        – data centers, demand zones, latency matrix, constants
- src/model.js       – dynamic WUE, LP solver, baseline routing, KPIs
- src/App.jsx        – state, weather sync, layout
- src/components/    – MapView, NodeCards, Kpis, Charts

## Tune the model
Energy per PFLOPS-hour, zone demand shares and the latency formula are in src/data.js.
