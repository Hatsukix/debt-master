# Debt Master

A satirical incremental game in which you play the banker who pulls the strings.
You create debt the way other people grow tomatoes, you sell insurance that covers
nothing, you raise rates at the worst possible moment — and when the anger becomes
unmanageable, you schedule the collapse yourself.

**Play it:** https://hatsukix.github.io/debt-master/

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
- **Milestone tiers** — every 10th, 25th, 50th unit of an instrument makes all of them better

### Chapters

New systems open on your count of engineered crises, not on the clock.

| | | opens at |
|---|---|---|
| **I** | Origination, doctrines, the policy rate | — |
| **II** | **The Trading Floor** — five sectors with opposite sensitivities to your own rate. Your decision lands next quarter, so you are the only one who knows. Positioning inside that gap raises Regulatory Attention, and an investigation settles for a fine that is always smaller than the quarter it came from. | 3 crises |
| **III** | **The Token** — issue your own currency, keep 80% as a founder allocation, buy hype, seed a reserve, open a staking yield paid out of the next depositor. Then decide when to pull the liquidity. | 7 crises |
| **IV** | **Conflicts** — a siege, not a battle. Influence accrues a few points a quarter and cannot be rushed with money, so campaigns are measured in quarters. Nine targets in three tiers: inquiries, rival institutions, sovereigns. Everything you are still besieging pushes back until it falls. | 11 crises |
| **V** | **Monetary Reform** — the meta-prestige. You do not collapse the institution this time, you collapse the money. Every contract is redenominated overnight in a currency you issue. It erases everything a crisis erases and then the things a crisis spares — the Pyramid, the token, every conflict won, your Seized Assets — and re-locks every chapter. Only the **Charter** crosses over, because the Charter is the part that says what money is. | 16 crises |

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

### The Charter

Bought with **seigniorage** — the profit an issuer makes simply by issuing. Nine clauses, written in
order, spanning roughly six eras: your name on the notes, an inherited ledger, doctrines that were
never repealed, desks that were never dismantled, a currency board, a second signature, a reform that
does not inconvenience the reformers, reserve currency status, and finally the clause explaining that
no further reforms are required.

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
4. Wait about a minute; the URL is `https://hatsukix.github.io/debt-master/`

## Licence

MIT — do what you like with it.
