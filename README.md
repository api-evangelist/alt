# Alt

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
