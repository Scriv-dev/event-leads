# event-leads

A list of 30 UK event companies, AV hire firms and production companies, in [`leads.csv`](leads.csv).

## Columns

| Column | Meaning |
|---|---|
| `company_name` | Trading name |
| `category` | Rough type: AV hire, technical production, event agency, etc. |
| `website` | Company website |
| `location` | Head office or main base (town/city, postcode where known) |
| `contact_email` | Public, general business inbox (blank if none could be confirmed) |
| `contact_page` | Contact/quote page URL where confirmed, otherwise a pointer to the website |
| `phone` | Publicly listed business phone number, where found |
| `source_confidence` | **High** = seen on the company's own site; **Medium** = reputable listing or company-branded page; **Low** = directory/data-broker or old source. "(dated)" = source is several years old |
| `notes` | Where the detail came from and any caveats |

## How it was compiled (November 2026)

- Found with web searches across company sites, industry press, trade directories and Companies House.
- **Only generic, publicly listed business contacts** (e.g. `info@`, `enquiries@`, `sales@`) are included. Named individuals' personal work emails and guessed email patterns from data-broker sites were deliberately left out.
- 11 of the 30 rows have a confirmed email; the rest point to the company website / contact form, because their email was masked or not published in search results.
- Company websites could not be opened directly from the research environment (network restrictions), so details come from search results rather than a live visit to each site. **Check each contact before outreach**, especially rows marked Low or "(dated)".

## Use

These are business contacts for B2B outreach. Follow UK GDPR / PECR rules: include a clear opt-out in emails and honour removal requests.

## Sheffield shortlist

[`sheffield_leads.csv`](sheffield_leads.csv) has 10 event, AV and production companies based in Sheffield, in rough order of size. It has the same columns plus `rank` and `size_signal`.

- **"Biggest" is an estimate.** These are mostly small private firms that file micro-company accounts, so turnover and headcount aren't public. The ranking uses what could be found: directory staff estimates, years trading, public-sector contracts, multi-city offices and client lists.
- **No general contact email could be confirmed for any Sheffield firm.** Where available, the row gives a phone number, website or contact/quote page instead.
- Bigger regional firms within about 40 miles are already in `leads.csv`: AYRE (Leeds) and Universal Live (Bradford).
