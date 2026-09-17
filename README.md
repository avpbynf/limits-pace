# Limits Pace

A small offline PWA that shows where weekly usage should stand right now, so that a 100% weekly
budget is spent evenly over seven days instead of in bursts.

The week starts at a fixed weekday and time. The budget is spread over the working hours of each
day, so the target stays flat overnight: at the start of the day it matches the end of the
previous one, and each full working day adds a seventh. The reset day and the working hours are
set under "Début de semaine" and kept in the browser.

Live at https://avpbynf.github.io/Limits-Pace/, installable from the browser menu on a phone.

## Run locally

It is plain static files, any server does:

```bash
python3 -m http.server 8765
```

Then open `http://127.0.0.1:8765`. Installing it as an app needs HTTPS, which the published page
has and this server does not.
