# 🥊 MMA Calendar

A modern, responsive web application for tracking UFC and MMA events. Features a clean calendar interface, light/dark mode, live iCalendar feed integration, and intelligent caching for optimal performance.

<img width="1185" height="1172" alt="mma-calendar" src="https://github.com/user-attachments/assets/16c02ebe-616c-42e9-9bd0-9b28c45a98c6" />



## ✨ Features

- 📅 **Monthly Calendar View** - Browse UFC events by month with intuitive navigation
- 🌓 **Light/Dark Mode** - Toggle between themes with persistent preference storage
- 📡 **Live Data Feed** - Fetch events from mmacalendars.com iCal feed
- 💾 **Smart Caching** - 6-hour cache with automatic fallback to demo data
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- 🎯 **Demo Mode** - Pre-loaded sample events for instant testing (no internet required)
- ⚡ **Fast Performance** - Vanilla JavaScript, no heavy frameworks
- 🔍 **Event Details** - Click any event to view fighters, location, date/time
- 🔗 **UFC Integration** - Direct links to UFC.com events page
- ♿ **Accessible** - Keyboard navigation, ARIA labels, screen reader support

## 🚀 Quick Start

### Option 1: Demo Mode (Instant)
1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Start exploring! No setup required.

### Option 2: Live Feed
1. Open the app in a browser
2. Select "Live Feed" from the data source dropdown
3. Events will be fetched from mmacalendars.com

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Variables, Grid, Flexbox
- **Vanilla JavaScript (ES6+)** - No frameworks, pure performance
- **ical.js** - iCalendar parsing library (CDN)
- **CORS Proxies** - For cross-origin iCal feed access

## ☁️ Live Demo

[Click here to try it live](https://vojislav77.github.io/mma-calendar)

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/mma-calendar.git

# Navigate to directory
cd mma-calendar

# Open index.html in your browser
# Or use a local server:
npx serve .
# or
python -m http.server 8000
