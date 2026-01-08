# Nova Search – Cinematic AI Assistant UI

Nova Search is a cinematic, futuristic AI search interface built with modern web technologies.  
It combines scroll-snapped storytelling, GPU-powered particle animations, and a minimal AI search experience to create a premium, immersive user interface.

This project is UI-first and designed to act as a foundation for an AI-powered search assistant or conversational system.

---

## Key Features

- Cinematic scroll experience with full-screen vertical snap sections  
- Interactive AI core using Three.js and custom GLSL shaders  
- Smooth real-time animations powered by GSAP  
- Modern, responsive UI using Tailwind CSS  
- Search-trigger-based interaction that changes the AI core state  
- Fully client-side; no backend required for this version  

---

## Tech Stack

- HTML5 – Core structure  
- Tailwind CSS – Styling and layout  
- Three.js – 3D rendering and particle system  
- GLSL Shaders – Particle deformation and motion  
- GSAP – Cinematic animation timelines  
- Canvas (WebGL) – GPU-accelerated visuals  
- Google Fonts – Typography  
- CSS.gg – Icon set  

---

## Project Structure

nova-search/
│
├── index.html # Main UI, shaders, and animation logic
├── README.md # Project documentation
└── assets/ # Optional future assets (models, sounds, images)



Note: This project uses procedurally generated geometry instead of external 3D models to avoid network or loading issues.

---

## How to Run

### Option 1: Open Directly
1. Download or clone the repository  
2. Open `index.html` in a modern browser (Chrome, Firefox, or Edge)

### Option 2: Run via Local Server (Recommended)
python3 -m http.server 5500


Then open:

http://localhost:5500



Running through a local server avoids browser restrictions on advanced WebGL features.

---

## Application Flow

### Sections

1. Hero Section  
   Introduction with branding and cinematic typography

2. Nova Core (Interactive Section)  
   - GPU-driven particle-based AI core  
   - Idle, sensing, and relaxed animation states  
   - Search button triggers focused interaction mode  

3. Footer Section  
   Vision statement, branding, and social placeholders

---

## Shader Animation States

- Running (State 0)  
  Entry and exit motion with disintegration effect  

- Sensing (State 1)  
  High-frequency noise and alert-like motion  

- Relaxing (State 2)  
  Smooth, calm breathing-style deformation  

---

## Design Philosophy

- Dark cinematic background  
- Neon cyan AI identity  
- Minimal UI with high visual impact  
- AI presented as a presence rather than a traditional tool  

---

## Browser Requirements

- WebGL 2.0 support  
- Hardware acceleration enabled  
- Latest versions of Chrome, Firefox, or Edge recommended  

---

## Future Enhancements

- AI backend integration (LLM-based responses)  
- Voice input and output  
- Emotion-aware conversational logic  
- Real-time web search integration  
- VR or AR visualization modes  
- Advanced mobile gesture support  

---

## License

This project is experimental and conceptual.  
You may freely modify and extend it for personal or educational use.

---

## Credits

Designed and developed as a cinematic AI interface concept.  
Focused on future-oriented human–AI interaction design.
