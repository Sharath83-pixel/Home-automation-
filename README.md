# VoxHome — Voice Controlled Home Automation frontend

Responsive React dashboard for a diploma project using the AI Thinker VC-02 voice recognition module. This is a **frontend-only demo**: switches and typed commands change the interface only. No backend, database, microphone access, or physical hardware control is connected.

## Requirements
- Node.js 18 or newer (Node.js 20 LTS recommended)
- npm (included with Node.js)
- A code editor such as VS Code

## Run locally
1. Download and extract this ZIP.
2. Open Terminal in the extracted folder:
   ```bash
   cd voice-home-automation-frontend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open the local URL shown in Terminal (usually `http://localhost:5173`).

Build for production with `npm run build`.

## Included
- Project introduction
- Hardware cards with reference pictures
- Prerequisites and safety notes
- Working principle and example voice phrases
- Conceptual circuit/block diagram
- Interactive simulated light, fan and pump controls
- Typed demo commands such as `turn on the light`, `turn off the fan`, and `start the pump`
- Responsive desktop, tablet and mobile layout

## Customize
- React interface: `src/App.jsx`
- Styling and responsive breakpoints: `src/App.css`
- Page title and metadata: `index.html`

Hardware pictures and Google Fonts load from external URLs, so those assets require an internet connection. The frontend itself runs locally.

## Safety note
The diagram is conceptual, not a verified pin-by-pin schematic. Verify the VC-02 documentation, output electrical characteristics, relay trigger requirements, load ratings and power supply before building. Never connect mains voltage directly to the voice module. Have a qualified instructor review mains-powered wiring.
# Home-automation-
