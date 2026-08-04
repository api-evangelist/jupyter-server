# Jupyter Server (jupyter-server)

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

Jupyter Server is the backend that powers Jupyter Notebook, JupyterLab, and other Jupyter web applications. It provides the core REST API for managing kernels, sessions, contents, terminals, and configuration, and it hosts the WebSocket endpoints used to communicate with kernels via the Jupyter messaging protocol.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Compute
- Interactive Computing
- Kernels
- Notebooks
- Portable
- Workbooks

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-19

## APIs

### Jupyter Server REST API

Core REST API for Jupyter Server, providing endpoints for managing kernels, sessions, contents (notebooks and files), terminals, kernel specifications, configuration, and server status.

- **Human URL:** [https://jupyter-server.readthedocs.io/en/latest/developers/rest-api.html](https://jupyter-server.readthedocs.io/en/latest/developers/rest-api.html)
- **Base URL:** `http://localhost:8888/api`

#### Tags

- Contents
- Kernels
- REST API
- Sessions
- Terminals

#### Properties

- [Documentation](https://jupyter-server.readthedocs.io/en/latest/developers/rest-api.html)
- [Repository](https://github.com/jupyter-server/jupyter_server)
- [Changelog](https://github.com/jupyter-server/jupyter_server/blob/main/CHANGELOG.md)
- [OpenAPI](openapi/jupyter-server-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jupyter-server-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupyter-server-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/jupyter-server-contents-model.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/jupyter-server-kernel.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/jupyter-server-session.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/jupyter-server-context.jsonld)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/project-jupyter)
- [Website](https://jupyter-server.readthedocs.io/)
- [Documentation](https://jupyter-server.readthedocs.io/en/latest/)
- [Getting Started](https://jupyter-server.readthedocs.io/en/latest/users/index.html)
- [GitHub Organization](https://github.com/jupyter-server)
- [Repository](https://github.com/jupyter-server/jupyter_server)
- [Community](https://discourse.jupyter.org/)
- [Security](https://jupyter.org/security)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
