# Migration Pulse

A lightweight, client-ready dashboard for reporting the progress of a SailPoint Identity Security Cloud (ISC) application migration. It makes the programme status, delivery risks, decisions, and application-level health easy to present in a steering committee.

## Run locally

This is a dependency-free static web application. Serve the repository with any static-file server, then open it in a browser:

```bash
python3 -m http.server 4173
```

Visit `http://localhost:4173`.

## What is included

- Executive migration completion, scope, forecast, and decision indicators.
- Application-level migration tracker with attention and blocked filters.
- Expandable, access-profile-level reporting: migration status, progress, population, and business owner for each profile.
- A criticality-led migration strategy: critical applications receive enhanced assurance first, then high- and medium-criticality applications follow in controlled waves.
- Weekly priorities and an at-a-glance risk radar.
- Add-application workflow for keeping the report current during client meetings.
- CSV export of the application portfolio for offline reporting.

## Sample data

`data/migration-sample.json` is an invented data set that drives the dashboard. Replace it with an export or transformation of your ISC programme data to report your own application and access-profile statuses.
