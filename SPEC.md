# Projet2 - Globe News 3D

## Overview
A web application displaying a rotating 3D wireframe globe with geolocated news headlines from the last 24 hours.

## Requirements

### Core Features
1. **3D Globe** (Three.js)
   - Wireframe style representation (low-poly or simple sphere with wireframe)
   - Auto-rotation (slow, continuous)
   - User interaction: drag to rotate manually, pinch/scroll to zoom (limited)
   - Responsive: works on desktop and mobile

2. **News Display**
   - Fetch 50 latest major news headlines worldwide
   - News API: utiliser une API gratuite (GNews ou NewsAPI free tier)
   - Each news item has:
     - Title
     - Description (short)
     - Publication date
     - Source
     - Theme/category tag (General, Politics, Tech, Business, Sports, Entertainment, Science, Health)
   - Filter: only show news from last 24 hours

3. **Geolocation**
   - Each news item mapped to a country/city based on source or keywords
   - Display as markers/points on the globe
   - Click marker to see news snippet

4. **UI/UX**
   - Clean, minimal interface
   - Dark theme (space-like)
   - Mobile-friendly
   - Easy navigation

## Tech Stack
- **Frontend**: Vanilla JS + Three.js (CDN)
- **News API**: GNews.io (free tier: 100 req/day)
- **Deployment**: Static HTML (simple, portable)

## Acceptance Criteria
- [ ] Globe renders and rotates automatically
- [ ] User can drag to rotate globe
- [ ] 50 news items displayed (filtered < 24h)
- [ ] News shown as markers on globe
- [ ] Clicking marker shows news details
- [ ] Works on mobile (touch support)
- [ ] Simple one-page app, no build step required

## Timeline
- Prototype: 2-3 hours
- Test & refine: 1-2 hours