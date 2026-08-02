# 280 Earth

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
