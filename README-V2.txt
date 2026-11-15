ROMAN AI V2

What's new:
- Brand Lab: organizes brand information supplied by the customer and creates a structured first-pass analysis.
- Sales Message Inbox: creates personalized outreach drafts and keeps them in an owner-review queue.
- JSON backup export/import.
- Existing prospects, orders, captions, and approvals are preserved through V1-to-V2 local data migration.

Important limitations:
- No live AI API is connected in this build. Brand analysis and outreach are structured local drafting tools.
- Instagram links are stored as references only. The app does not scrape Instagram or fetch profile content.
- No DMs are sent automatically. Review, copy, and send manually where appropriate.
- No payment processing or automatic order actions.
- Data remains in local browser storage. JSON backups help move records manually; cloud sync is not enabled.
- Do not place API keys, passwords, or private customer data in this static app.

Deploy:
Upload the contents of this folder (index.html, manifest.webmanifest, sw.js, icon.svg, README-V2.txt) to the root of your existing GitHub Pages repository. Commit changes to the main branch. Refresh the installed Home Screen app after GitHub Pages finishes deploying. If the old version remains cached, close the app fully and reopen it.
