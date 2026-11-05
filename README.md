# Pulse

A small feedback site. Visitors rate their experience on a single feedback card, and the dashboard turns the responses into ratings, sentiment, status tracking and insights. Feedback, Dashboard and Ideas sit on one scrolling page; the top bar jumps to each section.

**Live site:** https://aryatripathi2908-web.github.io/webathon/

## What's in it

- **Give feedback:** pick a face, choose a topic, add an optional comment and name, and submit.
- **Dashboard:** search and filter responses, read automatic insights, track each response from new to resolved, and export a CSV or printable report.
- **Ideas:** upvote the improvements you'd like to see first.
- **Admin view:** move responses along, delete them, and customize the form.

The site opens in a clean white theme. Visitors can pick another accent colour or switch to dark mode.

## Run it

There's no build step. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

## Good to know

- Responses, votes and settings live in the browser's `localStorage`, so visitors don't see each other's feedback yet. A shared backend is planned.
- Admin view has no login, so anyone can turn it on.
