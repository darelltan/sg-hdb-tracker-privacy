# Privacy Policy — SG HDB Tracker

*Last updated: 4 November 2026*

---

## Overview

SG HDB Tracker ("the app", "we", "us") helps people in Singapore research HDB resale flats — searching historical resale transactions, viewing price trends, comparing towns, and estimating affordability, stamp duty, grants, and loans.

We have designed the app to collect as little personal data as possible. In particular, **the financial information you enter (income, budget, buyer type, age) never leaves your device** — all affordability, stamp duty, grant, and loan calculations happen locally on your phone.

This policy explains what data the app handles, where it goes, and your choices.

---

## Information we do NOT collect

To be clear about what we *don't* do:

- We do **not** require you to create an account or log in.
- We do **not** ask for your name, email, phone number, or address.
- We do **not** collect or transmit the financial details you enter (income, budget, buyer type, age). These stay on your device and are used only for on-device calculations.
- We do **not** sell your data to anyone.
- We do **not** use your data for advertising.

---

## Information the app handles

### 1. Search queries sent to our backend

When you search or view price trends, the app sends the **town** and **flat type** you selected (and similar non-personal search parameters) to our backend service, which retrieves the relevant public HDB resale transaction data from Singapore's official open-data source (data.gov.sg).

- This data is **not personal** — it's a request like "3-room flats in Tampines".
- As with any internet request, our backend server receives your device's **IP address** as a technical necessity of the connection. We do not use it to identify you or link it to your searches, and we do not store it for tracking purposes.

### 2. Data stored on your device (not transmitted)

The app saves some information **locally on your device** to improve your experience. This never leaves your phone and is not sent to us:

- Your most recent search and viewed town
- Your saved financial profile (income, buyer type, age) — used only for on-device calculations
- Your saved searches
- Your app settings (e.g. light/dark theme)
- Your analytics/crash-reporting consent choice
- A locally-cached copy of recent results

You can clear this at any time (see "Your choices" below).

### 3. Optional analytics and crash reporting (only with your consent)

The app includes optional analytics and crash-reporting features to help us understand how the app is used and to detect and fix errors. **These are OFF unless you turn them on.**

If you opt in (via Settings → "Share crash & usage reports"), the app uses:

- **PostHog** (analytics) — records anonymous usage information such as which screens are used and general app activity. It uses a randomly-generated anonymous identifier (stored on your device); it does not use your name or any personal identifier. PostHog's servers are located in the EU.
- **Sentry** (crash/error reporting) — records technical information about errors and crashes (such as error messages and the technical state of the app at the time) to help us diagnose and fix problems.

**Your consent is honored immediately.** If you turn this off, the app stops sending analytics and error reports. If you turn it back on, it resumes.

We do not collect the financial figures you enter through these tools — only anonymous usage and technical error information.

*(Note: Sentry and PostHog receive your IP address as part of the technical connection when reporting is active. We have configured both services to discard IP addresses rather than store them.)*

---

## How the data is used

- **Search queries:** solely to retrieve and show you the HDB resale data you asked for.
- **On-device data:** solely to make the app work well for you (remembering preferences, running calculations, showing recent results).
- **Optional analytics/crash data (if you opt in):** solely to understand general usage patterns and to detect and fix bugs, so we can improve the app.

We do not use any of this data to build a profile of you, to advertise, or to sell to third parties.

---

## Third-party services

The app relies on these external services:

- **data.gov.sg** — Singapore's official open-data platform, the source of HDB resale transaction data. Your searches retrieve public data from here (via our backend).
- **Cloudflare** — hosts our backend service that sits between the app and data.gov.sg.
- **Supabase** — stores pre-computed public statistics and reference data (e.g. stamp duty rates) that the backend serves.
- **PostHog** (only if you opt in) — anonymous analytics. See PostHog's own privacy policy for how they handle data.
- **Sentry** (only if you opt in) — crash/error reporting. See Sentry's own privacy policy for how they handle data.

---

## Your choices

- **Analytics/crash reporting:** off by default. Turn it on or off any time in Settings → "Share crash & usage reports". Turning it off stops all reporting.
- **Clearing your data:** You can clear all app data by clearing the app's storage in your device settings, or by reinstalling the app. This removes your saved searches, financial profile, preferences, and any locally-cached data.

---

## Data retention

- **On-device data** stays on your device until you clear it (or uninstall the app).
- **Search queries** to our backend are used to serve your request; we do not maintain a personal log linking searches to you.
- **Analytics/crash data** (if you opted in) is retained by PostHog and Sentry according to their retention policies.

---

## Children's privacy

The app is intended for adults researching property purchases and is not directed at children.

---

## Accuracy of information

The app provides estimates and historical data for research purposes only. Financial figures (stamp duty, grants, loan limits, income ceilings) are based on published government rates and may change. The app is not financial, legal, or investment advice. Always verify figures with official sources (IRAS, HDB, CPF) before making decisions.

---

## Changes to this policy

We may update this policy as the app evolves. Material changes will be reflected here with an updated "Last updated" date.

---

## Contact

If you have questions about this policy or your data, contact us at: **sghdbtracker.app@gmail.com**

---

*SG HDB Tracker is an independent research tool and is not affiliated with, endorsed by, or connected to the Housing & Development Board (HDB), IRAS, CPF Board, or the Government of Singapore.*
