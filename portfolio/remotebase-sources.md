# RemoteBase — Data Sources & Methodology

**Version:** 0.2  
**Last reviewed:** 13 August 2026

RemoteBase is a personal decision-support experiment, not immigration, tax, legal or financial advice. It combines sourced benchmark data with transparent editorial heuristics. Every score should be treated as a comparison signal rather than a definitive fact.

## Travel profile used in v0.2

The current model is optimised for an **EU citizen travelling on a Croatian passport**.

### EU destinations

EU citizens can stay in another EU country for up to three months without being required to obtain a residence document, although some countries may require presence reporting. After three months, residence registration may be required depending on circumstances.

Source: European Union — Your Europe  
https://europa.eu/youreurope/citizens/residence/documents-formalities/registering-residence/index_en.htm

### Japan

Croatia is included in Japan's short-stay visa-exemption arrangements. The standard short-stay period for visa-exempt nationals is generally 90 days. Temporary Visitor status is not a general work authorisation; remote-work, tax and immigration implications should be checked before relying on it for a workation.

Sources: Japan Ministry of Foreign Affairs  
https://www.mofa.go.jp/j_info/visit/visa/short/novisa.html  
https://www.mofa.go.jp/j_info/visit/visa/faq.html

## Cost benchmarks

RemoteBase currently uses a simple comparable baseline:

**outside-centre one-bedroom benchmark + standardised monthly day-to-day basket**

The day-to-day basket is a RemoteBase modelling assumption intended to make cities comparable. It is not a Numbeo monthly-cost estimate. Users can change accommodation style and monthly spend ceiling to test different scenarios.

City benchmark sources:

- Sliema: https://www.numbeo.com/cost-of-living/in/Sliema
- Split: https://www.numbeo.com/cost-of-living/in/Split
- Lisbon: https://www.numbeo.com/cost-of-living/in/Lisbon
- Valencia: https://www.numbeo.com/cost-of-living/in/Valencia
- Limassol: https://www.numbeo.com/cost-of-living/in/Limassol
- Yokohama: https://www.numbeo.com/cost-of-living/in/Yokohama

Numbeo is crowdsourced, so individual prices and indices can change and should be cross-checked before committing to accommodation.

## Purchasing power

RemoteBase shows two different concepts:

1. **Your Budget Power** — your selected monthly spend ceiling divided by the modelled local baseline. This is the most relevant purchasing-power measure for someone earning income remotely.
2. **Local Purchasing Power Index** — a reference index based on local incomes and local prices. This helps explain what affordability feels like for local earners, but it should not be confused with the purchasing power of a foreign salary.

Reference pages used:

- Malta: https://www.numbeo.com/quality-of-life/country_result.jsp?country=Malta
- Split: https://www.numbeo.com/quality-of-life/in/Split
- Lisbon: https://www.numbeo.com/quality-of-life/in/Lisbon
- Valencia: https://www.numbeo.com/quality-of-life/in/Valencia
- Limassol: https://www.numbeo.com/quality-of-life/in/Limassol
- Japan: https://www.numbeo.com/quality-of-life/country_result.jsp?country=Japan

## Japanese yen conversion

Yokohama's euro rent reference is converted from the local-currency benchmark using an ECB reference rate near the data-review period. Exchange rates can move materially, so the tool labels the FX reference date.

Source: European Central Bank  
https://www.ecb.europa.eu/stats/policy_and_exchange_rates/euro_reference_exchange_rates/html/eurofxref-graph-jpy.en.html

## Infrastructure score

The infrastructure score is a **RemoteBase editorial composite**, not an official external index. It combines:

- local public transport
- regional / international connectivity
- broadband / digital-work practicality
- rail / intercity infrastructure
- everyday digital-service convenience

The component scores are visible in the detail panel so users can disagree with the assumptions instead of treating one opaque number as fact.

## Best months / seasonal fit

Season scores are a **climate-comfort heuristic**, not a weather forecast. They are designed for long-stay remote work rather than peak tourism alone. The model favours mild temperatures and penalises extreme heat, humidity, persistent winter discomfort or heavy-rain periods.

For Valencia, the official destination site explicitly describes spring as the best season and provides monthly temperature guidance:  
https://www.visitvalencia.com/en/plan-your-trip-to-valencia/valencia/weather

Other city month scores are editorial seasonal-comfort estimates and should be replaced over time with a structured climate dataset.

## What RemoteBase does not yet model

- personal income tax / tax residency
- social-security obligations
- employer permanent-establishment risk
- health-insurance eligibility
- furnished-rental availability by month
- live airfare prices
- live exchange rates
- visa rules for multiple nationalities
- neighbourhood-level safety and housing quality

These are deliberate roadmap items rather than hidden assumptions.
