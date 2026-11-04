# Finland: rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations in Finland: deposits, rent increases, termination notice, lease terms, registration and landlord duties, with a primary-source link for every value.

- Version: 1.0
- Facts checked: 2026-11-04
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index), [UK repository](https://github.com/izirento/izirento-uk-rent-index), [catalog of country repositories](https://github.com/izirento/izirento-rent-index-international)
- EU rent price change for all 27 member states: [izirento-eu-rent-index](https://github.com/izirento/izirento-eu-rent-index)
- Licence: CC BY 4.0 (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). Laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## IziRento pages for this country

- [Home, Suomi](https://izirento.com/fi-fi)

## Key facts

| Topic | Field | Value | Source |
| --- | --- | --- | --- |
| tenancy_law | Main law | Act on Residential Leases (asuinhuoneiston vuokrauslaki) 481/1995; the consolidated text read shows amendments up to 16.6.2026/531. | [Finlex (Ministry of Justice, Finland)](https://www.finlex.fi/fi/lainsaadanto/1995/481) |
| deposit | Maximum deposit | A term requiring security greater than three months of rent is void (section 8). | [Finlex (Ministry of Justice, Finland)](https://www.finlex.fi/fi/lainsaadanto/1995/481) |
| deposit | Return deadline | Security must be returned or released, or a written notice of withholding given, without delay and at the latest within 14 days of the end of the lease or of handing over possession (section 8). | [Finlex (Ministry of Justice, Finland)](https://www.finlex.fi/fi/lainsaadanto/1995/481) |
| termination | Landlord notice period | When the landlord terminates, the notice period is four months if the tenancy has lasted at least two years immediately before termination, otherwise three months; terms shortening the landlord's notice period are void (section 52). | [Finlex (Ministry of Justice, Finland)](https://www.finlex.fi/fi/lainsaadanto/1995/481) |
| termination | Tenant notice period | When the tenant terminates, the notice period is one month (section 52). | [Finlex (Ministry of Justice, Finland)](https://www.finlex.fi/fi/lainsaadanto/1995/481) |
| rent_level_change | Rent price change, 2025 annual average (HICP actual rentals for housing) | 1.0 percent (2024: 2.5 percent) | [Eurostat](https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/data/prc_hicp_aind?format=JSON&lang=EN&coicop=CP041&unit=RCH_A_AVG&geo=FI&time=2025) |
| rent_level_change | Rent price change, December 2025 year on year (HICP actual rentals for housing) | 0.2 percent | [Eurostat](https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/data/prc_hicp_manr?format=JSON&lang=EN&coicop=CP041&unit=RCH_A&geo=FI&time=2025-12) |

## Suomi

**Suomi.** Avoin data vuokrasta ja vuokranantajan velvollisuuksista: vakuus, vuokrankorotus, irtisanomisajat ja vuokrasopimus; jokaisella arvolla on linkki viralliseen lähteeseen.

*Tiedot annetaan sellaisenaan ilman mitään vastuuta. Järjestämme vain sen, mitä viralliset lähteet julkaisevat. Lait muuttuvat: tarkista jokainen arvo linkitetystä alkuperäislähteestä.*

Details: see the table above and `sources.md`.

## Files

| File | Content |
| --- | --- |
| `finland_rent_landlord_rules_2026.csv` | One row per fact, with source URL, optional cross-check URL and check date |
| `sources.md` | Every field with publisher and links, plus fields left empty and notes |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |
| `CITATION.cff` | Citation metadata |
| (Eurostat rows) | The last rows of the CSV hold the Eurostat rent price change for this country (HICP actual rentals, item CP041) |

## Field dictionary

| Field | Meaning |
| --- | --- |
| `country_code, country` | Code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, contract_form, registration, rent_payment, landlord_duties, rent_level_change and similar |
| `field` | Specific item |
| `value` | The fact in our own words; empty where no verified figure was found |
| `source_publisher` | Body that publishes the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | Second source actually read, if any |
| `checked_on` | Date the source was read |
| `note` | Scope, language of the source or caveat |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Rent price change is the Eurostat HICP index of rents actually paid. It shows how rents moved, not what they cost. The API responses used were last updated by Eurostat on 6 February 2026, so the latest period is December 2025.
4. Where a statute is translated or summarised from another language, the original-language text prevails.

## Citation

Gorok, L. (2026). *Finland: rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://github.com/izirento/izirento-finland-rent-index

## Attribution

Sources are listed in `sources.md` and in `LICENSE.md`.
