# Disruptions Tracker

A real-time supply chain intelligence platform designed to track, analyze, and visualize global disruptions across petrochemicals and downstream value chains.

Built to support sourcing, procurement, and strategy teams in identifying risk signals early and acting on them.

---

## Overview

The Disruptions Tracker consolidates geopolitical events, plant outages, logistics constraints, and feedstock volatility into a single interface. It maps disruptions geographically and translates them into actionable insights such as impacted products and value chain exposure.

This tool is designed to bridge the gap between raw event tracking and decision-ready intelligence.

---

## Key Features

### Global Disruptions Map
- Flat 2D map powered by OpenStreetMap
- Visual representation of disruption events across regions
- Size-based markers to indicate impact severity

### Advanced Filtering
- Filter disruptions by:
  - Event type (e.g. Force Majeure, Shutdowns)
  - Region
  - Impact level
- Filters dynamically update both event and product views

### Dual View System
- **Map / Events View**: Displays disruption events and details
- **Products at Risk View**: Shows impacted products based on selected filters

### Dynamic Product Intelligence
- Extracts impacted products directly from disruption events
- Updates in real-time based on active filters
- Eliminates static assumptions and ensures contextual relevance

### Value Chain Context
- Structured overview of broader petrochemical value chains
- Categorized exposure across:
  - Olefins & Polymers
  - Aromatics (BTX)
  - Solvents & Intermediates
  - Amines & Specialty Chemicals
  - Energy Feedstocks
  - Downstream Applications

### Price Signal Indicators
- Displays directional price movements (↑ / ↓) for key chemicals
- Highlights supply-driven pricing pressure across markets

### Clean, Enterprise-Ready UI
- High-contrast dark theme (black + white + lime accent)
- Minimal, non-cluttered interface
- Optimized for readability and usability across user profiles

---

## Product Philosophy

This tool is built on three core principles:

1. **Signal over Noise**  
   Focus on high-impact disruptions that move markets

2. **Context + Real-Time Data**  
   Combine structured industry knowledge with live event data

3. **Actionable Intelligence**  
   Move beyond tracking to enable sourcing and strategy decisions

---

## Use Cases

- Identify supply risks across petrochemical value chains  
- Track force majeure events and production outages  
- Monitor regional disruptions impacting feedstocks  
- Analyze downstream product exposure  
- Support procurement and sourcing decisions  

---

## Tech Stack

- Frontend: HTML, CSS, JavaScript  
- Map: OpenStreetMap (Leaflet.js)  
- Backend/API: Serverless functions (Vercel)  
- Deployment: Vercel  

---

## Deployment

The application is deployed on Vercel with automatic preview environments for branch updates.

### Workflow
- `main` branch → production  
- feature branches → preview deployments  

---

## Future Enhancements

- Supply risk scoring by product  
- Automated insight generation  
- Price forecasting signals  
- Supplier-level disruption mapping  
- Integration with sourcing workflows  

---

## Notes

- Product impact is derived from disruption-level data and may evolve with improved data granularity  
- Price indicators are directional and based on observed market signals  

---

## Author

Built as part of ongoing work in chemical market intelligence and supply chain disruption analysis.
