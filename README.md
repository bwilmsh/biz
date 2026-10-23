# biz

A single-page personal dashboard for running a marketing agency: clients, cold calling, outreach, a booked-call calendar, services with GoHighLevel links, and a customer presentation mode.

## Run it

It is one static file. Open `index.html` in a browser, or host it with GitHub Pages
(Settings, Pages, deploy from the `main` branch, root folder).

## What is in it

- Home: outreach, calls, replies, revenue goal gauge, business score, tasks, calendar
- Plus button (top right): track a call, contact, outreach numbers, client or task
- Clients, Cold calling (add, paste from Google Sheets, import Excel or CSV), Outreach, Services
- Services: prices, GoHighLevel links, customer presentation
- Data is saved in your browser (localStorage). It does not sync between devices.

## Notes

- The AI help button only works when the page is opened inside Claude. Elsewhere it shows a short "not available" message.
- Excel and CSV import loads SheetJS from cdnjs, so it needs an internet connection. Pasting rows works offline.
