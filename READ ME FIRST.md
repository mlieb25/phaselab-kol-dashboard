# phaseLab KOL Intelligence Dashboard

**File:** `phaseLab-KOL-Dashboard.html` (1.5 MB) · **Data as of:** 11 August 2026 · **126 KOLs**

## How to open it

1. **Download the file.** In Google Drive, right-click it → **Download**.
2. **Double-click the downloaded file.** It opens in your browser.

> **Drive will not run it in the preview window.** Google Drive stopped hosting web
> pages years ago, so previewing the file in Drive shows the page's source or a blank
> frame, not the dashboard. It has to be downloaded and opened locally. This is normal
> and does not mean the file is broken.

Works in Chrome, Edge, Safari and Firefox. Nothing to install.

## What is in it

One file, no attachments, no server. Everything is embedded — the 126-KOL dataset,
the charting library, the map library and the fonts.

| Tab | What it shows |
|---|---|
| **Overview** | World map of KOL locations, ranked score chart |
| **Analysis** | Two-KOL radar comparison, h-index vs score matrix, segment and domain breakdowns |
| **Vendors & Guidelines** | OEM affiliation split, average score by vendor, guideline leadership |
| **Directory** | All 126 KOLs, searchable and sortable, with a profile drawer per person |

Search, filters and the domain chips cross-filter every view at once.
**Export Filtered CSV** downloads whatever the current filters have selected.

## Two things to know before you rely on it

- **It works offline except the map.** Map tiles are the one thing that still needs an
  internet connection; if you are offline an orange notice says so and every other view
  keeps working.
- **Outreach statuses are stored in your own browser.** If you set someone to
  "In Touch", that is saved on your machine only — it is not shared with the team and it
  does not write back to the tracker. Treat it as a personal scratchpad.

## The score

`KOL Score = Researcher + Clinical + OEM + Guidelines`, each axis out of 100, so 0–400.
It is a **prioritisation device for deciding who to approach first**, not a judgement of
anyone's standing. 121 of the 126 are scored on all four axes; the other 5 carry a partial
sum and are marked `n/4` in the profile drawer.

## Where the data comes from

`04_Deliverables/KOL Tracking.xlsx` — the shared tracker. The dashboard is a read-only
view of it. **To change data, edit the tracker, not this file.** A refreshed dashboard is
rebuilt from the tracker by the pipeline in `dashboard/`.

Questions → Mitchell.
