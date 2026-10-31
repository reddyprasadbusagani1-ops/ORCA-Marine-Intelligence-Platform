# Candidate data sources and integration plan

> **Research status:** These are candidate sources to investigate. This list does not establish an active API integration, permission, guaranteed access, current availability or operational feed. Verify the provider's current documentation before implementation.

| Candidate source | Potential relevance | Checks before use |
|---|---|---|
| [ISRO MOSDAC](https://mosdac.gov.in/) | Satellite and meteorological/ocean-related products | Identify relevant products, access method, resolution, update cadence and terms |
| [INCOIS](https://incois.gov.in/) | Ocean information, advisories and PFZ services | Confirm official access routes, product availability, update schedule and redistribution terms |
| [India Meteorological Department](https://mausam.imd.gov.in/) | Weather forecasts and official warnings | Confirm machine-readable access, warning geometry and valid-time metadata |
| [Copernicus Marine Service](https://marine.copernicus.eu/) | Marine environmental datasets and forecasts | Review catalogue, API access, licensing and regional coverage |
| [data.gov.in](https://www.data.gov.in/) | Potential government datasets | Check dataset-specific API availability, quality and licence |

## Integration checklist

For every feed, record:

- Provider and exact dataset/product name.
- Official documentation URL and access method (API, download, portal, etc.).
- Authentication requirements and credential handling.
- Licence, attribution and redistribution restrictions.
- Units, coordinate reference system and spatial coverage/resolution.
- Temporal resolution, update cadence, observation time and forecast valid time.
- Quality flags, known gaps, latency and fallback behavior.

Prefer authoritative sources for safety-related information. A failed, missing or stale feed must be labelled unavailable or stale; it must never be represented as an all-clear.
