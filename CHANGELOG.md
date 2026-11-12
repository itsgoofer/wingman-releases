# Changelog

User-facing changes for each Wingman release, newest first.

## 0.7.0-beta (2026-11-12)

### Added
- Other pilots on the map (opt-in, off by default): turn on "Show my position to nearby pilots" in Settings to see other Wingman pilots as violet planes while you fly, and let them see you.
- Only your callsign, position, altitude, heading, speed and aircraft type are shared, only during an active flight, and they disappear about a minute after you stop.
- A new Pilots chip next to Traffic on the map hides or shows them.

## 0.6.0-beta (2026-11-10)

### Changed
- Test release to try the in-app updater. No functional changes.

## 0.5.0-beta (2026-11-10)

### Added
- Auto-update: Wingman checks for new versions and asks before installing, never during a flight. Turn it off in Settings.
- Wear and repair for owned aircraft.
- Aircraft profile autocomplete, add-current-aircraft and field validation.

## 0.4.0-beta (2026-11-09)

### Added
- Show other sim aircraft on the map.
- Weight and fuel units, and the sim data card in Settings.
- Sync the sim's airport data and keep it between sessions.
- Alert on server loss mid-flight and resume after a position jump.
- Only offer airports the sim has.
- Rework the Custom tab planner and route table.
- Custom legs in named trips, 200-job boards and 3-leg job band.
- Replay video export, plane and weather options in the replay.
- Record takeoff and arrival weather per flight.
- Full-window replay with live readout and a redesigned flight card.
- Score runway taxiing, beacon-less aircraft and landing light grace.

### Fixed
- Keep moving traffic that uses scenery aircraft models.
- Detect takeoff off the runway and recover from a dip in the first climb.
- Keep the invoice between legs and clear score and trail on register.
- Reset the flight, score and invoice on every dispatch.
- Ignore telemetry while the sim is in its menus.
- Leave closed runways out of the OurAirports fallback.
- Keep landing phase until the plane has slowed down.

## 0.3.0-beta (2026-11-08)

### Added
- Show the taxi route on the dispatch map.
- Gate-to-runway taxi routes from the sim's taxi network.
- Replace themes with Graphite and accent-colour variants.
- Live sidebar pilot card with change animations and sound.
- Show custom aircraft profiles as a table with an inline editor.
- First-run welcome screen and airport autocomplete for the home airport.
- Tidy the flight invoice and shrink the table text.
- Hard landings cost reputation on completed jobs.
- Retune touchdown, greaser and 10,000 ft grace limits.
- Finish economy tuning and scale free-flight rewards.

### Fixed
- Stop false position jumps after landing and drop ghost flights.

## 0.2.0-beta (2026-11-07)

### Added
- Dispatch with a flight plan view, SimBrief figures, weather briefing and OFP weights.
- Reputation replaces ranks and type ratings.
- Fleet tab with rent, buy and sell; redesigned logbook, profile and cash flow pages.
- Airport radio frequencies, a 100-job board at large airports, and flight cards that draw the track on the map.
- Job/freelance type, sortable columns, rep per flight, invoice layout.
- Dispatch layout, compact gauge bar, remembered weather panels.

### Changed
- Drop the final-speed rule and raise the taxi limit to 40 kt.
- Shipped as a Windows installer.

### Fixed
- Keep the dispatch until Register flight, reset on a new dispatch.
- Clearer free-flight invoice line, not styled as a loss.

## 0.1.0-beta (2026-11-06)

First public beta.
- Live map with trail, SimConnect provider with auto-reconnect, and flight and landing detection.
- Route generator, SimBrief dispatch, and live phase-based scoring.
- Ledger, invoices, logbook, achievements, challenges and airport passport.
- Profile storage with backups and .profile export and import.
- Fleet with rent, ownership, wear and repairs.
- Job board with expiry and penalties, free flights, ferry jobs and rentals.
- Flight replay, shareable flight card, and logbook CSV and JSON export.
- Flights survive restarts; pay follows touchdown rate, and a crash pays nothing.
