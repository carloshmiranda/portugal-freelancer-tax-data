# Portugal Freelancer Tax Data (2026)

Open-source, machine-readable dataset of Portuguese freelancer tax rules, rates, deadlines, and codes. Maintained for English-speaking freelancers, digital nomads, and D8 visa holders working as *trabalhadores independentes* in Portugal.

**Use this data** in your own apps, spreadsheets, or tax calculators. Licensed MIT.

> Building a tool for Portugal freelancers? Check out [VerdeDesk](https://verdedesk.vercel.app) — the English-friendly recibos verdes companion for expat freelancers.

---

## What's Included

| File | Description |
|------|-------------|
| [`data/irs-brackets-2026.json`](data/irs-brackets-2026.json) | IRS income tax brackets for 2026 |
| [`data/social-security.json`](data/social-security.json) | Social security (SS) rates and rules |
| [`data/vat-rates.json`](data/vat-rates.json) | VAT rates and Article 53 exemption thresholds |
| [`data/deadlines-2026.json`](data/deadlines-2026.json) | Month-by-month tax deadlines for freelancers |
| [`data/withholding-tax.json`](data/withholding-tax.json) | Withholding tax (retencao na fonte) rates |
| [`data/common-cae-codes.json`](data/common-cae-codes.json) | Common CAE activity codes for freelancers |
| [`data/nhr-ifici-2026.json`](data/nhr-ifici-2026.json) | NHR 2.0 / IFICI tax incentive rules |

---

## IRS Tax Brackets (2026)

Portugal uses progressive tax brackets for income tax. Freelancers under the **simplified regime** have a 75% taxable coefficient (only 75% of income is taxed).

| Bracket | Taxable Income (EUR) | Rate |
|---------|---------------------|------|
| 1 | Up to 7,703 | 13.25% |
| 2 | 7,703 - 11,623 | 18.00% |
| 3 | 11,623 - 16,472 | 23.00% |
| 4 | 16,472 - 21,321 | 26.00% |
| 5 | 21,321 - 27,146 | 32.75% |
| 6 | 27,146 - 39,791 | 37.00% |
| 7 | 39,791 - 51,997 | 43.50% |
| 8 | 51,997 - 81,199 | 45.00% |
| 9 | Over 81,199 | 48.00% |

*Source: Autoridade Tributaria, Codigo do IRS Art. 68.*

---

## Social Security for Freelancers

| Parameter | Value |
|-----------|-------|
| Standard rate | 21.4% of relevant income |
| Relevant income | 70% of gross income (services) |
| Effective rate on gross | ~14.98% |
| First-year exemption | 12 months from first invoice |
| Quarterly declaration | January, April, July, October |
| Minimum contribution | EUR 20/month |
| Annual threshold for exemption | Below EUR 2,736.90/year (6x IAS) |

---

## VAT (IVA) Rules

| Rule | Value |
|------|-------|
| Standard rate | 23% |
| Article 53 exemption threshold (2025) | EUR 14,500/year |
| Article 53 exemption threshold (2026) | EUR 15,000/year |
| B2B EU reverse charge | Article 6 CIVA — VAT shifts to client |
| Non-EU clients | VAT exempt (Article 6 CIVA) |
| Grace period for exceeding threshold | Eliminated January 2026 |

---

## Key Deadlines (2026)

| Month | Deadline | What |
|-------|----------|------|
| January | Jan 31 | Q4 2025 SS income declaration |
| February | Feb 25 | Validate e-Fatura invoices for 2025 |
| March | Mar 31 | 2025 annual income confirmation |
| April | Apr 1 | IRS filing period opens |
| April | Apr 30 | Q1 2026 SS income declaration |
| June | Jun 30 | IRS filing deadline |
| July | Jul 31 | Q2 2026 SS income declaration + SS payment |
| August | Aug 31 | IRS refund/payment deadline |
| October | Oct 31 | Q3 2026 SS income declaration |

---

## Withholding Tax (Retencao na Fonte)

| Scenario | Rate |
|----------|------|
| Services to Portuguese companies (standard) | 25% |
| Article 53 exempt freelancers | 0% (exempt) |
| Income below EUR 14,500 (2025) / EUR 15,000 (2026) | Can request exemption |
| Non-resident clients | 0% (no PT withholding) |

---

## Common CAE Codes for Freelancers

| Code | Activity |
|------|----------|
| 62010 | Computer programming |
| 62020 | IT consulting |
| 62090 | Other IT activities |
| 69200 | Accounting and tax advisory |
| 70220 | Management consulting |
| 73110 | Advertising agencies |
| 74100 | Design (graphic, UX, product) |
| 74300 | Translation and interpretation |
| 90030 | Artistic and literary creation |
| 85599 | Education and training |

---

## NHR 2.0 / IFICI (2024 onward)

The Non-Habitual Resident regime was replaced by IFICI starting January 2024.

| Parameter | Value |
|-----------|-------|
| Flat tax rate | 20% on eligible Portuguese-source income |
| Duration | 10 consecutive years |
| Eligibility | Not tax resident in Portugal for previous 5 years |
| Application deadline | March 31 of the year following arrival |
| Eligible activities | Scientific research, qualified professionals, startups, tech |

---

## Related Resources

- [VerdeDesk Tax Calculator](https://verdedesk.vercel.app/tools/tax-calculator) — Free interactive calculator for IRS, SS, and VAT
- [VerdeDesk NHR/IFICI Checker](https://verdedesk.vercel.app/tools/nhr-checker) — Check your eligibility for the 20% flat rate
- [How to Issue a Recibo Verde in English](https://verdedesk.vercel.app/guide/recibo-verde-english) — Step-by-step guide
- [Portal das Financas in English](https://verdedesk.vercel.app/guide/portal-das-financas-english) — Complete translation guide
- [2026 Tax Deadlines Calendar](https://verdedesk.vercel.app/guide/tax-deadlines-2026) — Never miss a deadline
- [VAT Exemption Article 53](https://verdedesk.vercel.app/guide/vat-exemption-article-53-portugal) — Understand the threshold rules

---

## Contributing

Found an error or have updated data? PRs welcome. Please cite official Portuguese tax authority (AT) sources.

## License

MIT — use this data freely in your projects.

## Disclaimer

This data is for informational purposes only and does not constitute tax advice. Always verify with the Autoridade Tributaria or a qualified accountant. Tax rules change annually.
