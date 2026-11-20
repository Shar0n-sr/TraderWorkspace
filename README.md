# TraderWorkspace

### Your Trading Development Workspace

**Learn · Record · Improve**

TraderWorkspace is a personal trading productivity and development platform designed to help traders organize their trading activities, document decisions, track learning progress, analyse performance, and build better trading habits.

It brings trade journaling, analytics, learning management, time tracking, task planning, and trading discipline tools together in one workspace.

🌐 **Live Application:** [https://traderworkspace.hatchable.site](https://traderworkspace.hatchable.site)

---

## ✨ Features

### 📊 Dashboard

- Overview of trading activity and development progress.
- Monthly trading statistics.
- Win rate and net realized P&L.
- Learning and trading time summaries.
- Recent trades and task management.
- Daily development missions.

### 📈 Trade Journal

- Record and manage individual trades.
- Track symbols, markets, direction, strategy, and outcomes.
- Record entry, exit, stop-loss, and take-profit prices.
- Track realized profit/loss and trading fees.
- Attach chart screenshots.
- Link TradingView charts.
- Document mistakes, notes, and lessons learned.

### 📉 Trading Analytics

- Total recorded trades.
- Win rate.
- Net realized profit/loss.
- Profit factor.
- Gross profit and gross loss.
- Trading fee tracking.

### 📅 Activity Calendar

- Monthly activity overview.
- View recorded trading, learning, journal, and task activities by date.

### 📚 Learning Hub

- Organize trading knowledge and learning topics.
- Categorize learning materials.
- Track learning progress.
- Record estimated learning hours.

### ⏱️ Time Tracker

- Track learning sessions separately from trading sessions.
- Start, pause, resume, and stop timers.
- Save completed sessions.
- Monitor time spent developing trading skills.

### ✅ Tasks & Planner

- Create and manage tasks.
- Set priorities and due dates.
- Track task progress.
- Organize tasks by completion status.

### 🧠 Mindset & Discipline

- Record emotional check-ins.
- Track emotions such as fear, greed, confidence, and frustration.
- Record emotional intensity and context.

### 🔍 Mistake Analysis

- Identify recurring trading mistakes.
- Analyse mistake patterns using trade journal tags.
- Review trades associated with recorded mistakes.

### 🎯 Monthly Goals

- Set monthly profit targets.
- Define maximum loss limits.
- Set expected trade counts.
- Establish learning-hour targets.
- Document monthly strategy priorities.

### 📝 Reviews

- Create weekly and monthly trading reviews.
- Document mistakes and lessons learned.
- Record future priorities.

### 🧮 Risk Calculator

- Calculate estimated position size.
- Set account balance and risk percentage.
- Calculate risk based on entry and stop-loss prices.
- Specify point value per unit.

### ⚙️ Settings & Data Management

- Personal profile settings.
- Dark and light themes.
- Currency preferences.
- Export and restore application backups.
- Clear locally stored application data.

---

## 💻 Technology Stack

TraderWorkspace is built using lightweight web technologies.

| Technology         | Purpose                                  |
| ------------------ | ---------------------------------------- |
| HTML5              | Application structure                    |
| CSS3               | Styling and responsive interface         |
| Vanilla JavaScript | Application logic and interactions       |
| IndexedDB          | Local application database               |
| LocalStorage       | Browser-side preferences and timer state |
| Service Worker     | Offline functionality and caching        |
| Web App Manifest   | Progressive Web App installation         |

No frontend framework is required.

---

## 📱 Progressive Web App (PWA)

TraderWorkspace is designed as an installable web application.

Supported capabilities include:

- Installable on supported desktop and mobile browsers.
- Standalone application display.
- App icons and installation metadata.
- Service-worker-based application caching.
- Offline application-shell fallback.

Open the live website in a supported browser and use its installation option to add TraderWorkspace to your device.

---

## 🔐 Privacy & Data Storage

TraderWorkspace follows a local-first data storage approach.

- Application records are stored in the browser using IndexedDB.
- Timer state and certain preferences use LocalStorage.
- Backup and restore functionality is available.
- No cross-device synchronization is currently implemented.

**Important:** Your data is associated with the browser and device where you use the application. Clearing browser storage or changing devices can make your records unavailable. Export backups regularly.

---

## 🚀 Run Locally

You can run the static application locally without installing a frontend framework.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/TraderWorkspace.git
```

### 2. Open the project directory

```bash
cd TraderWorkspace
```

### 3. Start a local development server

```bash
cd public
python -m http.server 8000
```

### 4. Open the application

Visit:

```text
http://localhost:8000
```

A local HTTP server is recommended because service workers require a secure context. Localhost is treated as a secure context by modern browsers.

---

## 📂 Project Structure

```text
TraderWorkspace/
│
└── public/
    ├── index.html
    ├── styles.css
    ├── app.js
    ├── manifest.json
    ├── sw.js
    ├── icon.svg
    │
    ├── icons/
    │   └── icon-192.png
    │
    └── brand/
        ├── traderworkspace-primary.svg
        ├── traderworkspace-icon.svg
        ├── traderworkspace-dark-background.svg
        └── traderworkspace-light-background.svg
```

---

## ⚠️ Important Disclaimer

TraderWorkspace is a personal trading organization, journaling, and educational productivity tool.

- It is not a broker or trading execution platform.
- It does not provide investment recommendations.
- Risk calculator results are estimates and may exclude slippage, fees, leverage, and currency conversion.
- Trading analytics depend on the accuracy and completeness of user-entered records.

Always independently verify position sizing and trading risks before making financial decisions.

---

## 👨‍💻 Developer

**Developed by Sharon S R**

Interested in building a website for your business, personal brand, or project?

I also develop custom websites tailored to individual requirements.

📧 **Email:** [srsharon06@gmail.com](mailto\:srsharon06@gmail.com)

---

## 📌 Project Information

| Detail           | Information                                                                      |
| ---------------- | -------------------------------------------------------------------------------- |
| Project          | TraderWorkspace                                                                  |
| Category         | Trading Productivity Software                                                    |
| Application Type | Progressive Web App                                                              |
| Architecture     | Offline-first, local-first                                                       |
| Interface        | Responsive web application                                                       |
| Status           | Live                                                                             |
| Website          | [https://traderworkspace.hatchable.site](https://traderworkspace.hatchable.site) |
| Developer        | Sharon S R                                                                       |

---

**TraderWorkspace — Your progress is built one deliberate decision at a time.**
