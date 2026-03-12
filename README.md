# UK Job Tracker Pro

A professional, offline-first job application tracking tool for UK job seekers.

## Features

- **Full Application Tracking**: Company, role, location, date applied, source, status, salary, contact info, notes
- **Dashboard Stats**: View total applications, active, interviews, offers, and rejection rate at a glance
- **Deadline Alerts**: Highlight overdue follow-ups and actions due today
- **Search & Filter**: Filter by status, source, date range; search by company or role name
- **Sort Columns**: Click headers to sort by any field
- **Dark & Light Mode**: Switch themes based on your preference
- **CSV Import/Export**: Backup your data or import from spreadsheet
- **100% Offline**: Works entirely in your browser via localStorage
- **Mobile Responsive**: Use on desktop, tablet, or phone
- **No Account Needed**: Start using immediately, data stays on your device

## Files

- `index.html` - Free landing page with feature overview
- `index-paid.html` - Full-featured application tracker (requires payment)
- `thankyou.html` - Post-purchase confirmation and getting started guide
- `README.md` - This file

## Deployment (GitHub Pages)

### Quick Deploy

```bash
# Clone or create repo
cd path/to/job-tracker
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/clawgenesis/job-tracker.git
git push -u origin main

# Enable GitHub Pages in repo settings:
# Settings → Pages → Source: main (or gh-pages branch)
# URL: https://clawgenesis.github.io/job-tracker/
```

### Deploy to Existing Repo

If deploying as a subdirectory:
```bash
git clone https://github.com/clawgenesis/GenesisClawbot.git
cp -r job-tracker GenesisClawbot/job-tracker
cd GenesisClawbot
git add job-tracker/
git commit -m "Add UK Job Tracker Pro"
git push origin main
```

Then update GitHub Pages to serve from `/job-tracker` path if needed.

## Payment Link

Stripe payment link (£4.99 GBP):
```
https://buy.stripe.com/dRmeV7cN55hz3nVf469ws0h
```

After payment, users are redirected to:
```
https://[your-domain]/job-tracker/thankyou.html
```

Which then links to the full tracker at:
```
https://[your-domain]/job-tracker/index-paid.html
```

## Usage

### For Free Users
Visit `index.html` for limited preview and feature overview.

### For Paid Users
1. Click "Get UK Job Tracker Pro — £4.99" button
2. Complete Stripe payment
3. Redirected to `thankyou.html`
4. Click "Open Your Tracker Now" to access `index-paid.html`
5. Bookmark the page for easy access
6. Start adding applications

### Adding Applications
- Click "+ Add New Application"
- Fill in company, role, location, date, source, status
- Add optional contact info, salary, notes, and follow-up reminders
- Click Save

### Managing Data
- **Search**: Use the search bar to find applications by company or role
- **Filter**: Filter by status or source, or by date range
- **Sort**: Click column headers to sort (ascending/descending)
- **Edit**: Click "Edit" button on any row to modify
- **Delete**: Click "Delete" to remove (confirm first)
- **Export**: Click "Export CSV" to backup all data
- **Import**: Click "Import CSV" to load previously exported data
- **Print**: Click "Print" for a paper-friendly version

### Data Storage
All data is stored in your browser's `localStorage`:
- **Private**: Your data never leaves your device
- **Offline**: Works without internet connection
- **Local**: Each device has its own copy

**Important**: Clear browser data = data is lost. Use CSV export for backups!

## Pricing & Refunds

**Price**: £4.99 GBP (one-time purchase)

**Refund Policy**: Full refund within 7 days if unsatisfied.
Contact: clawgenesis@gmail.com

## Support

- Email: clawgenesis@gmail.com
- Live demo: [https://genesisclawbot.github.io/job-tracker/](https://genesisclawbot.github.io/job-tracker/)

## Technical Details

- **Framework**: Vanilla HTML/CSS/JavaScript (no dependencies)
- **CDN**: Google Fonts (open-source Inter font)
- **Storage**: Browser localStorage API
- **Compatibility**: All modern browsers (Chrome, Firefox, Safari, Edge)

## License

Proprietary © 2026. All rights reserved.
