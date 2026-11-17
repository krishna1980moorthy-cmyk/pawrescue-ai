# 🐾 PawRescue AI — Frontend

This is the interactive frontend application for **PawRescue AI** (Goa AI Hackathon 2026), featuring role-based interfaces for:
- 🏥 **Citizen Emergency Portal** (Reporting with photo upload, geolocation, and symptom tags)
- 🚑 **Rescue Team Workspace** (Assigned missions, equipment readiness, team activity)
- 🖥️ **Admin / Dispatcher Dashboard** (Incident triage, AI priority review, smart dispatch, shelters & analytics)

---

## 🚀 Running the Frontend

### Method 1: Local Development Server (Recommended)
From the project root or the `frontend/` folder, run a lightweight HTTP server:

```bash
# Using Python
cd frontend
python -m http.server 3000
```
Then open: [http://localhost:3000](http://localhost:3000)

### Method 2: Direct Browser
You can open `frontend/index.html` directly in any modern browser.

---

## 📁 Files
- `index.html` - HTML shell and mount points (`#app`, `#toast`, `#modal`)
- `style.css` - Custom responsive design system with role-based styling
- `app.js` - Client-side SPA routing, state management, and mock workflow engine
