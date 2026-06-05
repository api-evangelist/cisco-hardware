# Cisco Hardware (cisco-hardware)

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
