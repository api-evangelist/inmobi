# InMobi

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

InMobi is a global advertising technology and mobile marketing platform headquartered in Bengaluru, India, and backed by SoftBank Vision Fund. It positions itself as the intelligence layer of the consumer internet, connecting brands and consumers across mobile apps and the open web. InMobi's enterprise platforms include InMobi Advertising for brand building, app growth and ad monetization; the InMobi Exchange, a programmatic OpenRTB 2.5 ad exchange for demand-side platforms; InMobi DSP performance solutions; and InMobi CMP (Choice), an IAB TCF-certified consent management platform. InMobi operates four documented, live REST APIs — the Publisher Reporting API 3.0 for inventory performance data, the Ad Management API for managing apps and placements, the DSP Cost API for asynchronous spend reporting, and a Server-to-Server Ad Request API — alongside native mobile ad SDKs for Android (Maven Central) and iOS (CocoaPods and Swift Package Manager). No OpenAPI, AsyncAPI, OAuth server or REST client library is published for any of them. Consumer brands include Glance and the 1Weather app.

**Areas:** Company · Enterprise · Advertising · AdTech · Mobile · Monetization · Programmatic · OpenRTB · SDK · Consent Management · DSP · Reporting

## InMobi on APIs.io

Everything profiled for InMobi is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/inmobi/](https://apis.io/providers/inmobi/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [InMobi Publisher Reporting API](https://apis.io/apis/inmobi/inmobi-publisher-reporting-api/) — Automates download of app inventory performance data for InMobi publishers. A single POST to /v3.0/reporting/publisher takes a reportRequest envelope of…
- [InMobi Ad Management API](https://apis.io/apis/inmobi/inmobi-ad-management-api/) — Manages InMobi monetization inventory — the apps and placements a publisher monetizes through InMobi — without clicking through the dashboard. Apps are…
- [InMobi DSP Cost API](https://apis.io/apis/inmobi/inmobi-dsp-cost-api/) — Asynchronous spend reporting for InMobi DSP advertisers. A bearer token is minted from clientId/clientSecret at POST /auth/token (8-hour validity), then a…
- [InMobi Server-to-Server Ad Request API](https://apis.io/apis/inmobi/inmobi-server-to-server-ad-request-api/) — Lets a publisher request InMobi ads from its own servers rather than through the client SDK, using the InMobi ad-request/ad-response contract at…
- [InMobi Exchange (OpenRTB 2.5)](https://apis.io/apis/inmobi/inmobi-exchange-openrtb/) — InMobi's programmatic ad exchange, integrated by demand-side platforms over the IAB OpenRTB 2.5 protocol. InMobi publishes its own delta specification…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Inmobi Authentication](https://apis.io/security/inmobi/inmobi-authentication/)
- [Inmobi Domain Security](https://apis.io/security/inmobi/inmobi-domain-security/)
- [Inmobi Trust Center](https://apis.io/security/inmobi/inmobi-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Inmobi Plans Pricing](https://apis.io/plans/inmobi/inmobi-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Inmobi Rate Limits](https://apis.io/rate-limits/inmobi/inmobi-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.inmobi.com/)
- [Documentation](https://support.inmobi.com/monetize)
- [Getting started](https://support.inmobi.com/monetize)
- [API reference](https://support.inmobi.com/monetize/inmobi-apis)
- [Pricing](https://support.inmobi.com/choice/getting-started-cmp/inmobi-cmp-premium)
- [Sign up](https://publisher.inmobi.com/signup)
- [Support](https://support.inmobi.com/)
- [Changelog](https://support.inmobi.com/inmobi-now)
- [Blog](https://www.inmobi.com/blog)
- [Security](https://www.inmobi.com/security/)
- [Compliance](https://www.inmobi.com/trust-center/)
- [Terms of service](https://www.inmobi.com/terms-of-service)
- [Privacy policy](https://www.inmobi.com/website-privacy-policy/)
- [GitHub](https://github.com/InMobi)

## API Evangelist rating

**Kin Score 48.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 5.3 |
| Contract governance | 18.2 |
| Operational transparency | 60.5 |
| Developer ergonomics | 64.3 |
| Access clarity | 75.0 |

**Agent readiness 7.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 29.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/inmobi/](https://apis.io/providers/inmobi/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for InMobi: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/inmobi/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
