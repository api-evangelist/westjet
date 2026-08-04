# WestJet (westjet)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

WestJet Airlines Ltd. is Canada's second-largest air carrier, headquartered in Calgary, Alberta, operating scheduled passenger service to more than 100 destinations across Canada, the United States, Mexico, Central America, the Caribbean, Europe and Asia, alongside WestJet Encore, WestJet Vacations, WestJet Cargo and the Sunwing Vacations Group. In the distribution chain WestJet sits upstream of the agency channel: its inventory reaches travel sellers today through EDIFACT in the Amadeus, Sabre and Travelport GDSs, and it is standing up an IATA NDC surface (schema 17.2 and 21.3/24.1) built and hosted on Accelya's FLX/Farelogix platform, with a stated Q4 2026 rollout. Its API posture is honest but closed: there is no public developer portal, no self-serve signup, no OpenAPI or WSDL and no consumer API. The WestJet Direct Connect API is documented only as a public capability matrix at westjetndc.com, and access requires an IATA or ARC accreditation number (TIDS is explicitly not supported), a business-type and sales-volume qualification form, and WestJet approval. Agency booking through WestJet Agent Direct likewise requires an IATA/TIDS/ARC number and a five-to-ten business day review. There is no bulk export for agency or booking data; guest data comes out only via a verbally authenticated PIPEDA-style "Guest information report" request.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/westjet/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/westjet/refs/heads/main/apis.yml)

## Tags

- Travel
- Canada
- Aviation
- Airline
- Distribution
- NDC
- Booking
- Cargo
- Loyalty

## Timestamps

- **Created:** 2026-07-28
- **Modified:** 2026-07-28

## APIs

### WestJet Direct Connect API

WestJet's IATA New Distribution Capability (NDC) direct-connect interface for travel sellers, offered in NDC schema versions 17.2 and 21.3/24.1 and delivered on Accelya's FLX/Farelogix platform. Published capability tables cover shopping (fare brands, fare types, complex itineraries, promo codes), ancillaries (EMD-A for bags and pre-reserved seats, seat maps), order creation (book-and-hold, book-and-instant-ticket), payment and ticketing (credit/debit, BSP and ARC cash, UATP, multiple forms of payment), settlement via BSP and ARC, change notifications (OCN), and servicing (CAT 33 voluntary refunds, True Reshop, waiver codes, split/divide PNR, SSR and OSI updates). No OpenAPI, WSDL, XSD or base URL is published; enrolment is by application and requires an IATA or ARC accreditation number. WestJet states a Q4 2026 rollout, with a $20-$22 USD Distribution Cost Recovery surcharge applying to non-NDC (EDIFACT) bookings on the lowest class per cabin in NDC-enabled points of sale.

- **Human URL:** [https://westjetndc.com/connection-options/](https://westjetndc.com/connection-options/)
- **Base URL:** not published

#### Tags

- NDC
- Distribution
- Airline
- Booking
- Travel

#### Properties

- [Documentation](https://westjetndc.com/)
- [Documentation](https://westjetndc.com/connection-options/)
- [Documentation](https://westjetndc.com/capabilities/)
- [Documentation](https://westjetndc.com/benefits/)
- [Documentation](https://westjetndc.com/faq/)
- [Signup](https://westjetndc.com/direct-connect/)
- [Support](https://westjetndc.com/technical-support/)
- [Status Page](https://accelyastatus.statuspage.io/)
- [Change Log](https://westjetndc.com/release-notes/)

## Common Properties

- [Website](https://www.westjet.com/)
- [Portal](https://westjetndc.com/)
- [Documentation](https://westjetndc.com/capabilities/)
- [Travel Agent Resources](https://westjettravelagents.com/)
- [Policy Library](https://westjettravelagents.com/policy-library/)
- [Terms of Service](https://westjettravelagents.com/policy-library/ticketing-policy/)
- [Terms of Service](https://www.westjet.com/en-ca/legal/terms-use)
- [Privacy Policy](https://www.westjet.com/en-ca/legal/privacy-policy)
- [Data Portability](https://www.westjet.com/en-ca/legal/privacy-policy/privacy-requests)
- [Login](https://westjetagentdirect.westjet.com/login-agent.html)
- [Signup](https://westjetagentdirect.westjet.com/registeragency.html)
- [Login](https://agents.westjetvacations.com/)
- [Cargo](https://www.westjetcargo.com/en-ca)
- [Business Travel](https://westjetbusinesstravel.com/)
- [Vacations](https://www.westjetvacations.com/en/)
- [LLMs.txt](https://www.westjet.com/llms.txt)
- [LinkedIn](https://www.linkedin.com/company/westjet)
- [Newsroom](https://www.westjet.com/en-ca/news)
- [Press Room](https://westjet.mediaroom.com/)
- [Support](https://www.westjet.com/en-ca/contact)

## Switching Cost

The full evidence trail lives in [`review.yml`](review.yml). In short:

| Dimension | Finding |
| --- | --- |
| Interface shape | `standard-plus-proprietary` — IATA NDC 17.2 and 21.3/24.1 plus EDIFACT, extended with WestJet-only fare-basis bundle encoding and channel-exclusive UltraBasic content |
| Second source | `no-alternative` — six routes to the inventory (Direct Connect, SPRK, Amadeus, Sabre, Travelport, Travelfusion, plus aggregators such as Duffel), one supplier of it |
| Exit path | `export-on-request` — a "Guest information report" with verbal authentication; no bulk export, no agency data dump |
| Identifier portability | Mostly IATA-owned: WS designator, 838 ticket stock, PNR record locators, EMD-A, IATA/ARC/TIDS accreditation numbers, IATA airport codes, CAT 31/33. Proprietary layer: seventh-character fare-basis bundle codes and WestJet waiver codes |
| Contractual lock-in | Canadian OTAs "must have a sales incentive contract directly with WestJet or Book and Ticket through an Official WestJet Online Redistributor"; policy amendable "in its sole discretion"; ADMs with no minimum value and 10-150 CAD/USD administrative fees, including a "Dual CRS" penalty |
| Distribution model | `gds-intermediated` today (EDIFACT via Amadeus/Sabre/Travelport), moving to `ndc-direct` |
| NDC posture | IATA NDC Certification Level 2, granted 22 March 2017. Direct Connect API in NDC 17.2 and 21.3/24.1 on Accelya FLX, rollout stated for Q4 2026. $20-$22 USD Distribution Cost Recovery surcharge on non-NDC bookings, lowest class per cabin |
| Access gate | `accredited-or-licensed` — IATA or ARC number required, TIDS explicitly unsupported for the API, sub-$1M agencies deflected to a GDS |

## Notes

- No OpenAPI, Swagger, WSDL, XSD, Postman collection or AsyncAPI is published anywhere on WestJet's properties. `openapi/` is intentionally absent.
- `developer.westjet.com`, `developers.westjet.com` and `docs.westjet.com` do not resolve. `www.westjet.com/openapi.json` and `/swagger.json` return HTTP 200 but serve the SPA soft-404 page.
- No public GitHub organization: `api.github.com/orgs/westjet` is 404, and all seven WestJet-named orgs report zero public repositories.
- The consumer surface (flight status, check-in, manage trips, WestJet Rewards) is web and app only. The distribution surface is the only real API, and it is gated.
