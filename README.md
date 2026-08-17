# Debt Master

A satirical incremental game in which you play the banker who pulls the strings.
You create debt the way other people grow tomatoes, you sell insurance that covers
nothing, you raise rates at the worst possible moment — and when the anger becomes
unmanageable, you schedule the collapse yourself.

**Play it:** https://USERNAME.github.io/debt-master/

---

## What's in it

- **10 instruments of origination**, from the Payday Kiosk to the Lunar Collateral Vault
- **24 doctrines** — Fluoride Rebate Program, Black-Helicopter Collections, Birds Are Not Real (They're Auditors), The All-Seeing Audit
- **A policy rate** you set yourself: higher yield, angrier public. Rate changes take
  effect at the next fiscal quarter, like a real policy meeting
- **Civil unrest**, which becomes a revolt if you let it reach 100% — or Seized Assets
  if you harvest it first by engineering the crisis on your own schedule
- **A prestige tree** in three branches (Capital, The State, Information), plus a
  repeatable capstone that never runs out
- **10 dossiers** that unlock after your first engineered crisis

## Controls

| Action | How |
|---|---|
| Sign a loan | Click the button, or press **Space** |
| Buy in bulk | The ×1 / ×10 / ×100 / MAX toggle above the operations list |
| Save | Automatic, every 10 seconds, in your browser |
| Move a save to another machine | **Export** gives you a string, **Import** takes it back |
| Start over | **Wipe** |

Progress is stored in your browser's local storage. Clearing your browsing data
clears the game — use **Export** if you care about a run.

## A note on the satire

The absurd conspiracies are jokes: reptilians, the moon as collateral, pigeons as
auditors, the sub-basement under Denver airport.

The **dossiers** are not. Each one is built on a documented, widely reported mechanism —
the revolving door between regulators and the firms they supervise, legislators trading
around information they receive in committee, the issuer-pays model at the ratings
agencies, deferred prosecution agreements, loan conditionality, weekend bailouts, the
measured return on lobbying spend. The actors in them are deliberately unnamed
archetypes, never real individuals. The target is a set of incentives, not a group of
people.

## Running it

It is one static HTML file with no dependencies, no build step and no server. Open
`index.html` in a browser, or drop it on any static host.

### Deploying to GitHub Pages

1. Create a repository named `debt-master`
2. Upload `index.html` (and this README) to the root of the `main` branch
3. **Settings → Pages → Source: Deploy from a branch → `main` / `root` → Save**
4. Wait about a minute; the URL is `https://USERNAME.github.io/debt-master/`

## Licence

MIT — do what you like with it.
