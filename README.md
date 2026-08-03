# 280 Earth

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

280 Earth is a direct air capture (DAC) company that permanently removes carbon dioxide from the atmosphere. Launched in 2018 inside X, the Alphabet moonshot factory, and spun out as an independent company in 2022, it is backed by Sergey Brin and Builders VC and closed a $50M Series B in 2024. Its proprietary sorbent moves through a gravity-fed, dual-chamber system that continuously cycles material between capturing and releasing CO2, running on low-grade industrial waste heat or clean electricity and producing fresh water as a byproduct. Its first pilot plant, in The Dalles, Oregon, captures 500 tons of CO2 per year on a site sized for more than 20,000 tons per year at full build-out, and underpins a $40M offtake agreement with the Frontier carbon removal buyer consortium.

- Website: https://280.earth/
- Projects: https://280.earth/projects/
- Careers: https://280.earth/careers/
- GitHub: https://github.com/280earth
- Secondary market: https://forgeglobal.com/280-earth_stock/

## API surface

**None published.** Contract discovery on 2026-08-02 probed the website host and eleven candidate
subdomains (`api.`, `docs.`, `developer.`, `developers.`, `app.`, `portal.`, `status.`, `trust.`,
`security.`, `data.`, `mcp.` — none resolve), plus `/openapi.json`, `/openapi.yaml`, `/swagger.json`,
`/v1/openapi.json`, `/api-docs`, `/docs`, `/redoc`, `/graphql`, `/llms.txt`, and the full
`/.well-known/` discovery surface including `agent-card.json` and the legacy `agent.json`. Every probe
missed — the site 301-redirects unknown paths to the homepage, so the HTML responses are catch-all
false positives, not documents. No OpenAPI, GraphQL, AsyncAPI, MCP server, agent card, SDK, or
security.txt exists. Full evidence is in `well-known/280-earth-well-known.yml`.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Domain security | `security/280-earth-domain-security.yml` | probed |
| Well-known / contract discovery | `well-known/280-earth-well-known.yml` | probed |
| llms.txt | `llms/280-earth-llms.txt` | generated |
