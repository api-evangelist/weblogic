# Oracle WebLogic Server APIs

Collection of APIs and resources for Oracle WebLogic Server administration and management. WebLogic Server is Oracle's enterprise-grade Java EE application server providing high availability, scalability, and comprehensive management capabilities through RESTful management APIs, monitoring and diagnostics, and deployment services.

**Type:** Company
**Website:** [oracle.com/middleware/technologies/weblogic.html](https://www.oracle.com/middleware/technologies/weblogic.html)
**Documentation:** [docs.oracle.com/middleware/fusion-middleware/weblogic-server](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/)

## APIs

| API | Description |
|-----|-------------|
| [RESTful Management Services](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/restm/) | Domain configuration, server lifecycle, cluster and data source management |
| [Monitoring and Diagnostics](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrst/) | Runtime metrics, server health, JVM stats, WLDF diagnostics |
| [Deployment API](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/depgd/) | Deploy, redeploy, undeploy, start, and stop Java EE applications |
| [WLST Scripting Tool](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstc/) | Python-based CLI for automating domain administration |
| [JMX API](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/) | Java Management Extensions access to WebLogic MBeans |

## Artifacts

### OpenAPI Specifications
- [weblogic-restful-management-services-openapi.yml](openapi/weblogic-restful-management-services-openapi.yml) — 57 management operations for domain configuration and server lifecycle
- [weblogic-monitoring-diagnostics-openapi.yml](openapi/weblogic-monitoring-diagnostics-openapi.yml) — 21 monitoring operations for server health, metrics, and diagnostics
- [weblogic-deployment-openapi.yml](openapi/weblogic-deployment-openapi.yml) — 17 deployment operations for application lifecycle management

### Naftiko Capabilities
**Workflow Capabilities:**
- [domain-administration.yaml](capabilities/domain-administration.yaml) — Domain admin (server management + monitoring): 17 tools
- [application-deployment.yaml](capabilities/application-deployment.yaml) — Full deployment lifecycle (deployment + monitoring): 13 tools

**Shared Per-API Definitions:**
- [capabilities/shared/weblogic-management.yaml](capabilities/shared/weblogic-management.yaml) — Management API definition
- [capabilities/shared/weblogic-monitoring.yaml](capabilities/shared/weblogic-monitoring.yaml) — Monitoring API definition
- [capabilities/shared/weblogic-deployment.yaml](capabilities/shared/weblogic-deployment.yaml) — Deployment API definition

### Spectral Rules
- [weblogic-rules.yml](rules/weblogic-rules.yml) — Linting rules enforcing WebLogic API conventions

### JSON Schemas
- [weblogic-server-configuration.json](json-schema/weblogic-server-configuration.json)
- [weblogic-domain-configuration.json](json-schema/weblogic-domain-configuration.json)
- [weblogic-cluster-configuration.json](json-schema/weblogic-cluster-configuration.json)
- [weblogic-datasource-configuration.json](json-schema/weblogic-datasource-configuration.json)
- [weblogic-server-runtime.json](json-schema/weblogic-server-runtime.json)
- [weblogic-application-deployment.json](json-schema/weblogic-application-deployment.json)

### JSON Structures
- [weblogic-server-configuration-structure.json](json-structure/weblogic-server-configuration-structure.json) — Server configuration field documentation

### JSON-LD Contexts
- [weblogic-context.jsonld](json-ld/weblogic-context.jsonld) — Linked data context for WebLogic resources

### Examples
- [weblogic-start-server-example.json](examples/weblogic-start-server-example.json) — Start managed server request/response
- [weblogic-deploy-application-example.json](examples/weblogic-deploy-application-example.json) — Deploy application request/response

### Vocabulary
- [weblogic-vocabulary.yml](vocabulary/weblogic-vocabulary.yml) — Oracle WebLogic terminology and concepts

## Common Properties

- [Portal](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/)
- [Getting Started](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/intro/)
- [Downloads](https://www.oracle.com/middleware/technologies/weblogic-server-downloads.html)
- [Support](https://support.oracle.com)
- [Community](https://community.oracle.com/tech/developers/categories/weblogic-server)
- [Blog](https://blogs.oracle.com/weblogicserver/)
- [GitHub Organization](https://github.com/oracle)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/weblogic)
- [YouTube](https://www.youtube.com/@OracleDevelopers)
- [Status](https://ocistatus.oraclecloud.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
