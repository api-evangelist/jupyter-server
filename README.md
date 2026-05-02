# Jupyter Server (jupyter-server)

Jupyter Server is the backend that powers Jupyter Notebook, JupyterLab, and other Jupyter web applications. It provides the core REST API for managing kernels, sessions, contents, terminals, and configuration, and it hosts the WebSocket endpoints used to communicate with kernels via the Jupyter messaging protocol.

**APIs.yml:** [https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/apis.yml)

## Tags

- Compute
- Interactive Computing
- Kernels
- Notebooks
- Portable
- Workbooks

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-04-28

## APIs

### Jupyter Server REST API

Core REST API for Jupyter Server, providing endpoints for managing kernels, sessions, contents (notebooks and files), terminals, kernel specifications, configuration, and server status.

**Human URL:** https://jupyter-server.readthedocs.io/en/latest/developers/rest-api.html

**Base URL:** http://localhost:8888/api

#### Tags

- Contents, Kernels, REST API, Sessions, Terminals

#### Properties

- [Documentation](https://jupyter-server.readthedocs.io/en/latest/developers/rest-api.html)
- [Repository](https://github.com/jupyter-server/jupyter_server)
- [ChangeLog](https://github.com/jupyter-server/jupyter_server/blob/main/CHANGELOG.md)
- [OpenAPI](openapi/jupyter-server-rest-api-openapi.yml)
- [JSONSchema](json-schema/jupyter-server-contents-model.json)
- [JSONSchema](json-schema/jupyter-server-kernel.json)
- [JSONSchema](json-schema/jupyter-server-session.json)
- [JSONLDContext](json-ld/jupyter-server-context.jsonld)

## Common Properties

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
