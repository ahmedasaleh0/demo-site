# Security Command Center Demo

A standalone recreation of the 21 main eagle-i demo pages observed in the browser, plus a Demo Data manager. This is an independently authored frontend demo; it does not contain eagle-i's original source code or backend.

Open the hosted site, use the menu to navigate, and select **Demo Data** to generate records or import JSON. Changes are stored in this browser's local storage. Export JSON to back up or transfer a dataset. Each dataset supports up to 1,000 records. You can edit records, resolve findings, simulate investigations and scans, create demo reports, and change the organization name.

Scans, intelligence, chat replies, invites, report schedules, and takedowns are simulated. No real monitoring, messaging, AI service, or takedown request is performed. Charts and some supplementary dashboard metrics are illustrative sample values. Layouts and secondary workflows are approximations based on the visible demo.

The site consists of static files in `dist`. Serve that folder with any static web server. Navigation uses hash routes, so no server rewrite configuration is required.

Validation: JavaScript syntax and data import validation are checked. WebMCP registration is feature-detected; no supported WebMCP validation context was available in this session.
