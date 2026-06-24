# Beaver Telemetry - Tahsis Salmon Fishing Reunion App

## Project Overview
- **Purpose**: A fun, offline-first Progressive Web App (PWA) for a 37-year Ohio State University Aerospace Engineering reunion trip. Four friends (including Tim) are flying on a De Havilland Beaver seaplane from Seattle to Westview Marina in Tahsis, BC (Vancouver Island) for salmon fishing in Nootka Sound / Esperanza Inlet.
- **Theme**: Aerospace + fishing mashup ("mission logs"). Light-hearted competition and nostalgia.
- **Key Personality**: Humorous references to Professor Rudolph Edse (thermodynamics professor — aged German who worked with Werner von Braun; quirk: wiped the blackboard at the start of every class then filled it perfectly from memory).
- **Tech**: Single self-contained HTML file. Tailwind CSS (CDN), Chart.js (CDN), vanilla JavaScript. Fully offline with localStorage. JSON export/import for group sharing.

## Core Features (Current Implementation)
- **Crew Manifest**: Editable list of 4 crew members (default: Tim + placeholders). Add/remove.
- **Log Catch Form**:
  - Angler (dropdown from crew)
  - Location (preloaded Tahsis-area spots: Westview Marina, Esperanza Inlet points like Rosa Harbour / Grassi Island / Ferrer Point, Nootka Sound / Yuquot Point, Catala Island Glory Hole, + Custom)
  - Species (Chinook/King, Coho, Sockeye, Pink, Chum)
  - Weight (lbs), Length (in), Gear/Notes, Story/Black Box notes
- **Edse Analysis Button**: Random humorous thermodynamics commentary referencing the professor’s blackboard ritual and von Braun background.
- **Tabs**:
  - Log Catch
  - Mission Logs (list view)
  - Dashboard (bar chart of fish counts + leaderboard by total weight)
  - Story Vault (add reflections / Edse memories)
- **Controls**: Export JSON, Import JSON (for merging crew data), Reset.
- **PWA**: Basic manifest for "Add to Home Screen" support.

## Goals for Refinement
- Make it more polished, mobile-friendly, and fun for the reunion.
- Improve usability during the trip (spotty or no internet at the lodge).
- Enhance Edse humor and nostalgia without clutter.
- Better data visualization and sharing.
- Possible additions: Photo placeholders (File API / base64), simple cast physics simulator (aerospace flavor), daily challenges, end-of-trip report generator, dark/outdoors theme consistency.
- Keep it as a **single HTML file** for easy distribution on the plane.

## Current Strengths
- Works completely offline.
- Simple and focused.
- Good foundation with Tailwind and Chart.js.

## Desired Improvements / Tasks for Copilot
1. Polish UI/UX (better mobile layout, icons, animations, color scheme with salmon/aerospace vibes).
2. Enhance Edse integration (more quote variety, badge system).
3. Improve data handling (better merging, duplicate prevention, summary stats).
4. Add lightweight features (e.g. simple projectile "cast simulator", photo upload display, printable/export-to-PDF trip report).
5. Bug fixes / robustness (form validation, empty states, chart resizing).
6. Accessibility and performance.
7. Any other ideas that fit the fun reunion + fishing + aerospace theme.

Provide updated full HTML code after changes. Keep dependencies minimal (CDNs only).

Current full code (paste the entire HTML I gave you here if needed for context).

Start by reviewing the existing code and suggest prioritized improvements.