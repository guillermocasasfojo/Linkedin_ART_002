# Philips 12NC Reference

A public reference for the **Philips 12NC** — the twelve-digit part numbering system introduced by Philips in 1963, still in use today across an ecosystem of former Philips companies and their suppliers.

Very little about the 12NC is documented online. This repository collects reference tables reconstructed from publicly available sources: historical references, academic research, and vintage collections from the Philips ecosystem. It accompanies the article **[The Philips 12NC System](ADD-LINKEDIN-ARTICLE-LINK-HERE)** published in the *Thinking About PLM* newsletter.

## Structure of a 12NC

A 12NC consists of twelve decimal digits, conventionally grouped as `NNNN NNN NNNNN` (4 · 3 · 5):

| Digits | Meaning |
|--------|---------|
| 1–2 | Product Group (*Hoofd-Industrie Groep*, HIG) |
| 3–4 | Coding Centre |
| 5–6 | Subcoding Centre |
| 7 | Category |
| 8 | Subcategory |
| 9–11 | Product Code |
| 12 | Revision |

## Reference tables

- [Digits 1–2: Product Groups (HIG)](product-groups-hig.md) — also available as [CSV](product-groups-hig.csv)
- [Digits 3–4: Coding Centres](coding-centres.md) — also available as [CSV](coding-centres.csv)

## Disclaimer

This is a historical reconstruction exercise based on available evidence. It is not an official Philips publication, and it aims to understand the principles behind the numbering logic, not to provide an authoritative registry. Corrections and additions are welcome — please open an issue or a pull request.

## Sources

- Griens J.H., *"PDM in de PPD: analyse en herontwerp van het productgegevensbeheer bij de ontwikkelingafdeling van Philips Display Components"*, Eindhoven University of Technology, 1999.
- Gerard's Radio Corner *(https://gerardtel.nl/Articles/PhilType.htm#thilet)*
- Maximus-Randd *(https://www.maximus-randd.com/tv-tuner-history-pt2.html#12nc)*

## Author

Guillermo Casas Fojo — *Thinking About PLM* newsletter *(https://www.linkedin.com/newsletters/thinking-about-plm-7479924860673114112/)*
