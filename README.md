# Oracle WebLogic Server (oracle-weblogic)

APIs for managing and monitoring Oracle WebLogic Server - a leading platform for building and deploying enterprise Java applications.

**APIs.json:** [https://www.oracle.com/middleware/weblogic/](https://www.oracle.com/middleware/weblogic/)

## Tags

- Application Server
- Enterprise
- Java EE
- Middleware
- Oracle

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### WebLogic RESTful Management Services API

RESTful API for managing and monitoring WebLogic Server domains, servers, applications, and resources.

- **Human URL:** [https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrest/index.html](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrest/index.html)
- **Base URL:** `http://localhost:7001/management/weblogic/latest`

#### Tags

- Management
- Monitoring
- REST

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrest/index.html)
- [OpenAPI](openapi/oracle-weblogic-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-weblogic-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-weblogic-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrest/authentication.html)
- [JSON Schema](json-schema/oracle-weblogic-server-configuration.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/oracle-weblogic-data-source.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/oracle-weblogic-jms-configuration.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/oracle-weblogic-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### WebLogic Monitoring and Diagnostics API

API for accessing runtime monitoring data, diagnostics information, and performance metrics.

- **Human URL:** [https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/index.html](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/index.html)
- **Base URL:** `http://localhost:7001/management/weblogic/latest/domainRuntime`

#### Tags

- Diagnostics
- JMX
- Metrics
- Monitoring

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/index.html)
- [Guide](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlach/monitor.html)
- [OpenAPI](openapi/oracle-weblogic-monitoring-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-weblogic-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-weblogic-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/oracle-weblogic-domain-runtime.json) — [JSON Schema](https://json-schema.org/specification)

### WebLogic Deployment API

API for deploying, undeploying, and managing application deployments on WebLogic Server.

- **Human URL:** [https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrest/op-management-weblogic-latest-edit-appdeployments-post.html](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrest/op-management-weblogic-latest-edit-appdeployments-post.html)
- **Base URL:** `http://localhost:7001/management/weblogic/latest/edit/appDeployments`

#### Tags

- Applications
- Deployment
- Lifecycle

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrest/resources.html)
- [Tutorial](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/depgd/index.html)
- [OpenAPI](openapi/oracle-weblogic-deployment-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-weblogic-deployment.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-weblogic-deployment.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/oracle-weblogic-deployment.json) — [JSON Schema](https://json-schema.org/specification)

### WebLogic WLST (WebLogic Scripting Tool) API

Python-based scripting interface for automating WebLogic Server administration tasks.

- **Human URL:** [https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstc/index.html](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstc/index.html)
- **Base URL:** `https://localhost:5556`

#### Tags

- Administration
- Automation
- Python
- Scripting

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstc/index.html)
- [Reference](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstg/index.html)
- [Postman Collection](collections/oracle-weblogic-deployment.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-weblogic-deployment.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/oracle-weblogic-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-weblogic-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/oracle-weblogic-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-weblogic-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WebLogic JMX API

Java Management Extensions API for programmatic management and monitoring of WebLogic Server.

- **Human URL:** [https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/index.html](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/index.html)
- **Base URL:** `service:jmx:rmi:///jndi/rmi://localhost:7001/jmxrmi`

#### Tags

- Java
- JMX
- Management
- MBeans

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/index.html)
- [API Reference](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlapi/index.html)
- [Examples](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/examples.html)
- [Postman Collection](collections/oracle-weblogic-deployment.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-weblogic-deployment.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/oracle-weblogic-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-weblogic-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/oracle-weblogic-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-weblogic-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Support](https://support.oracle.com/)
- [Documentation](https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/)
- [Downloads](https://www.oracle.com/middleware/technologies/weblogic-server-downloads.html)
- [Community](https://community.oracle.com/customerconnect/categories/appsuite-weblogic-server)
- [License](https://www.oracle.com/downloads/licenses/standard-license.html)
- [Blog](https://blogs.oracle.com/weblogicserver/)
- [Website](https://www.oracle.com/middleware/technologies/weblogic.html)
- [Terms of Service](https://www.oracle.com/legal/terms.html)
- [Privacy Policy](https://www.oracle.com/legal/privacy/)
- [GitHub Organization](https://github.com/oracle)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/weblogic)
- [YouTube](https://www.youtube.com/@OracleDevelopers)
- [Sign Up](https://cloud.oracle.com/)
- [Status Page](https://ocistatus.oraclecloud.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
