# Facilitator Timer & Team Tracker

**Facilitator Timer** is a lightweight timer and progress-tracking app designed for physical training sessions with small teams. It helps a facilitator manage timing and visually track team progress during interactive labs, team-building activities, or classroom workshops.

---

## 🖼️ What it does

- Set a countdown timer (e.g., 20 minutes)
- Input the number of teams participating
- Display one red dot per team on the left side
- Allow teams to scan a QR code when finished
- Each scan turns a red dot into a green one on the right
- When all teams are done, the timer display changes to ✅ or 🏁

The app can be used in two ways:
- **Electron App (FacilitatorTimer.app)**: Runs as a macOS desktop-style application with no browser distractions.
- **Web Browser**: Accessible at `http://localhost:5050` for the same functionality.

---

## 🚀 How to run the app

### 1. ✅ Prerequisites

- **Docker Desktop** must be installed on your machine (macOS or Windows).
- Internet connection (first time only, to pull the Docker image).

### 2. 🐳 Start the Flask backend (Docker)

Download these two files into a folder on your machine:

- [`docker-compose.yml`](docker-compose.yml)
- [`start-backend.sh`](start-backend.sh)

Make `start-backend.sh` executable if needed:
```bash
chmod +x start-backend.sh
