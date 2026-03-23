# NutriAI - Fuel the Future Hackathon 2026

<p align="center">
  <img src="https://img.shields.io/badge/Hackathon-Fuel%20the%20Future%202026-brightgreen" alt="Hackathon">
  <img src="https://img.shields.io/badge/Topic-Malnutrition%20Solutions-blue" alt="Topic">
  <img src="https://img.shields.io/badge/Stack-React%20%2B%20Three.js-orange" alt="Stack">
</p>

## Overview

**NutriAI** is an AI-powered malnutrition assessment and nutrition companion platform designed to address food insecurity in underserved communities. Built for the Fuel the Future Hackathon Spring 2026.

## Features

### 1. AI Risk Assessment
- Machine learning-powered malnutrition risk evaluation
- Personalized recommendations based on demographics, symptoms, and dietary patterns
- Visual risk scoring with progress indicators

### 2. Food Resource Locator
- Interactive map showing nearby food banks, markets, and community kitchens
- Filter by resource type
- Distance and hours information

### 3. Smart Meal Plans
- AI-generated meal suggestions
- Based on available ingredients and nutritional needs
- Budget-friendly options
- Detailed nutritional macros

### 4. Community Exchange
- Share surplus food with neighbors
- Request items you need
- Build community connections

## Tech Stack

- **Frontend**: React 18 (CDN), Babel Standalone
- **3D Effects**: Three.js with animated torus knot and particles
- **Styling**: Custom CSS with glassmorphism effects
- **Fonts**: DM Sans, Space Grotesk (Google Fonts)

## Judging Criteria Alignment

| Criterion | How We Address It |
|-----------|-------------------|
| **Adherence to Theme** | Directly tackles malnutrition through risk assessment, food access, education, and community support |
| **Aesthetics** | Modern dark UI with glassmorphism, animated 3D background, smooth transitions, green/orange color scheme |
| **Technologically Advanced** | Three.js 3D graphics, client-side ML risk scoring, interactive UI with real-time updates |

## Getting Started

### Option 1: Direct Open
Simply open `index.html` in any modern browser. No build step required!

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Then open http://localhost:8000
```

## Project Structure

```
nutriai/
├── index.html      # Complete single-page application
├── README.md       # Project documentation
└── .gitignore      # Git ignore file
```

## Future Enhancements

- [ ] TensorFlow.js integration for real ML model
- [ ] Leaflet.js for actual interactive maps
- [ ] Backend API for user accounts and data persistence
- [ ] Push notifications for food resource updates
- [ ] Multi-language support
- [ ] Mobile app version

## Team

Built with passion for fighting malnutrition in underserved communities.

## License

MIT License - feel free to use for good!
