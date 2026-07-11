# 🇱🇰 LankaTaxMate

**Tax deadlines & calculators for Sri Lankan small businesses — FY 2025/26**

A free, lightweight web app that helps Sri Lankan SMEs and sole proprietors stay on top of their taxes. No login, no install — open it in any browser.

**Live demo:** _(deploy on Vercel/GitHub Pages and put your link here)_

## Features (v1)

- **Dashboard** — days until your next tax deadline, everything due within 30 days, key FY 2025/26 tax facts
- **Tax Calendar** — auto-updating monthly deadlines (APIT/PAYE 15th, VAT payment 20th, VAT return & EPF/ETF end of month) plus annual income tax installments and return dates
- **VAT Calculator (18%)** — add VAT to a price, extract VAT from an inclusive price, or compute monthly net VAT payable (output − input)
- **Income Tax Estimator** — FY 2025/26 personal tax with Rs. 1.8M relief and 6% / 18% / 24% / 30% / 36% bands, with per-band breakdown, monthly figure, and effective rate

## Tax rates used (FY 2025/26)

| Band | Rate |
|---|---|
| First Rs. 1,800,000 | 0% (personal relief) |
| Next Rs. 1,000,000 | 6% |
| Next Rs. 500,000 | 18% |
| Next Rs. 500,000 | 24% |
| Next Rs. 500,000 | 30% |
| Balance | 36% |

VAT: 18%. Rates per Inland Revenue (Amendment) Act No. 2 of 2025, effective 1 April 2025.

## Run it

Just open `index.html` in a browser. That's it — pure HTML/CSS/JS, zero dependencies.

## Deploy free

1. Push this repo to GitHub
2. Repo → Settings → Pages → Source: `main` branch → Save
3. Your app is live at `https://perera1325.github.io/lanka-tax-mate/`

(Or import the repo at [vercel.com](https://vercel.com) for a vercel.app URL.)

## Roadmap

- [ ] Business profile (VAT registered? employees?) → personalized calendar
- [ ] Email/WhatsApp deadline reminders (paid tier)
- [ ] Document vault for receipts (paid tier)
- [ ] Multi-client mode for accountants (Rs. 5,000/mo plan)
- [ ] සිංහල / தமிழ் language support

## Disclaimer

Estimates only — not professional tax advice. Verify with [ird.gov.lk](https://www.ird.gov.lk) or a qualified accountant.

## License

MIT
