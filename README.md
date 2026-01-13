# Military Aircraft Tracker

**Real-time intelligence platform for tracking government, military, and VIP aircraft worldwide.**

[![Website](https://img.shields.io/badge/Website-militaryaircrafttracker.com-00ff00?style=flat-square)](https://militaryaircrafttracker.com)
[![Data Source](https://img.shields.io/badge/Data-ADSB.One-blue?style=flat-square)](https://adsb.one)
[![Aircraft DB](https://img.shields.io/badge/Aircraft%20DB-28%2C000%2B-orange?style=flat-square)](https://militaryaircrafttracker.com/search)
[![Locations](https://img.shields.io/badge/Sensitive%20Locations-420%2B-red?style=flat-square)](https://militaryaircrafttracker.com/locations)

---

## What Is This?

Military Aircraft Tracker is an open-source intelligence (OSINT) platform that monitors high-interest aircraft in real-time using publicly available ADS-B data. Built for researchers, journalists, aviation enthusiasts, and the OSINT community.

**Live at:** [militaryaircrafttracker.com](https://military-aircraft-tracker.com)

<img width="1447" height="748" alt="image" src="https://github.com/user-attachments/assets/5bd0e521-cfd2-4daa-8d78-ab985c9b2f97" />

---

## Features

### Real-Time Tracking
- Live positions updated every 60 seconds via [ADSB.One](https://adsb.one) API
- Flight trails and trajectory history
- Altitude, speed, heading, and squawk codes displayed on tactical HUD

### Aircraft Database (28,000+ entries)
- Presidential and VIP transports (Air Force One, Marine One)
- Reconnaissance & surveillance (RC-135 Rivet Joint, RQ-4 Global Hawk, U-2)
- Military gunships and special operations (AC-130, MH-53 Pave Low)
- Government executive jets and helicopters
- Dictator Alert aircraft from authoritarian regimes

### Sensitive Locations (420+ sites)
- Nuclear facilities (weapons labs, power plants, ICBM bases)
- Military installations (air bases, naval stations, test ranges)
- Government buildings (Pentagon, Capitol, embassies)
- Space launch sites (Cape Canaveral, Vandenberg, Baikonur)
- DMZs and conflict zones

### Flight Path Heatmaps
- Aggregate flight pattern visualization
- Filter by time range, aircraft category, or watchlist
- Identify high-activity corridors and operational patterns

### Emergency Squawk Monitoring
- 7500 - Hijack
- 7600 - Radio failure
- 7700 - General emergency
- 7777 - Military intercept
- Historical squawk event log

### Aircraft Type Intelligence (150+ types)
- Detailed specifications (dimensions, speed, ceiling, range)
- Sensor packages and weapons systems
- OSINT significance and operational notes

---

## Screenshots

| Live Tracker | Flight Heatmap |
|:---:|:---:|
| ![Tracker](https://military-aircraft-tracker.com/static/images/hero-tracking.jpg) | ![Heatmap](https://military-aircraft-tracker.com/static/images/hero-heatmap.jpg) |

| Aircraft Database | Sensitive Locations |
|:---:|:---:|
| ![Database](https://military-aircraft-tracker.com/static/images/hero-database.jpg) | ![Locations](https://military-aircraft-tracker.com/static/images/hero-locations.jpg) |

---

## Data Sources

| Data | Source | License |
|------|--------|---------|
| Live positions | [ADSB.One](https://adsb.one) | Free API |
| Aircraft database | [Plane Alert DB](https://github.com/sdr-enthusiasts/plane-alert-db) | Open source |
| Aircraft images | Wikipedia / Wikimedia Commons | Various |
| Location data | Manually curated from public sources | - |

---

## Report Issues & Contribute

This repository is for **bug reports, feature requests, and data corrections**.

### How to Report

1. **Check existing issues** - Your report may already exist
2. **Use issue templates** - Select the appropriate template
3. **Be specific** - Include aircraft ICAO hex, timestamps, screenshots

### Issue Types

- **Bug Report** - Something isn't working correctly
- **Feature Request** - Suggest new functionality
- **Data Correction** - Wrong aircraft info, missing images, incorrect locations
- **New Aircraft Request** - Add aircraft to the database
- **New Location Request** - Add sensitive location to monitor

### What We're Looking For

- Missing or incorrect aircraft operator/type information
- Better aircraft images (high quality, properly licensed)
- New sensitive locations with coordinates and descriptions
- UI/UX improvements
- Performance issues

---

## Technical Stack

- **Data:** ADSB.One API (1 req/sec rate limit)

### PoC Codebase

A proof-of-concept implementation is available:
**[github.com/hexobandit/AirForceNone](https://github.com/hexobandit/AirForceNone)**

---

## Roadmap

- [ ] Transponder anomaly detection (aircraft appearing mid-flight)
- [ ] Altitude deviation alerts
- [ ] Route deviation detection
- [ ] Aircraft statistics and analytics
- [ ] Operator fleet tracking
- [ ] Push notifications for watchlist

---

## Legal & Ethics

This project tracks **only publicly observable aircraft** using ADS-B transponder signals. All data comes from community-operated receiver networks and public sources.

- We do not interfere with aircraft operations
- We do not access restricted systems
- We do not track individuals, only aircraft
- All location and intelligence data is from public sources

**For aviation safety concerns, contact the appropriate authorities.**

---

## Links

- **Website:** [militaryaircrafttracker.com](https://military-aircraft-tracker.com)
- **Tracker:** [militaryaircrafttracker.com/tracker](https://military-aircraft-tracker.com/tracker)
- **Search:** [militaryaircrafttracker.com/search](https://military-aircraft-tracker.com/search)
- **Locations:** [militaryaircrafttracker.com/locations](https://military-aircraft-tracker.com/locations)
- **Heatmap:** [militaryaircrafttracker.com/heatmap](https://military-aircraft-tracker.com/heatmap)
- **Alerts:** [militaryaircrafttracker.com/alerts](https://military-aircraft-tracker.com/alerts)
- **Changelog:** [militaryaircrafttracker.com/changelog](https://military-aircraft-tracker.com/changelog)

---

<p align="center">
  <sub>Built for the OSINT community</sub>
</p>
