# Alt

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

Alt (alt.xyz) is an alternative-asset platform for high-value graded trading cards. Collectors and
investors research, value, buy, sell, vault and borrow against slabbed sports cards, Pokemon and other
trading-card games in one place. Alt operates a fixed-price marketplace, timed and "Liquid" auctions, an
Instant Pricer, a physical vault in Delaware that removes sales tax from transactions, and card-backed
lending — all underwritten by Alt Value, a machine-learning pricing model tuned by card-pricing
specialists that produces a real-time value for every BGS, PSA and SGC card vaulted with Alt. The company
was founded by Leore Avidar, previously co-founder of the API company Lob, and raised a $75M Series B in
November 2021 led by Spearhead with Seven Seven Six.

## API status

**Alt publishes no public developer program.** As of 2026-08-02 there is no developer portal, API
reference, OpenAPI/AsyncAPI/GraphQL contract offered to third parties, SDK, CLI, sandbox, MCP server,
A2A agent card, or self-service API signup. The alt.xyz applications are served by a private platform
backend that is neither documented nor offered externally. No `/.well-known/` discovery documents are
published on any Alt host — the alt.xyz origin is a single-page app that answers 200 with its HTML shell
for every unmatched path, which is recorded as a catch-all false positive in `well-known/`.

- https://alt.xyz/
- https://support.alt.xyz/
- https://github.com/onlyalt
- https://forgeglobal.com/alt_stock/ (secondary-market listing — harvest source)

## Artifacts

| Artifact | File |
|---|---|
| APIs.json profile | `apis.yml` |
| Domain security posture (probed) | `security/alt-domain-security.yml` |
| `/.well-known/` discovery probe (none published) | `well-known/alt-well-known.yml` |
| llms.txt | `llms/alt-llms.txt` |
