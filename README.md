# UFC Calendar

A modern, responsive web application for tracking UFC events. Features a clean calendar interface, light/dark mode, live GitHub (ufc-cal) feed integration, and intelligent caching for optimal performance.


<img width="1219" height="1064" alt="ufcc" src="https://github.com/user-attachments/assets/78e42403-1348-49ac-a5d3-209134f56b06" />


## Features

- **Monthly Calendar View** - Browse UFC events by month with intuitive navigation
- **Light/Dark Mode** - Toggle between themes with persistent preference storage
- **Live Data Feed** - Fetch events from mmacalendars.com iCal feed
- **Smart Caching** - 6-hour cache with automatic fallback to demo data
- **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- **Demo Mode** - Pre-loaded sample events for instant testing (no internet required)
- **Fast Performance** - Vanilla JavaScript, no heavy frameworks
- **Event Details** - Click any event to view fighters, location, date/time
- **UFC Integration** - Direct links to UFC.com events page
- **Accessible** - Keyboard navigation, ARIA labels, screen reader support

## Quick Start

### Option 1: Demo Mode (Instant)
1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Start exploring! No setup required.

### Option 2: Live Feed
1. Open the app in a browser
2. Select "Live Feed" from the data source dropdown
3. Events will be fetched from GitHub (ufc-cal)

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Variables, Grid, Flexbox
- **Vanilla JavaScript (ES6+)** - No frameworks, pure performance
- **ical.js** - iCalendar parsing library (CDN)
- **CORS Proxies** - For cross-origin iCal feed access

## Live Demo

[Click here to try it live](https://vojislav77.github.io/ufc-calendar)

## Installation

```bash
# Clone the repository
git clone https://github.com/vojislav77/ufc-calendar.git

# Navigate to directory
cd mma-calendar

# Open index.html in your browser
# Or use a local server:
npx serve .
# or
python -m http.server 8000
