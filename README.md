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
- Expandable AD-to-Entra access-profile comparison: the AD source profile, its Entra equivalent, comparison status, population, and business owner.
- A global percentage of fully migrated applications. An application is migrated only when its Entra application exists and every AD access profile has a matching Entra profile.
- A criticality-led migration strategy: critical applications receive enhanced parity assurance first, then high- and medium-criticality applications follow in controlled waves.
- Weekly priorities and an at-a-glance risk radar.
- Add-application workflow for keeping the report current during client meetings.
- CSV export of the application portfolio for offline reporting.

## Sample data

`data/migration-sample.json` is an invented data set that drives the dashboard. It models the AD application and access-profile baseline alongside the current Entra version. Replace it with an export or transformation of your ISC programme data to report your own parity statuses.
