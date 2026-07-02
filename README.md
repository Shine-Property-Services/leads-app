# leads-app
Hosted UI for the Shine Property Services lead tracker (replaces the Google Sheet).
UI only — no data or secrets here. Data loads at runtime from the gated Supabase
`leads-board` edge function. Open with `?key=PASSCODE`.
Rebuild from `shine-leads/app/index.html` via `shine-leads/scripts/build-pages.ps1`.
