# Lyten

Lyten is a San Jose, California advanced-materials company founded in 2015 that invented and commercializes **Lyten 3D Graphene** — a tunable three-dimensional carbon supermaterial produced by converting methane into nanostructured carbon while co-producing hydrogen.

Lyten applies that materials platform across four product lines:

- **Battery systems** — lithium-sulfur cells with no cobalt, nickel or manganese, targeting roughly 40% weight savings versus lithium-ion
- **3D printer filament** — 3D graphene reinforced additive-manufacturing filament
- **Construction materials** — concrete admixture and structural adhesives
- **Sensors** — chemical and environmental sensing, including **Lyten Atmos**, a continuous methane-intelligence platform pairing solar-powered LTE field sensors with cloud analytics and dashboards

The company has raised over $600 million from investors including Stellantis, FedEx and Honeywell, operates a 145,000 sq ft pilot facility in Alviso (North San Jose), acquired Cuberg's San Leandro battery assets in 2024, and in 2025 acquired Northvolt battery manufacturing assets in Poland and Sweden, establishing a European headquarters in Gdansk.

- Website: https://lyten.com/
- News: https://lyten.com/news/
- Secondary market: https://forgeglobal.com/lyten_stock/

## API surface

**None.** Lyten publishes no public API program. A full enrichment discovery pass on 2026-08-01 probed every resolving host for OpenAPI/Swagger, GraphQL introspection, an MCP `tools/list` endpoint, an A2A agent card, and the `/.well-known/` discovery surface — all missed. No first-party SDK exists on npm, PyPI or crates.io, and there is no Lyten GitHub organization. `api.lyten.com`, `docs.lyten.com`, `developer.lyten.com` and siblings resolve to a Cloudflare wildcard that redirects to the marketing site.

The site runs WordPress and exposes the WordPress core REST API at `/wp-json/`; that is CMS infrastructure, not a Lyten product API, and is deliberately not catalogued as one.

See `apis.yml` `x-discovery` and `well-known/lyten-well-known.yml` for the recorded probe results.
