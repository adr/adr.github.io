---
icon: fas fa-briefcase
order: 4
title: Decision Capturing Tools
---

> The following list is rather inclusive.
> Please find out about the status and the maturity of the list entries for yourself by following the links.
> We are happy to include more candidate assets here.
{: .prompt-info }

- [adr-manager](https://adr.github.io/adr-manager/#/): Craft MADR 2.x templates directly in the Web Browser.
- [adr-tools](https://github.com/npryce/adr-tools) - bash scripts to manage ADRs in the [Nygard format](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions.html). [example](https://github.com/npryce/adr-tools/blob/master/doc/adr/0002-implement-as-shell-scripts.md).
  - Ansible script to install adr-tools: [ansible-adr-tools](https://github.com/escalate/ansible-adr-tools)
  - C# rewrite: [adr-cli](https://github.com/GingerTommy/adr-cli)
  - Go rewrite: [adr](https://github.com/marouni/adr)
  - Java rewrite: [adr-j](https://github.com/adoble/adr-j)
  - ESM Node.js port: [adr-tools](https://github.com/meza/adr-tools)
  - Node.js rewrite: [adr](https://github.com/phodal/adr)
  - PHP version: [phpadr](https://github.com/globtec/phpadr)
  - Powershell module: [adr-ps](https://github.com/rdagumampan/adr-ps)
  - Python rewrite: [adr-tools-python](https://pypi.org/project/adr-tools-python/)
  - Another Powershell module: [ArchitectureDecisionRecords](https://github.com/ajoberstar/ArchitectureDecisionRecords)
  - Rust rewrite: [adrs](https://github.com/joshrotenberg/adrs)
- [adr-plugin](https://github.com/backstage/community-plugins/tree/main/workspaces/adr/plugins/adr) - plugin to explore and search ADRs within a backstage based developer portal. Search at scale across mutliple orgs/repos.
- [adr-viewer](https://github.com/mrwilson/adr-viewer) - python application to generate a website from a set of ADRs.
- [architectural-decision](https://github.com/cspray/architectural-decision): PHP library to create ADRs using PHP8 Attributes.
- [dotnet-adr](https://github.com/endjin/dotnet-adr) - A cross platform .NET Global Tool for creating and managing Architectural Decision Records (ADR).
- [Embedded Architectural Decision Records](https://github.com/adr/e-adr#embedded-architectural-decision-records), which shows how a distributed AD log can be embedded in Java Code via ADR annotations.
- [Log4brains](https://github.com/thomvaill/log4brains): CLI and web UI to log and publish your ADRs as a static website. Currently in [low maintenance mode](https://github.com/thomvaill/log4brains/discussions/108#discussioncomment-7607483).
- [Loqbooq](https://loqbooq.app): Web App with Slack integration to record ADR-inspired decision logs
- [Talo](https://github.com/canpolat/talo): CLI (and dotnet tool) to manage and export ADRs, RFCs and custom software design document types.

For a more detailed list for tooling for MADR, please head to <https://adr.github.io/madr/tooling.html>.

### Tooling related to architecture management

- [ArchUnit](https://github.com/TNG/ArchUnit): unit tests for architecture
- [docToolchain](https://doctoolchain.github.io/docToolchain/): docToolchain is an implementation of the [docs-as-code](https://www.writethedocs.org/guide/docs-as-code/) approach for software architecture plus some additional automation.
- [Structurizr](https://www.structurizr.com/): Structurizr is a collection of tooling to help you visualise, document and explore your software architecture using the [C4 model](https://c4model.com/).

### Interesting, but unmaintained tooling

- [adr-log](https://github.com/adr/adr-log): Generates an architectural decision log out of MADRs.
- [ADMentor](https://github.com/IFS-HSR/ADMentor) Architectural Decision Modeling Add-In for [Sparx Enterprise Architect](https://www.sparxsystems.de/uml/neweditions/)
- [eadlsync](https://adr.github.io/eadlsync/): Synchronizes embedded architectural decision records with a repository of architectural decisions.
- [SE Repo](https://github.com/adr/serepo): Software Engineering Repository. A repository for versioning software engineering artifacts, which can be architectural decisions, patterns, and others.

