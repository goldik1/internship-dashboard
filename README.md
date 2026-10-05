# Internship Radar

A tracker for CSE internships, on and off campus, in one place.

**Live demo:** https://goldik1.github.io/internship-dashboard/

## Problem
Internship listings are spread across many sites, and it is easy to miss deadlines. I built this to keep one list, and to be honest about how sure I am that each listing is real and open.

## What it does
- Search and filters: category, region, remote, pay, tracking status
- Relevance score for each listing
- Status tracking (Interested, Applied, Interview and more)
- "My date" field with a countdown, and sort by deadline
- Export and import your tracking as a JSON file
- Every listing carries a verification label, and unconfirmed deadlines are clearly flagged

## Design decisions
- **Honesty over volume:** a wrong deadline is worse than a missing one, so unverified dates are flagged instead of presented as fact.
- **No backend:** a single HTML file with browser storage, so it is free and simple to host.

## Tech
HTML, CSS, vanilla JavaScript, localStorage

## Next steps
Automatic refresh of listings, deadline reminders
