# Cisco Hardware (cisco-hardware)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Cisco Hardware is an aggregated index of programmable interfaces for managing Cisco network and data center hardware, including routers, switches, wireless access points, data center fabric, and unified computing systems. The index covers Cisco Catalyst Center (formerly DNA Center), Meraki cloud-managed devices, IOS XE RESTCONF, ACI APIC, UCS Manager, and Intersight cloud infrastructure management. Cisco hardware APIs are exposed through Cisco DevNet, with sandboxes available for developers to test integrations against live hardware without owning physical devices.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cisco-hardware/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cisco-hardware/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Hardware
- Infrastructure
- Networking
- Routers
- Switches

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-23

## APIs

### Cisco Catalyst Center API

The Cisco Catalyst Center API (formerly Cisco DNA Center) provides programmatic management of Cisco enterprise network infrastructure, including discovery, inventory, provisioning, assurance, software image management, and policy. Authentication uses a basic-auth token exchange that returns a session token used as the X-Auth-Token header for subsequent calls. Responses are JSON.

- **Human URL:** [https://developer.cisco.com/docs/dna-center/](https://developer.cisco.com/docs/dna-center/)

#### Tags

- Automation
- Catalyst
- Network Management
- SDN

#### Properties

- [Documentation](https://developer.cisco.com/docs/dna-center/)
- [API Reference](https://developer.cisco.com/docs/dna-center/api/)
- [Sandbox](https://devnetsandbox.cisco.com/)
- [Postman Collection](collections/cisco-hardware.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-hardware.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Meraki Dashboard API

The Meraki Dashboard API is a RESTful interface for cloud-managed Meraki hardware including switches, wireless access points, security appliances, cameras, and sensors. Authentication uses an API key passed in the X-Cisco-Meraki-API-Key header. All endpoints return JSON. The API is fully versioned and an OpenAPI specification is published live at the Meraki dashboard URL.

- **Human URL:** [https://developer.cisco.com/meraki/](https://developer.cisco.com/meraki/)
- **Base URL:** `https://api.meraki.com/api/v1`

#### Tags

- Cloud Managed
- Dashboard
- Switching
- Wireless

#### Properties

- [Documentation](https://developer.cisco.com/meraki/api-latest/)
- [OpenAPI](https://api.meraki.com/api/v1/openapiSpec) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://developer.cisco.com/meraki/api/getting-started/)
- [Postman Collection](collections/cisco-hardware.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-hardware.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco IOS XE RESTCONF API

The IOS XE RESTCONF API exposes Cisco enterprise routers and switches running IOS XE through a model-driven RESTCONF interface that maps directly onto YANG data models. Operations include retrieving device configuration, applying configuration changes, and reading operational state. Authentication uses basic auth and payloads are negotiated as JSON or XML.

- **Human URL:** [https://developer.cisco.com/docs/ios-xe/](https://developer.cisco.com/docs/ios-xe/)

#### Tags

- IOS XE
- RESTCONF
- Routers
- Switches
- YANG

#### Properties

- [Documentation](https://developer.cisco.com/docs/ios-xe/)
- [Y A N G  Models](https://github.com/YangModels/yang/tree/main/vendor/cisco/xe)
- [Sandbox](https://devnetsandbox.cisco.com/RM/Topology)
- [Postman Collection](collections/cisco-hardware.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-hardware.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco APIC REST API

The Cisco APIC REST API manages Application Centric Infrastructure (ACI) data center fabric. The API operates on the ACI Management Information Model and supports tenants, application profiles, endpoint groups, contracts, and fabric infrastructure. Authentication uses login endpoints that return a token cookie used for subsequent object queries and configuration changes.

- **Human URL:** [https://developer.cisco.com/docs/aci/](https://developer.cisco.com/docs/aci/)

#### Tags

- ACI
- APIC
- Data Center
- Fabric
- SDN

#### Properties

- [Documentation](https://developer.cisco.com/docs/aci/)
- [API Reference](https://developer.cisco.com/docs/apic-mim-ref/)
- [SDK](https://github.com/datacenter/acitoolkit)
- [Postman Collection](collections/cisco-hardware.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-hardware.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Intersight API

The Cisco Intersight API is a cloud-based control plane for managing Cisco UCS, HyperFlex, and partner infrastructure. The API follows an OData v4-flavored REST style, uses HTTP signature authentication with API keys, and exposes resource collections for compute, storage, networking, virtualization, and orchestration domains.

- **Human URL:** [https://intersight.com/apidocs/](https://intersight.com/apidocs/)
- **Base URL:** `https://intersight.com/api/v1`

#### Tags

- Cloud Management
- HyperFlex
- Infrastructure
- UCS

#### Properties

- [Documentation](https://intersight.com/apidocs/introduction/overview/)
- [OpenAPI](https://intersight.com/apidocs/downloads/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [SDK](https://github.com/CiscoDevNet/intersight-python)
- [Postman Collection](collections/cisco-hardware.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-hardware.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco UCS Manager API

The UCS Manager XML API is the legacy programmatic interface for managing Cisco Unified Computing System blade and rack servers. The API uses an XML over HTTPS request-response model targeting the UCS object model and provides endpoints for chassis discovery, service profile association, firmware management, and policy configuration.

- **Human URL:** [https://developer.cisco.com/site/ucs-dev-center/](https://developer.cisco.com/site/ucs-dev-center/)

#### Tags

- Compute
- Data Center
- Servers
- UCS
- XML

#### Properties

- [Documentation](https://developer.cisco.com/docs/ucs-manager/)
- [SDK](https://github.com/CiscoUcs/ucsmsdk)
- [Postman Collection](collections/cisco-hardware.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-hardware.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.cisco.com/)
- [Documentation](https://developer.cisco.com/docs/)
- [Sandbox](https://devnetsandbox.cisco.com/)
- [Code  Exchange](https://developer.cisco.com/codeexchange/)
- [Learning](https://developer.cisco.com/learning/)
- [Support](https://developer.cisco.com/site/support/)
- [Community](https://community.cisco.com/)
- [Status Page](https://status.cisco.com/)
- [Terms of Service](https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end_user_license_agreement.html)
- [Privacy Policy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [JSON-LD](json-ld/cisco-hardware-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/cisco-hardware-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
