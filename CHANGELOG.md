# Changelog

All notable changes to How Safe are documented here.
Format: [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) · Versioning: [SemVer](https://semver.org/).

## [Unreleased]

## [1.2.0] - 2026-10-09
### Added
- Safer walking routes: candidates from Apple Maps plus detours, scored every 20 m against community safety areas, Safest/Fastest badges, per-area route colouring, one-tap Walk with me.
- Walk with me Live Activity (Lock Screen + Dynamic Island) with I'm safe / +10 min buttons and overdue state.
- App Intents & App Shortcuts: Start Walk with me, I'm safe, Add time, Alert my contacts, Walk status (Siri, Spotlight, Shortcuts, Action button).
- Manage trusted contacts from a running walk.

## [1.1.0] - 2026-10-09
### Added
- Walk with me: check-in timer, trusted contacts, reminder / due / overdue local notifications with actions, pre-filled alert message with latest location, map countdown banner.
- Area alerts: on-device CLMonitor geofences for nearby low-rated areas, after-dark option, 1-hour per-area cooldown.
- Map snapshot image attached when sharing an area.
- Zoom in / zoom out buttons on the map.
### Changed
- "SOS" tab renamed to "Safety" and expanded.
- Privacy policy v1.1: trusted contacts, background location, notifications.

## [1.0.0] - 2026-10-09
### Added
- Community safety map with geohash-based red → green overlay and confidence shading.
- Rating flow: 5 levels, time of day, day type, place type, 14 concern + 10 positive tags, company, source, note.
- Area detail sheet: distribution, day and night scores, top tags, notes with helpful votes and reporting.
- Map filters: time lens, reporter gender, recency, tags, first-hand only, hide low confidence.
- Share link and summary; open in Apple Maps and Google Maps; `howsafe://` deep links.
- SOS tab: region-aware emergency number, location sharing, nearby safe places.
- Optional on-device profile with opt-in anonymous demographics.
- Delete-all-my-data.
