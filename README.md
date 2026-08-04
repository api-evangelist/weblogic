# Oracle WebLogic Server APIs (weblogic)

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

Collection of APIs and resources for Oracle WebLogic Server administration and management. WebLogic Server is Oracle's enterprise-grade Java EE application server providing high availability, scalability, and comprehensive management capabilities through RESTful management APIs, monitoring and diagnostics, and deployment services.

**APIs.json:** [https://www.oracle.com/middleware/technologies/weblogic.html](https://www.oracle.com/middleware/technologies/weblogic.html)

## Tags

- Application Server
- Enterprise
- Java EE
- Middleware
- Oracle
- WebLogic

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### WebLogic RESTful Management Services API

RESTful API for monitoring and managing WebLogic Server domains, servers, applications, and resources. Provides access to configuration editing, server lifecycle management, cluster administration, data source management, and JMS resource configuration.

#### Tags

- Administration
- Clusters
- Configuration
- Data Sources
- JMS
- Management
- Monitoring
- REST
- Server Lifecycle

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/restm/)
- [OpenAPI](openapi/weblogic-restful-management-services-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weblogic-restful-management-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weblogic-restful-management-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/weblogic-server-configuration.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/weblogic-domain-configuration.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/weblogic-cluster-configuration.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/weblogic-datasource-configuration.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/weblogic-server-runtime.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/weblogic-server-configuration-structure.json)
- [JSON-LD](json-ld/weblogic-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### WebLogic Monitoring and Diagnostics API

API for accessing runtime monitoring data, metrics, and diagnostics information. Provides server health, JVM metrics, thread pool statistics, JDBC data source metrics, JMS statistics, application deployment metrics, and WLDF diagnostics.

#### Tags

- Diagnostics
- Health
- JMX
- Metrics
- Monitoring
- Performance
- WLDF

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrst/)
- [OpenAPI](openapi/weblogic-monitoring-diagnostics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weblogic-monitoring-diagnostics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weblogic-monitoring-diagnostics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/weblogic-server-runtime.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/weblogic-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### WebLogic Deployment API

API for deploying, undeploying, redeploying, and managing applications and shared libraries. Supports the full deployment lifecycle including prepare, activate, start, stop, redeploy, and undeploy operations.

#### Tags

- Applications
- Deployment
- DevOps
- Libraries
- Resources

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/depgd/)
- [OpenAPI](openapi/weblogic-deployment-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weblogic-deployment.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weblogic-deployment.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/weblogic-application-deployment.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/weblogic-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### WebLogic WLST (WebLogic Scripting Tool) API

Python-based scripting interface for automating WebLogic Server administration tasks. Supports online (connected) and offline modes for configuring, deploying, and managing WebLogic domains programmatically.

#### Tags

- Automation
- CLI
- Python
- Scripting

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstc/)
- [Reference](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstg/)
- [Postman Collection](collections/weblogic-deployment.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weblogic-deployment.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/weblogic-monitoring-diagnostics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weblogic-monitoring-diagnostics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/weblogic-restful-management-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weblogic-restful-management-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WebLogic JMX API

Java Management Extensions API for programmatic access to WebLogic Server MBeans. Provides the same management capabilities as the REST API via JMX connections, suitable for Java-based management clients and monitoring tools.

#### Tags

- Java
- JMX
- Management
- MBeans

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/)
- [API Reference](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlmbr/)
- [Postman Collection](collections/weblogic-deployment.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weblogic-deployment.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/weblogic-monitoring-diagnostics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weblogic-monitoring-diagnostics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/weblogic-restful-management-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weblogic-restful-management-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/)
- [Getting Started](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/intro/)
- [Downloads](https://www.oracle.com/middleware/technologies/weblogic-server-downloads.html)
- [Support](https://support.oracle.com)
- [Community](https://community.oracle.com/tech/developers/categories/weblogic-server)
- [Blog](https://blogs.oracle.com/weblogicserver/)
- [Website](https://www.oracle.com/middleware/technologies/weblogic.html)
- [Terms of Service](https://www.oracle.com/legal/terms.html)
- [Privacy Policy](https://www.oracle.com/legal/privacy/)
- [GitHub Organization](https://github.com/oracle)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/weblogic)
- [YouTube](https://www.youtube.com/@OracleDevelopers)
- [Status Page](https://ocistatus.oraclecloud.com/)
- [Vocabulary](vocabulary/weblogic-vocabulary.yml)
- [Spectral Rules](rules/weblogic-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
