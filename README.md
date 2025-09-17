
# Essence-iel

**Visualiseur de Données des Stations-Service**

Essence-iel is a modern web application for exploring, visualizing, and analyzing fuel station data in France. It provides interactive maps, statistics, and filtering tools to help users find the best fuel prices and station features.

## Features
- Interactive map of fuel stations (Leaflet)
- Price distribution charts and statistics (Recharts)
- Advanced filtering by location, fuel type, price, and services
- Top N stations by price or distance
- Responsive UI with Radix UI and TailwindCSS
- French localization

## Tech Stack
- React 19 + TypeScript
- Vite (bundler)
- TailwindCSS (custom theming)
- Radix UI, Lucide Icons, Phosphor Icons
- Leaflet (maps), Recharts (charts)
- Zod (validation)
- Spark (GitHub integration)

## Getting Started
1. **Install dependencies:**
	```bash
	npm install
	```
2. **Start development server:**
	```bash
	npm run dev
	```
3. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Project Structure
- `src/` — Main source code
  - `components/` — UI and feature components
  - `lib/` — Data services, utilities, translations
  - `types/` — TypeScript types
  - `styles/` — Custom CSS themes

## Data Source
Fuel price and station data is fetched from [roulez-eco.fr](https://donnees.roulez-eco.fr/opendata/instantane).

## License
MIT License. See `LICENSE` for details.
