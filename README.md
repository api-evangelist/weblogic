# Oracle WebLogic Server APIs (weblogic)

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
