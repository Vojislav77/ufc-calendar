# UFC Calendar

A modern, responsive web application for tracking UFC events. Features a clean calendar interface, light/dark mode, live GitHub (ufc-cal) feed integration, and intelligent caching for optimal performance. Everything lives in a single `index.html` file — no build step, no dependencies to install.


<img width="1219" height="1064" alt="ufcc" src="https://github.com/user-attachments/assets/78e42403-1348-49ac-a5d3-209134f56b06" />


## Features

- **Monthly Calendar View** - Browse UFC events by month with arrow-key and swipe navigation
- **Light/Dark Mode** - Toggle between themes with persistent preference storage
- **Live Data Feed** - Fetch events from the GitHub ufc-cal iCal feed
- **Smart Caching** - Live events cached for 6 hours for faster repeat visits
- **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- **Demo Mode** - Sample events generated around upcoming weekends, so they never go stale (no internet required)
- **Fast Performance** - Vanilla JavaScript, no heavy frameworks
- **Event Details** - Click any event to view fighters, location, date/time
- **UFC Integration** - Direct links to UFC.com events page
- **Accessible** - Keyboard-navigable event cards, ARIA labels, screen reader support
- **Secure Rendering** - All remote feed content is HTML-escaped before display

## Quick Start

### Option 1: Demo Mode (Instant)
1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Start exploring! No setup required.

### Option 2: Live Feed
1. Open the app in a browser
2. Select "Live Feed" from the data source dropdown
3. Events will be fetched from GitHub (ufc-cal)

### Option 3: AppImage (Linux Desktop App)
1. Download `UFC-Calendar-1.0.0.AppImage` from the [Releases](https://github.com/vojislav77/ufc-calendar/releases) page
2. Make it executable and run:
   ```bash
   chmod +x UFC-Calendar-1.0.0.AppImage
   ./UFC-Calendar-1.0.0.AppImage
   ```
3. The app runs as a native desktop window (WebKitGTK) with the UFC Calendar icon in the window titlebar and taskbar. No installation required.

> The AppImage bundles everything it needs, including `ical.js`, so it works offline in Demo mode. Live Feed mode requires an internet connection.

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Variables, Grid, Flexbox
- **Vanilla JavaScript (ES6+)** - No frameworks, pure performance
- **ical.js** - iCalendar parsing library (CDN)
- **GitHub Raw** - Direct, CORS-friendly access to the ufc-cal iCal file

## Project Structure

```
ufc-calendar/
├── index.html      # The entire application (HTML + CSS + JS)
├── favicon.png     # Site icon
└── README.md       # You are here
```

The application is fully self-contained in `index.html`; the only external
dependency is the ical.js library loaded from a CDN.

## Live Demo

[Click here to try it live](https://vojislav77.github.io/ufc-calendar)

## Installation

```bash
# Clone the repository
git clone https://github.com/vojislav77/ufc-calendar.git

# Navigate to directory
cd ufc-calendar

# Open index.html in your browser
# Or use a local server:
npx serve .
# or
python -m http.server 8000
```

### Linux Desktop (AppImage)

Download the AppImage from the [Releases](https://github.com/vojislav77/ufc-calendar/releases) page:

```bash
chmod +x UFC-Calendar-1.0.0.AppImage
./UFC-Calendar-1.0.0.AppImage
```

> Tip: After updating the app, do a hard refresh (Ctrl+Shift+R / Cmd+Shift+R) if
> the browser is still showing cached older content.
