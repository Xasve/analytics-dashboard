# 📊 Analytics Dashboard

Real-time data visualization control panel built with HTML, CSS, JavaScript, and Chart.js. Demonstrates skills in admin interface design, interactive charts, and dynamic data handling.

## Features

- **Live KPIs** — Total revenue, active users, conversion rate, and monthly orders with change indicators
- **Line chart** — Revenue and orders trend with multi-axis support
- **Donut chart** — Traffic source distribution (Organic, Direct, Social, Referral)
- **Hourly bar chart** — User activity by hour of day
- **Horizontal bar chart** — Top 5 products by revenue
- **Customers table** — With engagement progress bar and status badges
- **Date range selector** — Switch between 7, 30, 90 days and full year with regenerated data
- **Simulated live updates** — Refresh button and live user counter every 3 seconds
- **Navigation sidebar** — With Main and Reports sections
- **Responsive design** — Collapsible sidebar on mobile

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, JavaScript ES6+ |
| Charts | Chart.js 4.4 |
| Layout | CSS Grid, Flexbox, Sticky sidebar |
| Typography | Inter + JetBrains Mono |

> **Production stack:** Vue.js · Python (FastAPI) · PostgreSQL · REST API · WebSockets

## Getting Started

```bash
# Clone the repository
git clone https://github.com/Xasve/analytics-dashboard.git

# Open in browser (no server required)
open index.html
```

Or visit the **[Live Demo →](https://xasve.github.io/analytics-dashboard)**

## Project Structure

```
analytics-dashboard/
└── index.html      # Full app with Chart.js via CDN
```

## Layout Preview

```
┌─────────────────────────────────────────────────────────┐
│  Sidebar        │  KPIs (4 cards)                        │
│  - Overview     │  [$48,294] [3,847] [4.2%] [1,284]     │
│  - Analytics    ├──────────────────────────────────────  │
│  - Users        │  Revenue chart  │  Traffic donut       │
│  - Campaigns    ├──────────────────────────────────────  │
│                 │  Top customers table                    │
│  [EB] Admin     ├──────────────────────────────────────  │
│                 │  Hourly bars    │  Top products         │
└─────────────────────────────────────────────────────────┘
```

## Author

**Ethan Barboza** — Full Stack Developer · Freelance
📧 ethan.barboza10@gmail.com
🌐 [xasve.github.io](https://xasve.github.io)
