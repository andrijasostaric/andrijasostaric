# RemoteBase — Data Sources & Methodology

**Version:** 0.3  
**Last reviewed:** 13 August 2026

RemoteBase is a decision-support product for comparing possible temporary bases. It is **not immigration, tax, employment, social-security, legal or financial advice**. The score mixes sourced data with clearly labelled RemoteBase heuristics. It is designed to make trade-offs visible, not to declare one objectively “best” city.

## Scope in v0.3

The current passport profile is **EU / EEA ordinary passport — generic**. This is intentionally more universal than the previous Croatia-specific version, but an “EU passport” is not a single immigration nationality outside the EU. Some countries treat individual EU/EEA nationalities differently. Where the rule is not uniform, RemoteBase flags the entry note for exact-passport verification.

The current comparison universe is a curated **five-city shortlist per region**:

- **Europe:** Valencia, Lisbon, Split, Las Palmas, Athens
- **Africa:** Cape Town, Marrakech, Nairobi, Port Louis, Tunis
- **Asia:** Kuala Lumpur, Bangkok, Chiang Mai, Da Nang, Tokyo
- **Oceania:** Brisbane, Melbourne, Perth, Adelaide, Auckland
- **South America:** Buenos Aires, Medellín, Florianópolis, Santiago, Montevideo

These are RemoteBase candidates chosen for a mix of cost, climate, infrastructure, connectivity, international accessibility and long-stay usefulness. They are not presented as a published external “top 5” ranking. The app re-ranks them for the user’s own dates, budget and visitor-window requirements.

## 1. Visitor-window model

RemoteBase distinguishes between:

- **Easy-entry window** — the normal visa-free / eTA / eVisitor / short-stay route available to the relevant EU passport profile.
- **Maximum visitor route** — a longer ordinary visitor/tourist route where a straightforward extension or separate visitor visa is officially documented.

A longer visitor route may involve an application, fee, extension, financial evidence or discretionary approval. It is therefore scored lower than an easy-entry stay even if it can technically cover the requested duration.

### European Union

EU nationals have free-movement rights. During the first three months in another EU country, they cannot generally be required to obtain a residence document, although presence reporting can apply. After three months, residence registration may be required depending on status and circumstances.

Source — European Union, Your Europe:  
https://europa.eu/youreurope/citizens/residence/documents-formalities/registering-residence/index_en.htm

### Australia

For eligible European passports, the **eVisitor (subclass 651)** is free and permits stays of up to three months per entry during its validity. A separate **Visitor visa (subclass 600)** may be granted for up to 12 months. Neither should be treated as a general work visa.

Sources — Australian Department of Home Affairs:  
https://immi.homeaffairs.gov.au/visas/getting-a-visa/visa-listing/evisitor-651  
https://immi.homeaffairs.gov.au/visas/getting-a-visa/visa-listing/visitor-600/tourist-stream-overseas

### New Zealand

EU/EEA passports on New Zealand’s visa-waiver list normally use an **NZeTA** and can receive a Visa Waiver Visitor Visa for up to three months on arrival. A separate Visitor Visa can allow up to nine months in an 18-month period. New Zealand explicitly states that a visa-waiver visitor may work remotely for a business overseas, subject to the visa conditions and other applicable rules.

Sources — Immigration New Zealand:  
https://www.immigration.govt.nz/visas/visa-waiver-visitor-visa/  
https://www.immigration.govt.nz/visas/visitor-visa/  
https://www.immigration.govt.nz/visit/what-you-need-to-visit-new-zealand/visa-waiver-countries-and-territories/

### Japan

Japan maintains visa-exemption arrangements with many EU countries. The standard short stay for most listed EU passports is 90 days under Temporary Visitor status. Temporary Visitor status is not a general authorisation for income-earning activities in Japan.

Sources — Japan Ministry of Foreign Affairs:  
https://www.mofa.go.jp/j_info/visit/visa/short/novisa.html  
https://www.mofa.go.jp/j_info/visit/visa/faq.html

### Malaysia

Malaysian diplomatic missions state that many European passport holders can enter for tourism/business without a visa for up to 90 days. The Malaysia Digital Arrival Card (MDAC) is required for most foreign travellers. Exact nationality should still be verified before travel.

Examples — Ministry of Foreign Affairs, Malaysia:  
https://www.kln.gov.my/web/ita_rome/requirement_foreigner  
https://www.kln.gov.my/web/che_berne/requirement_foreigner

### Thailand

Thailand approved a major revision of the visa-exemption system in May 2026: the earlier 60-day scheme was revoked and a revised 30-day exemption scheme for a smaller list of countries/territories was approved, to take effect after publication under the announced process. Because eligibility is nationality-specific and the scheme recently changed, RemoteBase uses **30 days** for Bangkok/Chiang Mai but marks it for exact-passport verification.

Source — Thailand Ministry of Foreign Affairs:  
https://www.mfa.go.th/en/content/summary-press-briefing-190526

### Vietnam

Vietnam’s official eVisa system provides an eVisa route of up to **90 days**, single or multiple entry. RemoteBase uses the eVisa route rather than assuming that every EU passport has the same visa-free allowance.

Source — Vietnam Immigration eVisa portal:  
https://evisa.gov.vn/

### Kenya

Kenya requires an Electronic Travel Authorisation (eTA) for most foreign visitors who are not exempt. The eTA authorises travel; the permitted duration is determined at entry. Kenyan immigration also requires foreign-national registration for residence exceeding 90 days. RemoteBase therefore uses 90 days as the standard visitor ceiling for the generic EU profile.

Sources — Kenya Directorate of Immigration / eTA:  
https://etakenya.go.ke/general-information  
https://immigration.go.ke/issuance-of-foreign-nationals-certificate-alien-card/

