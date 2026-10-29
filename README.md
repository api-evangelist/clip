# Clip

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

Clip (legal name Payclip) is a Mexico City-based fintech and SMB acquirer often described as the Square equivalent in Mexico. Founded in 2012, Clip enables merchants of all sizes to accept card, contactless, and QR payments through a family of mobile point-of-sale (mPOS) terminals — Clip Plus 2, Clip Pro 2, Clip Ultra, Clip Total 3, and the high-volume Clip PinPad — as well as Tap to Pay on iOS/Android smartphones, an online Checkout payment gateway, payment links, and the Clip Cuenta digital business account with same-day settlement and SMB loans. Clip operates the developer portal developer.clip.mx, which publishes the Checkout Redirect, Checkout Transparente, Transactions, Deposits, Refunds, and PinPad APIs along with the Checkout Transparente SDK and a Terminal SDK for embedding card acceptance into third-party POS apps. The company is backed by strategic investors including American Express Ventures, Banorte, Capital Group, and Morgan Stanley, and is consistently ranked among Mexico's top private fintech employers.

**Areas:** Payments · Acquiring · SMB Payments · Point-of-Sale · mPOS · Tap to Pay · Card Acceptance · Checkout · Payment Gateway · Payment Links · Mexico · Latin America

## Clip on APIs.io

Everything profiled for Clip is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/clip/](https://apis.io/providers/clip/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Clip Checkout Redirect API](https://apis.io/apis/clip/clip-checkout-redirect-api/) — Hosted checkout flow that redirects shoppers to a Clip-hosted payment page to capture card data and complete the charge. Returns the authorized payment back…
- [Clip Checkout Transparente API](https://apis.io/apis/clip/clip-checkout-transparente-api/) — Server-side payment processing that tokenizes card data via the Card Token API and charges through the Payments API while keeping the checkout experience…
- [Clip Transactions API](https://apis.io/apis/clip/clip-transactions-api/) — Query individual transactions and list transactions across a date range from a Clip merchant account — used for reconciliation across both online Checkout…
- [Clip Deposits API](https://apis.io/apis/clip/clip-deposits-api/) — Retrieve detailed deposit reports and deposit summaries for the merchant's Clip Cuenta over a date window (up to 90 days). Use to reconcile payouts to the…
- [Clip Refunds API](https://apis.io/apis/clip/clip-refunds-api/) — Create full or partial refunds against previously approved Clip payments and query refund status. Supports both Checkout and PinPad sourced transactions.
- [Clip PinPad API](https://apis.io/apis/clip/clip-pinpad-api/) — Drive a Clip PinPad device (fixed, high-volume terminal) from a merchant's own POS software — initiate card-present sales, query device status, capture…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Clip Domain Security](https://apis.io/security/clip/clip-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.clip.mx)
- [Documentation](https://developer.clip.mx/docs/getting-started)
- [Getting started](https://developer.clip.mx/docs/primeros-pasos)
- [Support](https://ayuda.clip.mx/s/)
- [Blog](https://blog.clip.mx)
- [Compliance](https://developer.clip.mx/reference/pci-compliance)
- [Terms of service](https://www.clip.mx/terminos)
- [Privacy policy](https://www.clip.mx/privacidad)
- [GitHub](https://github.com/ClipMX)

## API Evangelist rating

**Kin Score 21.3** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 6.6 |
| Developer ergonomics | 44.0 |
| Access clarity | 28.9 |

**Agent readiness 3.9** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 17.0** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/clip/](https://apis.io/providers/clip/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Clip: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/clip/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
