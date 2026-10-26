# BlackSky (blacksky)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

BlackSky Technology (NYSE: BKSY) is a Herndon, Virginia headquartered real-time space-based intelligence company. BlackSky operates a high-revisit Earth observation satellite constellation and delivers AI-enhanced tactical ISR imagery and analytics to defense, intelligence, and global security customers through its cloud-based Spectra platform.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/blacksky/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Earth Observation, Satellite Imagery, Remote Sensing, Geospatial Intelligence, Space, ISR, Tasking, AI Analytics, Object Detection, Defense, Monitoring, Spectra, Gen-3, NYSE BKSY

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## Company Snapshot

| Field | Value |
|---|---|
| Headquarters | Herndon, Virginia |
| Manufacturing | Tukwila, Washington |
| Stock | NYSE: BKSY (publicly traded since September 2021) |
| Constellation | Gen-2 (83 cm) and Gen-3 (35 cm class VHR) |
| Platform | Spectra — tasking, imagery delivery, AI analytics |
| Revisit | Hourly over select areas; up to 15 time-diverse images per location per day |
| Delivery SLA | Under 90 minutes target for tasked imagery |

## Offerings

### BlackSky Spectra

Spectra is BlackSky's purpose-built cloud intelligence platform. It provides an interactive UI plus a secure tasking and delivery API for vetted customers. Capabilities include:

- On-demand and recurring satellite tasking with feasibility indicators
- Sub-90-minute imagery delivery
- AI-driven automated object detection (vessels, aircraft, vehicles)
- Comparative / change analytics for continuous monitoring
- Imagery archive access
- Partner data integration as additional layers

### BlackSky ON-DEMAND

Flexible, global tasking subscription tier with hourly revisit over select areas, historical archive access, and AI-driven automated object detection. Designed for customers whose collection priorities shift over time.

### BlackSky ASSURED

Contract-backed, dedicated tasking capacity for persistent monitoring over defined areas of interest. Guarantees uncontested capacity, time-diverse high-frequency monitoring, and low-latency delivery.

### Mission Solutions

Custom capabilities for specific operational requirements where ON-DEMAND or ASSURED subscriptions do not fit — typically defense and intelligence integrations.

## Imagery Products

- **Daytime Imagery** — repeat-cycle ground-truth collection
- **Stereo Imagery** — two-frame or five-frame sets for 3D product generation
- **Burst Imagery** — five frames in a single pass for motion analysis
- **Nighttime Imagery** — after-dark activity monitoring
- **Area 2x1 Imagery** — extended coverage for airports, ports, and other large facilities

Delivered as 1 panchromatic + 3 multispectral (RGB) bands; acquired at 12-bit and delivered at 16-bit.

## API Surface (Customer-Gated)

BlackSky exposes a Spectra tasking and imagery delivery API, but it is access-controlled for vetted defense, intelligence, and enterprise customers and is not published as a public self-service developer portal. As of this entry there is no public Spectra developer documentation site, no public OpenAPI specification, and no official open-source SDK from BlackSky.

BlackSky's API is reachable today through three primary channels:

- **Direct Spectra API** — provisioned to enterprise and government customers after contract; access via `tasking.blacksky.com`
- **Esri ArcGIS integration** — on-demand BlackSky satellite tasking available to ArcGIS Online customers via the [ArcGIS BlackSky Imagery Tasking app](https://www.esri.com/en-us/arcgis/products/blacksky-imagery-tasking)
- **UP42 marketplace** — BlackSky Gen-2 and Gen-3 tasking, Mono Catalog, and Stereo Catalog products are orderable through the [UP42 Tasking and Catalog APIs](https://docs.up42.com/data/blacksky)

The community-maintained [STAT (Satellite Tasking API) FastAPI BlackSky backend](https://github.com/stapi-spec/stapi-fastapi-blacksky) demonstrates a third-party proxy pattern (`GET /products`, `POST /opportunities`) that wraps a `BLACKSKY_BACKEND_TOKEN`-authenticated upstream — useful as a reference for what the customer-facing API surface looks like, but not an official BlackSky-published specification.

This repository therefore tracks BlackSky as a provider profile (company, offerings, partners, tags) without generating placeholder OpenAPI, Naftiko capabilities, JSON Schema, plans, rate limits, or FinOps artifacts. Those will be added if and when BlackSky publishes a public developer area.

## Common Properties

- [Website](https://blacksky.com)
- [Technology](https://blacksky.com/technology/)
- [Offerings](https://blacksky.com/offerings/)
- [BlackSky ON-DEMAND](https://blacksky.com/offerings/blacksky-on-demand/)
- [BlackSky ASSURED](https://blacksky.com/offerings/blacksky-assured/)
- [Tasking Portal — tasking.blacksky.com](https://tasking.blacksky.com)
- [Company](https://blacksky.com/company/)
- [Newsroom](https://blacksky.com/news/)
- [Investor Relations](https://ir.blacksky.com/)
- [Careers](https://blacksky.com/company/careers/)
- [Contact](https://blacksky.com/company/contact-us/)
- [Newsletter](https://info.blacksky.com/subscribe)
- [Partner — Esri ArcGIS](https://www.esri.com/en-us/arcgis/products/blacksky-imagery-tasking)
- [Partner — UP42 BlackSky data](https://docs.up42.com/data/blacksky)
- [Twitter / X](https://twitter.com/blackskyinc)
- [LinkedIn](https://www.linkedin.com/company/blackskyinc)
- [YouTube](https://www.youtube.com/@BlackSkyInc)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
