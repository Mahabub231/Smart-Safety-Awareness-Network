# Smart-Safety-Awareness-Network

**Smart Safety Awareness Network** — a realtime community safety web app for Bangladesh.

SSAN Bangladesh helps users monitor incidents, report hazards, view alerts on a live map, access emergency services, and trigger SOS requests. The platform supports both **English** and **বাংলা** for better accessibility.

## Features

- **Live Safety Map**
  - Realtime incident markers across Bangladesh
  - User location centering
  - Refreshable map pins

- **Realtime Alerts**
  - Incident feed with severity and type filters
  - Search incidents by keyword
  - High, medium, and low severity labels

- **Incident Reporting**
  - Submit incident reports with:
    - incident type
    - severity
    - description
    - optional photo
    - current GPS location or typed location
  - Edit and delete incidents
  - Reverse geocoding for readable location names

- **AI Safety Assistant**
  - Supports **English + বাংলা**
  - Quick responses for:
    - accidents
    - suspicious activity
    - emergency guidance
    - risk awareness

- **SOS Support**
  - Trigger SOS alerts
  - Share live location
  - Quick emergency call button (`999`)
  - Nearby emergency services display

- **Admin Dashboard**
  - User management
  - Incident management
  - Analytics dashboard for:
    - total incidents
    - users
    - resolution rate
    - risk areas
    - incident type distribution

- **Push Notifications**
  - Firebase Cloud Messaging support
  - Browser notification permission flow

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Maps:** Leaflet.js + OpenStreetMap
- **Authentication & Database:** Firebase Auth + Firestore
- **Storage / Images:** Supabase Storage
- **Notifications:** Firebase Cloud Messaging

## Project Structure

```bash
.
├── index.html
├── styles.css
├── app.js
├── firebase.js
└── supabase.js
