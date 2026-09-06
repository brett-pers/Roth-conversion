# Bracket Filling — Roth Conversion & Social Security Planner

A single-page, interactive retirement model. It runs a year-by-year projection
(2027–2055) comparing two Social Security claiming ages, and simulates
converting IRA money to Roth each year up to a target income ("filling the
bracket"). Every assumption is a slider — balances, growth rate, living
expenses, Social Security amount, target income, and more — and the charts
and tables update live as you drag them.

It's a static, single HTML file. No build step, no server, no account needed.

## Try it

### Option 1 — open the live link (easiest)

**https://brett-pers.github.io/Roth-conversion/**

If that link 404s, GitHub Pages hasn't been turned on for this repo yet.
To enable it (repo owner only):

1. Go to **Settings → Pages** in this repo
2. Under **Build and deployment → Source**, choose **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)** → **Save**
4. Wait about a minute, then reload the link above

### Option 2 — run it locally (no Pages needed)

1. Click the green **Code** button on this repo → **Download ZIP** (or clone
   the repo with `git clone`)
2. Unzip it, then double-click **`index.html`**

It opens straight in your default browser — nothing to install, no
`npm install`, no local server.

## Using it

- Drag any slider on the left to change an assumption; every chart, stat, and
  table on the page recomputes instantly.
- Toggle **Scenario A / Scenario B** to compare claiming Social Security at
  66y2mo vs. delaying to age 70.
- Your slider positions are saved in your own browser (`localStorage`) so
  they'll still be there next time you open the page in that same browser —
  nothing is sent anywhere or shared between people.
- Click **Reset to defaults** to get back to the example starting point.

## What this is (and isn't)

This is a planning illustration, not tax or investment advice. The starting
slider values are one example household's numbers, not a template you should
assume applies to you — change every input to your own situation before
drawing any conclusions. See the "What this model simplifies" section at the
bottom of the app itself for the full list of caveats (flat returns, a few
approximated tax tables, filing-status assumptions, etc.).
