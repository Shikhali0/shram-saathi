# Shram Saathi

A volunteer dashboard for a campus drive that helps workers (mess staff, housekeeping, security, electricians and plumbers) learn about and register for national welfare schemes in India.

## What it does

- **Check a worker:** answer a few questions and see which of 15 schemes the worker is eligible for, with a one-line pitch, the documents to bring and the official form for each.
- **All 15 schemes:** benefits, cost, eligibility, where to register and the official source for each scheme.
- **Forms:** official application forms (Gujarati, Hindi, English) linked from the issuing department's website.
- **How to talk:** a conversation script, common questions from workers and helpline numbers.
- **Today's tally:** counts of workers met, registrations and referrals.

## Privacy

Nothing is stored. The tally lives only in the open browser tab and holds no names or ID numbers. There is no backend, database or analytics.

## Schemes covered

e-Shram, PMJJBY, PMSBY, PM-SYM, Atal Pension Yojana, Ayushman Bharat PM-JAY, PM Jan Dhan, PM MUDRA, NFSA / One Nation One Ration Card, PM Awas Yojana, Sukanya Samriddhi, PM Matru Vandana, PM Ujjwala, Janani Suraksha Yojana, and Gujarat state schemes (Ganga Swarupa widow pension, BOCW e-Nirman card).

Facts were checked against official government websites on 20 October 2026. Recheck them before each drive.

## Deploy

It is a single static file (`index.html`) with no build step. On Vercel, import the repository and keep the default settings (Framework preset: Other, no build command, output directory: root).
