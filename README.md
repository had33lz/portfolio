# portfolio
# 🌆 3D Light Pole Portfolio

A creative, interactive portfolio built with **React + Three.js**, deployed with **GitHub Pages**.  

## ✨ Concept
The portfolio is presented as a **street light pole in 3D**.  
- A **real-time analog clock** sits on top.  
- **Directional glowing signs** hang from the pole, linking to sections like:
  - About
  - Skills
  - Projects
  - Education
  - Contact & Links  

The **background dynamically changes** with the time of day:
- 🌅 Morning: pastel sky with golden glow  
- 🌞 Afternoon: bright sky, sharp shadows  
- 🌇 Evening: warm gradient sunset  
- 🌌 Night: navy sky with stars + glowing lamp  

## 🎮 Interactivity
- Hover over a sign → it glows & wiggles.  
- Click → camera pans to that section.  
- Subtle **3D parallax** on pole & signs with mouse movement.  
- Ambient details: birds in morning, neon flickers at night, stars twinkling.  

## 🚀 Tech Stack
- [React](https://reactjs.org/)  
- [Three.js](https://threejs.org/) via [@react-three/fiber](https://github.com/pmndrs/react-three-fiber)  
- [Vite](https://vitejs.dev/) for fast dev  
- GitHub Pages for hosting  

## 📂 Structure
- `src/` → main React + Three.js components  
- `public/` → static assets  
- `index.html` → entry point  

## 🔧 Run Locally
```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/portfolio.git

# Open the folder
cd portfolio

# Install dependencies
npm install

# Start development server
npm run dev
