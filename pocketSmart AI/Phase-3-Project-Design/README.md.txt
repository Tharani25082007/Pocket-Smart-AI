# Phase 3: Project Design
PocketSmart AI - Smart Budget & Recommendation Assistant

## System Architecture
- Frontend: HTML, CSS, JavaScript (Jinja2 templates)
- Backend: FastAPI
- Database: SQLite
- AI: Gemini API (with local fallback engine)

## User Flow
Register -> Login -> Choose Planner (Home / Party / Jewelry) -> Enter Budget -> Generate Recommendations -> View History

## Project Structure
- app/ : backend code (ai, routers, services)
- data/ : local catalog data
- run.py : starts the application