# Awesome-Saas-Security-Application-Connectivity

## Top SaaS Security & Application Connectivity Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on SaaS Discovery, Access Governance & Open-Source Connectivity Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial SaaS security and connectivity platforms** and **open-source projects** that discover SaaS applications, govern access, secure app-to-app connections, and automate identity lifecycle across cloud applications.



**Examples** include AWS AppFabric, AppOmni, DoControl, Obsidian Security, Adaptive Shield, Wing Security, Grip Security, Torii, BetterCloud, and Lumos (the category leaders).



**Open-source emphasis**: SaaS security and connectivity is an emerging open-source domain. **Keycloak** and **Authentik** provide identity foundations for SaaS SSO, **OPA** and **Casbin** enforce authorization policy, **n8n** and **Activepieces** automate SaaS-to-SaaS connectivity, and **CloudQuery** and **Steampipe** provide SaaS asset visibility. **DefectDojo** aggregates security findings, and **OpenSearch** handles audit log analysis. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS AppFabric](https://aws.amazon.com/appfabric/)**  

  **AWS's SaaS application integration service** — connects SaaS apps for unified security and productivity insights . **Normalizes audit logs** from SaaS applications into OCSF format . **Best for AWS-centric SaaS security** .



- **[AppOmni](https://appomni.com/)**  

  **SaaS security posture management (SSPM)** — continuous monitoring and configuration assessment . **Best for enterprise SaaS security** .



- **[DoControl](https://www.docontrol.io/)**  

  **SaaS security platform** — data access governance, threat detection, and automated remediation . **Best for SaaS data protection** .



- **[Obsidian Security](https://www.obsidiansecurity.com/)**  

  **SaaS security posture management** — threat detection and compliance for SaaS . **Best for enterprise SaaS security** .



- **[Adaptive Shield](https://www.adaptiveshield.com/)**  

  **SaaS security posture management** — misconfiguration detection and remediation . **Best for SSPM** .



- **[Wing Security](https://www.wing.security/)**  

  **SaaS security platform** — discovery, posture management, and shadow IT detection . **Best for SaaS security automation** .



- **[Grip Security](https://www.grip.security/)**  

  **SaaS identity and access management** — discovery and governance for SaaS apps . **Best for SaaS identity governance** .



- **[Torii](https://www.toriihq.com/)**  

  **SaaS management platform** — discovery, management, and optimization of SaaS applications . **Best for SaaS spend and security** .



- **[BetterCloud](https://www.bettercloud.com/)**  

  **SaaS operations platform** — automation and security for SaaS applications . **Best for SaaS workflow automation** .



- **[Lumos](https://www.lumos.com/)**  

  **SaaS identity and access management** — app discovery, access reviews, and automated provisioning . **Best for SaaS access governance** .



## Open-Source GitHub Projects



### Identity & Access Management



- **[Keycloak](https://github.com/keycloak/keycloak)**  

  **The leading open-source identity provider**, Apache-2.0 licensed with **36,000+ GitHub stars** . **SSO, MFA, identity brokering, and user federation** . **The identity foundation for SaaS SSO** — supports OAuth 2.0, OIDC, and SAML . **Best for SaaS identity integration** .



- **[Authentik](https://github.com/goauthentik/authentik)**  

  **Flexible open-source identity provider**, MIT/GPL licensed with **10,000+ GitHub stars** . **OAuth2, SAML, LDAP, and proxy support** . **Flow-based authentication customization** . **Best for SaaS SSO with customization** .



- **[Zitadel](https://github.com/zitadel/zitadel)**  

  **Identity infrastructure with multi-tenancy and API-first design**, Apache-2.0 licensed . **OIDC, OAuth2, SAML2, passkeys/FIDO2, and SCIM 2.0** . **Best for modern SaaS identity** .



- **[Ory](https://github.com/ory)**  

  **Open-source identity infrastructure** — Kratos (identity), Hydra (OAuth2), Keto (authorization), Oathkeeper (access proxy) . Apache-2.0 licensed . **Best for modular SaaS identity** .



### Authorization & Policy



- **[Casbin](https://github.com/casbin/casbin)**  

  **Open-source authorization library**, Apache-2.0 licensed with **17,000+ GitHub stars** . **ACL, RBAC, and ABAC** for multi-tenant SaaS . **Best for SaaS authorization** .



- **[Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa)**  

  **General-purpose policy engine**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Unified policy enforcement across SaaS, Kubernetes, and CI/CD** . **Best for policy-as-code** .



- **[OpenFGA](https://github.com/openfga/openfga)**  

  **Fine-grained authorization**, Apache-2.0 licensed . **Google Zanzibar-inspired relationship-based access control** . **Best for SaaS authorization at scale** .



- **[SpiceDB](https://github.com/authzed/spicedb)**  

  **Authorization database**, Apache-2.0 licensed . **Zanzibar-inspired permissions system** . **Best for SaaS permissions** .



- **[Permify](https://github.com/Permify/permify)**  

  **Open-source authorization service**, Apache-2.0 licensed . **Zanzibar-inspired with multi-tenancy** . **Best for SaaS authorization** .



- **[Cerbos](https://github.com/cerbos/cerbos)**  

  **Policy-as-code authorization**, Apache-2.0 licensed . **Language-agnostic with stateless design** . **Best for SaaS authorization** .



- **[Oso](https://github.com/osohq/oso)**  

  **Open-source authorization framework**, Apache-2.0 licensed . **Polar language for authorization logic** . **Best for SaaS authorization** .



### SaaS Discovery & Security Posture



- **[CloudQuery](https://github.com/cloudquery/cloudquery)**  

  **Open-source cloud asset inventory**, MPL-2.0 licensed with **6,000+ GitHub stars** . **Extracts, transforms, and loads cloud and SaaS configuration** . **Best for SaaS and cloud asset visibility** .



- **[Steampipe](https://github.com/turbot/steampipe)**  

  **Zero-ETL cloud API querying with SQL**, AGPL-3.0 licensed with **7,000+ GitHub stars** . **Query SaaS and cloud resources with SQL** . **Best for SaaS security posture queries** .



- **[DefectDojo](https://github.com/DefectDojo/django-DefectDojo)**  

  **Open-source vulnerability management**, Apache-2.0 licensed . **Aggregates findings from 200+ security tools** . **Best for SaaS security findings aggregation** .



- **[Wazuh](https://github.com/wazuh/wazuh)**  

  **Open-source security platform with SIEM and XDR**, GPLv2 licensed with **16,646+ GitHub stars** . **Compliance modules for PCI-DSS, NIST 800-53, and GDPR** . **Best for security monitoring and compliance** .



- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**  

  **Open-source search and analytics suite**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Log analytics and security analytics** . **Best for SaaS audit log analysis** .



### SaaS Connectivity & Automation



- **[n8n](https://github.com/n8n-io/n8n)**  

  **Workflow automation platform**, Sustainable Use License with **100,000+ GitHub stars** . **400+ integrations for SaaS automation** . **Best for SaaS-to-SaaS workflow automation** .



- **[Activepieces](https://github.com/activepieces/activepieces)**  

  **MIT-licensed AI-native automation platform**, MIT licensed with **23,000+ GitHub stars** . **200+ integrations with MCP server support** . **Best for open-source SaaS automation** .



- **[Windmill](https://github.com/windmill-labs/windmill)**  

  **Developer-first automation platform**, AGPLv3 licensed with **10,000+ GitHub stars** . **Scripts in Python, TypeScript, Go, Bash, or SQL** . **Best for developer-centric SaaS automation** .



- **[Node-RED](https://github.com/node-red/node-red)**  

  **Flow-based programming for event-driven applications**, Apache-2.0 licensed with **20,000+ GitHub stars** . **Visual wiring of SaaS APIs and services** . **Best for visual SaaS integration** .



- **[Kestra](https://github.com/kestra-io/kestra)**  

  **Declarative orchestration platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **YAML-based workflows with 500+ plugins** . **Best for declarative SaaS orchestration** .



- **[Apache Airflow](https://github.com/apache/airflow)**  

  **Workflow orchestration standard**, Apache-2.0 licensed with **35,000+ GitHub stars** . **Python-based DAGs for SaaS integration workflows** . **Best for complex SaaS orchestration** .



### Additional Strong Open-Source Options



- **Apache Camel** — Integration framework with 300+ connectors .

- **Benthos (Redpanda Connect)** — Stream processing without code .

- **Vector** — Observability data pipeline .

- **Fluentd** — Unified logging layer .

- **Grafana Loki** — Log aggregation .

- **Graylog** — Log management .

- **Authelia** — Authentication and authorization server .

- **Pomerium** — Identity-aware access proxy .



**Frameworks for building custom SaaS security and connectivity solutions**: Combine **Keycloak** or **Authentik** for SaaS SSO and identity . Use **OPA**, **Casbin**, or **OpenFGA** for authorization and policy . Deploy **CloudQuery** or **Steampipe** for SaaS asset visibility . Integrate **DefectDojo** for security findings aggregation . Use **n8n**, **Activepieces**, or **Windmill** for SaaS-to-SaaS automation . Deploy **OpenSearch** or **Loki** for audit log analysis . Note that true enterprise SSPM with discovery, posture assessment, and automated remediation (AppOmni, Obsidian, Adaptive Shield) remains primarily commercial territory; open-source stacks provide strong identity, authorization, policy, and automation foundations that require integration for complete SaaS security posture management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- SaaS security platforms access sensitive application data and configurations. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **SaaS security requires continuous monitoring** — misconfigurations, shadow IT, and permission sprawl are ongoing risks. Open-source tools provide visibility but require integration and tuning .

- **License considerations**: n8n uses Sustainable Use License (fair-code, not OSI), Activepieces uses MIT, Windmill uses AGPLv3, and Keycloak uses Apache-2.0. Verify licensing against your use case before committing .

- **Open-source SSPM requires operational expertise** — discovery, posture assessment, and remediation workflows require integration across multiple tools. Commercial platforms provide unified SSPM with vendor support.

- The open-source ecosystem provides strong identity, authorization, policy, and automation foundations, but **unified SSPM with discovery, posture assessment, and automated remediation** remain primarily commercial offerings.



---



**Made for security engineers, SaaS administrators, and organizations seeking SaaS security sovereignty.**  

Let's make SaaS security and application connectivity more open, transparent, and automated.
