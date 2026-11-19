# ServiceNow Learning Lab (CSA → CAD → CIS-CSM)

A structured engineering lab, architecture notebook, and script repository documenting my deep dive into the ServiceNow platform—progressing from core administration to scoped application development and Customer Service Management (CSM) implementation.

> **Note on Repository Architecture:** ServiceNow Studio enforces a 1:1 mapping between a Git repository and a Scoped Application. This repo houses my architectural notes, `Scripts - Background` labs, Glide API benchmarks, and REST payloads. Standalone Scoped Applications built with Studio or the ServiceNow SDK (`now-sdk`) live in their own dedicated repositories linked below.

---

## Certification Roadmap

| Stage | Credential | Core Focus | Status |
| :--- | :--- | :--- | :--- |
| **1** | **CSA** *(Certified System Administrator)* | Data model (`task` inheritance), ACL evaluation, Update Sets, Flow Designer, core platform mechanics | In Progress |
| **2** | **CAD** *(Certified Application Developer)* | Scoped app architecture, ES2021 vs. Rhino ES5, `GlideRecord`/`GlideAggregate`, `GlideAjax`, Script Includes, IntegrationHub | Planned |
| **3** | **CIS-CSM** *(Certified Implementation Specialist – CSM)* | B2B/B2C data models (Accounts, Contacts, Consumers, Install Base), Case lifecycle, AWA routing, Portals | Planned |

---

## Repository Structure

```text
servicenow-learning-lab/
├── 01-csa-platform-fundamentals/   # Data model, ACLs, CMDB, Update Sets, Flow Designer
├── 02-cad-app-development/         # Client/Server scripting, Glide APIs, Script Includes, REST
├── 03-cis-csm-implementation/      # CSM data model, Case management, AWA, Portals
├── scripts-background/             # Runnable server-side JS snippets & SQL debug labs
├── api-payloads/                   # Table API, Scripted REST, and cURL/Postman collections
└── notes/                          # Architecture deep dives & exam vs. production gotchas