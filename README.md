# ⚡ NER Smart Logistics — Tactical Admin Command Center ("Excellent & Crazy Hub")

This repository contains the standalone **Admin Tactical Command Center** for NER Smart Logistics.

## Features
- **3D Spatial Radar & 11-Unit Telemetry Grid**: WebGL 3D radar sweep tracking 5 cold-chain trucks and 6 VTOL aerial drones.
- **AI Predictive Landslide & Weather Risk Matrix**: Interactive sliders for rainfall rate, soil moisture, and river surge level to dynamically recalculate terrain risks.
- **Remote Fleet Dispatch & Signal Override**: Emergency Green Wave traffic overrides, VTOL rescue drone launcher, and automatic convoy rerouting.
- **VTOL Drone FLIR Thermal SAR Camera Feed**: Live simulated thermal camera lock scanning mountain passes for stranded convoys.
- **Operations Terminal**: Dark scrolling real-time network log console.

## How to Deploy Standalone

### Option A: Deploy to Vercel (Recommended)
```bash
cd ner_admin_website
npx vercel
```

### Option B: Deploy to Netlify
```bash
cd ner_admin_website
npx netlify deploy --prod
```

### Option C: Serve Locally
```bash
cd ner_admin_website
npx serve .
```
