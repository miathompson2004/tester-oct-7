# Jusfruit paycheck

A one-page app that estimates spending money from my next Jusfruit paycheck.

- Pay periods are Sunday–Saturday two-week blocks; payday is the Friday 6 days after (biweekly, one week behind). Reference payday: Fri Sep 18, 2026.
- Spending money = (calendar hours + 5 extra hours) × wage − CPP − EI. Income tax is not subtracted.
- Wage, extra hours, and CPP/EI rates are editable under "Pay settings" (saved in the browser).

## Getting shifts in

- **On claude.ai:** the hosted version reads the "Jusfruit" Google Calendar directly.
- **Self-hosted (this repo):** open `index.html` (or serve it with GitHub Pages) and import a Google Calendar export (.ics) of the Jusfruit calendar.

## Hosting on GitHub Pages

Repo Settings → Pages → Deploy from branch → `main` / root.