### Mauritius

EU passport holders are exempt from visa requirements. Mauritius states that a tourist stay of up to **six months in a calendar year** may be granted case-by-case. A separate free Premium Visa can allow a one-year renewable stay and explicitly covers eligible professionals working remotely; RemoteBase does not currently substitute the Premium Visa automatically for the ordinary visitor route.

Sources — Mauritius Passport and Immigration Office:  
https://passport.govmu.org/passport/?page_id=605  
https://passport.govmu.org/passport/?page_id=595

### South America

- **Argentina:** many EU passports are visa-exempt for tourism up to 90 days.  
  https://ealem.cancilleria.gob.ar/es/node/3408
- **Brazil:** EU citizens are generally visa-exempt for up to 90 days in a 180-day period and, for most EU citizens, the 90-day stay is not extendable.  
  https://www.gov.br/mre/pt-br/consulado-zurique/deutsch/visa-english-1/vivis_en
- **Chile:** Permanencia Transitoria normally allows up to 90 days and may be extended once for up to another 90 days.  
  https://serviciomigraciones.cl/en/permanencia-transitoria-permit/  
  https://serviciomigraciones.cl/en/permanencia-transitoria-permit/extension/
- **Colombia:** visa-exempt short-stay nationalities include EU countries; the ordinary short-stay period is under 90 days and may be extendable to a maximum of 180 days where the rules permit.  
  https://cancilleria.gov.co/normograma/compilacion/docs/resolucion_minrelaciones_5488_2022.htm
- **Uruguay:** published consular guidance for EU nationalities such as Germany gives 90 days without a visa, extendable for another 90 days. Exact EU nationality should be checked.  
  https://www.gub.uy/ministerio-relaciones-exteriores/embajada-republica-oriental-del-uruguay-alemania/tramites-consulares/visa-turismo

### Morocco and Tunisia

The current v0.3 model uses the common 90-day tourist window for most EU passports, but marks both countries for **exact-nationality verification** because a sufficiently clear, current, nationality-complete primary-source table has not yet been incorporated into the product dataset.

## 2. Numbeo rent and cost data

RemoteBase uses **2026 Numbeo snapshots** for each city. The app exposes the source metrics rather than hiding them inside one score:

- 1-bedroom apartment rent in the city centre
- 1-bedroom apartment rent outside the city centre
- Cost of Living Index
- Groceries Index where available
- Restaurant Price Index where available
- Local Purchasing Power Index

Examples:

- Valencia: https://www.numbeo.com/cost-of-living/in/Valencia
- Lisbon: https://www.numbeo.com/cost-of-living/in/Lisbon
- Split: https://www.numbeo.com/cost-of-living/in/Split
- Athens: https://www.numbeo.com/cost-of-living/in/Athens
- Port Louis: https://www.numbeo.com/cost-of-living/in/Port-Louis

For cities whose regional Numbeo table was surfaced in USD, v0.3 converts the stored snapshot to EUR using a **12 August 2026 USD/EUR snapshot of 0.867502**. Port Louis was converted from MUR using **0.0184332 EUR per MUR** on the same date. These FX conversions are snapshots, not live rates.

### All-in monthly budget estimate

Numbeo does not publish one universally comparable “single remote worker monthly spend” figure for all 25 cities in the same public table. To keep budget filtering possible without pretending otherwise, RemoteBase uses a transparent model:

`selected 1BR rent + (Numbeo Cost of Living Index × €12)`

The second component is explicitly a **RemoteBase comparison allowance**, not a Numbeo monthly-expense quote. The user can optionally apply a +25% scenario to rent to simulate a furnished 1–3 month rental premium. Raw Numbeo rents remain visible beside the modelled total.

## 3. Weather for selected dates

The app displays **rounded typical climate conditions**, not a future weather forecast. For every city, RemoteBase stores a monthly profile with:

- typical daytime temperature
- typical overnight temperature
- a qualitative precipitation/humidity label

If a stay crosses several calendar months, RemoteBase evaluates all months touched by the trip and produces a combined climate summary.

This is deliberately coarse in v0.3. The next data upgrade is to replace the stored climate profiles with calculated historical normals from a weather-data source. Open-Meteo’s Historical Weather API is suitable for this because it exposes global reanalysis data back to 1940 through a documented API:

https://open-meteo.com/en/docs/historical-weather-api

Until that integration is complete, the climate output should be read as **typical seasonal guidance**, never as a forecast.

## 4. Infrastructure and time-zone scores

Infrastructure is a RemoteBase editorial score intended to represent usefulness for a remote worker, drawing on:

- local public transport
- intercity / rail usefulness
- broadband and digital convenience
- international air connectivity
- ease of functioning without a car

The EU-hours score measures practical overlap with a Central European working day. These are not third-party published indices and are deliberately labelled as RemoteBase scores.

## 5. Ranking logic

Default **Balanced** weighting in v0.3:

- Cost fit — 30
- Visitor fit — 25
- Selected-stay weather — 18
- Infrastructure — 12
- Local purchasing power — 8
- EU-hours fit — 7

The user can switch to Low-cost, Weather-first, Long-stay or Infrastructure presets, or set the weights manually.

Hard-fit mode can remove a destination when:

1. the modelled all-in monthly spend is above the user’s budget, or
2. the requested visitor window exceeds the maximum ordinary visitor route stored for that country.

## 6. Data-quality principle

RemoteBase should always distinguish:

**sourced fact → conversion → RemoteBase model → judgement**

When an immigration rule is uncertain, nationality-specific or newly changed, the correct product behaviour is to flag the uncertainty — not to manufacture precision.
