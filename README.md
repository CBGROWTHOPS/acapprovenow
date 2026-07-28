# AC Approve Now

HVAC lead-gen one-pager. Newport/Astoria design lane (navy + teal).

## Stack
Static HTML/CSS/JS. Single `index.html`. Deploy = Vercel auto-publish on push.

## Live
- Production: https://acapprovenow.com (pending DNS)
- Vercel: https://acapprovenow.vercel.app

## Backend TODO
Form currently logs to console + shows success state. Wire real backend:
- POST endpoint to `/api/lead` (Google Sheet + email routing, or Modernize/Networx ping-post)
- Replace placeholder phone `(754) 757-7436` with a tracked number
