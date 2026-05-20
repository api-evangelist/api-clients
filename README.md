# API Clients (api-clients)
An index and topic collection covering API clients, the developer tools used to inspect, debug, exercise, and document APIs interactively. API clients include desktop and web applications such as Postman, Insomnia, Bruno, Hoppscotch, HTTPie, Paw, Yaak, Thunder Client, and Apidog, along with command-line HTTP clients and language-specific HTTP libraries presented as products. These tools sit between developers and APIs, providing request building, response inspection, collection management, environment variables, scripting, mocking, and team collaboration features that accelerate every stage of the API consumption and integration lifecycle.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Client, HTTP Client, API Debugging, Developer Tools, REST Client, API Testing

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - HTTP Request Schema](https://raw.githubusercontent.com/api-evangelist/api-clients/refs/heads/main/json-schema/api-clients-http-request-schema.json)
- [JSONSchema - Collection Schema](https://raw.githubusercontent.com/api-evangelist/api-clients/refs/heads/main/json-schema/api-clients-collection-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/api-clients/refs/heads/main/json-ld/api-clients-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/api-clients/refs/heads/main/vocabulary/api-clients-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Interactive Request Building | API clients provide visual editors for composing HTTP requests with methods, URLs, headers, query parameters, and request bodies, removing the friction of hand-crafting requests in code. |
| Response Inspection and Pretty-Printing | Clients render JSON, XML, HTML, image, and binary responses with syntax highlighting, formatting, and inspection tools that make debugging and exploration far faster than raw output. |
| Collections and Workspaces | Tools like Postman, Insomnia, and Bruno organize requests into named collections and shared workspaces that capture how an API is intended to be exercised end-to-end. |
| Environments and Variables | API clients let developers parameterize requests across environments (dev, staging, prod) using variable substitution, secret stores, and dynamic value providers. |
| Authentication Flows | Built-in support for Bearer tokens, API keys, Basic auth, OAuth 2.0 with PKCE, AWS SigV4, and other auth mechanisms removes the need to script authentication by hand. |
| Scripting, Assertions, and Testing | Pre-request and post-response scripting hooks combined with assertions turn ad-hoc requests into runnable, repeatable test suites that can be executed in CI. |
| Mocking and Local Development | Many clients can publish mock servers from collections or specs, letting frontend and consumer teams build against a stable contract before the real API is ready. |
| Specification Import and Sync | API clients import OpenAPI, AsyncAPI, GraphQL SDL, and Postman Collection formats so request libraries stay in sync with the API source of truth. |

## Use Cases

| Name | Description |
|------|-------------|
| Exploring a Third-Party API | Developers use Postman, Insomnia, or HTTPie to send their first requests against a new third-party API, inspect responses, and understand its behavior before writing integration code. |
| Debugging a Failing Integration | When a production integration fails, developers replay the failing request in a client like Bruno or Paw, tweak headers and payloads, and isolate the root cause without redeploying code. |
| Building Reusable Request Collections | Teams curate shared collections of API requests in Postman or Insomnia workspaces so engineers, support staff, and QA can run common operations consistently. |
| Local Mocking for Frontend Development | Frontend teams generate mock servers from API collections or specs so they can develop UI against realistic responses before the backend is finished. |
| API Contract Testing in CI | Tools like Hurl, Step CI, and Postman's Newman run collections of requests with assertions as part of CI pipelines to catch regressions against contracts. |
| gRPC and GraphQL Exploration | Clients like Kreya, Yaak, and Insomnia provide first-class support for gRPC reflection and GraphQL introspection so developers can explore non-REST APIs interactively. |
| Reverse-Engineering and Traffic Capture | Tools like mitmproxy, Charles Proxy, and Fiddler capture live HTTP traffic from mobile apps, browsers, or services to understand undocumented or third-party APIs. |

## Integrations

| Name | Description |
|------|-------------|
| Postman | The most widely adopted API client and platform with collections, environments, mock servers, monitors, and team workspaces serving millions of developers. |
| Insomnia | Open-source desktop API client from Kong supporting REST, GraphQL, gRPC, and WebSocket with a strong focus on simplicity and design workflows. |
| Bruno | Open-source, file-based, offline-first API client that stores collections as plain text files in your git repository, making collections diffable and reviewable. |
| Hoppscotch | Open-source web-based API client supporting REST, GraphQL, WebSocket, SSE, and MQTT with no install required. |
| HTTPie | Human-friendly command-line HTTP client with intuitive syntax, JSON support, and a desktop GUI counterpart for terminal-first developers. |
| Paw | Native macOS API client (now part of RapidAPI) with deep macOS integration, advanced dynamic values, and code-generation across many languages. |
| Yaak | Modern open-source desktop client supporting REST, GraphQL, and gRPC with a focus on local-first data and offline workflows. |
| Apidog | All-in-one platform combining API design, debugging, mocking, and automated testing in a single workspace, often positioned as a Postman alternative. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [HTTP Request Schema](json-schema/api-clients-http-request-schema.json)
- [Collection Schema](json-schema/api-clients-collection-schema.json)

### JSON Structure

- [HTTP Request Structure](json-structure/api-clients-http-request-structure.json)
- [Collection Structure](json-structure/api-clients-collection-structure.json)

### JSON-LD

- [API Clients Context](json-ld/api-clients-context.jsonld)

## Vocabulary

- [API Clients Vocabulary](vocabulary/api-clients-vocabulary.yaml) - Unified taxonomy mapping 5 resources, 8 actions, 4 workflows, and 4 personas across API client tools, debugging, collections, and request lifecycle management

## Network

This index references the following API client repositories:

- [API Dash](https://github.com/api-evangelist/api-dash)
- [Apidog](https://github.com/api-evangelist/apidog)
- [Axios](https://github.com/api-evangelist/axios)
- [Bruno](https://github.com/api-evangelist/bruno)
- [Charles Proxy](https://github.com/api-evangelist/charles-proxy)
- [cURL](https://github.com/api-evangelist/curl)
- [Fiddler](https://github.com/api-evangelist/fiddler)
- [Firecamp](https://github.com/api-evangelist/firecamp)
- [Hoppscotch](https://github.com/api-evangelist/hoppscotch)
- [HTTPie](https://github.com/api-evangelist/httpie)
- [Hurl](https://github.com/api-evangelist/hurl)
- [Insomnia](https://github.com/api-evangelist/insomnia)
- [Kreya](https://github.com/api-evangelist/kreya)
- [Microcks](https://github.com/api-evangelist/microcks)
- [Mitmproxy](https://github.com/api-evangelist/mitmproxy)
- [Nightingale](https://github.com/api-evangelist/nightingale)
- [Paw](https://github.com/api-evangelist/paw)
- [Postman](https://github.com/api-evangelist/postman)
- [RapidAPI](https://github.com/api-evangelist/rapidapi)
- [ReadyAPI](https://github.com/api-evangelist/readyapi)
- [Restfox](https://github.com/api-evangelist/restfox)
- [Scalar](https://github.com/api-evangelist/scalar)
- [Step CI](https://github.com/api-evangelist/step-ci)
- [Stoplight](https://github.com/api-evangelist/stoplight)
- [Thunder Client](https://github.com/api-evangelist/thunder-client)
- [Voiden](https://github.com/api-evangelist/voiden)
- [Yaak](https://github.com/api-evangelist/yaak)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
