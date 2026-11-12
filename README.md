# Hi, I'm Bruce Weygandt

**Compliance engineer.** I'm a Forward Deployed Engineer at [Paramify](https://www.paramify.com), where I build the Python evidence fetchers and regex validators that prove FedRAMP 20x and CMMC controls with machine-readable evidence, and work with clients as they prepare for assessments.

[Website and blog](https://bruceweygandt.github.io) · [LinkedIn](https://linkedin.com/in/bruce-weygandt) · [bruce.weyg@gmail.com](mailto:bruce.weyg@gmail.com)

---

## Open source: paramify-fetchers

[paramify/paramify-fetchers](https://github.com/paramify/paramify-fetchers) is Paramify's open-source (GPLv3) collection of compliance evidence fetchers for AWS, Azure, GCP, Oracle Cloud, Okta, Wiz and more. I'm one of six engineers contributing to it. My merged pull requests:

**Azure** (FedRAMP 20x evidence for Azure Government and commercial tenants)
- [#114](https://github.com/paramify/paramify-fetchers/pull/114) Azure Managed Redis, DNS, VPN Gateway and Virtual WAN fetchers
- [#118](https://github.com/paramify/paramify-fetchers/pull/118) Azure private endpoint and private DNS zone fetchers
- [#119](https://github.com/paramify/paramify-fetchers/pull/119) Classic Azure Cache for Redis configuration fetcher
- [#148](https://github.com/paramify/paramify-fetchers/pull/148) Azure flow log, AI services, managed identity and API Management fetchers
- [#149](https://github.com/paramify/paramify-fetchers/pull/149) Azure AI hub, container workloads and data services fetchers
- [#199](https://github.com/paramify/paramify-fetchers/pull/199) Fix for the private endpoint and DNS zone fetchers

**Other platforms**
- [#203](https://github.com/paramify/paramify-fetchers/pull/203) Oracle Cloud fetcher set: 15 fetchers
- [#212](https://github.com/paramify/paramify-fetchers/pull/212) FedRAMP Marketplace vendor certification fetchers
- [#97](https://github.com/paramify/paramify-fetchers/pull/97) New Jira category and Jira site inventory fetcher
- [#2](https://github.com/paramify/paramify-fetchers/pull/2), [#4](https://github.com/paramify/paramify-fetchers/pull/4) AWS GuardDuty findings fetcher
- [#154](https://github.com/paramify/paramify-fetchers/pull/154) Regenerated the KSI mapping docs

**Earlier version:** [paramify/legacy-evidence-fetchers](https://github.com/paramify/legacy-evidence-fetchers)
- [#2](https://github.com/paramify/legacy-evidence-fetchers/pull/2) Okta IAM evidence fetchers
- [#10](https://github.com/paramify/legacy-evidence-fetchers/pull/10) IAM-07 fix so API service accounts aren't counted as user accounts

## Projects

| Project | What it is | Stack |
|---|---|---|
| [aca-capstone-terraform](https://github.com/bruceweygandt/aca-capstone-terraform) | Re-architecture of a single-host PHP and MySQL app into a highly available, private three-tier AWS design, assessed against FedRAMP 20x KSIs and NIST 800-53, with scheduled evidence collection | Terraform, AWS |
| [purview-action-update](https://github.com/paramify/purview-action-update) | Updates Microsoft Purview Compliance Manager improvement actions from Paramify. Compliance Manager has no write API, so the tool fills in the Action Update workbook for re-upload. It reads Paramify only and never connects to Microsoft 365. Published as Paramify open source. | Python |
| [audit-assessment-converter](https://github.com/bruceweygandt/audit-assessment-converter) | Terminal UI that turns an auditor's CSV report into an audit assessment file ready to import into Paramify, with a live preview and demo data | Go |
| [bruceweygandt.github.io](https://github.com/bruceweygandt/bruceweygandt.github.io) | My website and engineering blog | HTML, CSS |

## Writing

Write-ups of what I've built, on [my blog](https://bruceweygandt.github.io/blog/index.html):
- [Writing the validators before the fetcher](https://bruceweygandt.github.io/blog/validators-before-the-fetcher.html)
- [When "no detectors" is still valid evidence](https://bruceweygandt.github.io/blog/no-detectors-is-still-evidence.html)
- [Vulnerability evidence straight from the scanner](https://bruceweygandt.github.io/blog/vulnerability-reports-from-the-api.html)
- [CMMC Level 2, one assessment objective at a time](https://bruceweygandt.github.io/blog/cmmc-one-objective-at-a-time.html)

## What I work with

- **Frameworks:** FedRAMP 20x, CMMC Level 2, NIST 800-53 Rev 5, NIST CSF 2.0, SOC 2, ISO 27001, ISMAP
- **Engineering:** Python, Go, Bash, Terraform, REST and Graph APIs, regex validators, JSON schemas, Claude API, MCP
- **Platforms:** AWS GovCloud, Azure Government, Oracle Cloud, Microsoft 365 GCC High, Entra ID, Okta, Wiz, SentinelOne, Qualys
- **Credentials:** CompTIA Security+ · ISC2 CISSP in progress · ISO 27001 Lead Auditor training
- **Languages:** English and Japanese, native-level in both
