---
title: Decision Capturing Tools
toc: true
categories: [adr]
---

> The following lists are rather inclusive and sorted alphabetically.
> Please find out about the status and the maturity of the list entries for yourself by following the links.
> We are happy to include more candidate assets here.
{: .prompt-info }

## Tooling to create and maintain decision files

### Any template

- [ADG (Architectural Decision Guidance)](https://github.com/adr/ad-guidance-tool), a command-line tool written in Go for modeling, managing, and reusing architectural decisions in a lightweight and structured way (step-by-step usage example in this [Medium story](https://medium.com/olzzio/adg-a-light-architectural-decision-guidance-and-management-tool-902fd65d2185)). Template options: Nygard, MADR (basic), QOC.
- [dotnet-adr](https://github.com/endjin/dotnet-adr) - A cross platform .NET Global Tool for creating and managing Architectural Decision Records (ADR).

### MADR template

| Name                                                                                                        | MADR Version                          | Comment                                                                                                                 |
| ----------------------------------------------------------------------------------------------------------- | ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| [adr-log](https://github.com/adr/adr-log?tab=readme-ov-file#adr-log-)                                       | 2.1.2                                 | CLI to keep an `index.md` file updated with all ADRs                                                                    |
| [ADR Manager](https://adr.github.io/adr-manager/)                                                           | 2.1.2                                 | Web-based UI connecting to GitHub to directly edit ADRs in a form-based way                                             |
| [ADR Manager VS Code Extension](https://github.com/adr/vscode-adr-manager)                                  | 2.1.2                                 | Visual Studio Code (VS Code) extension                                                                                  |
| [Backstage ADR plugin](https://github.com/backstage/community-plugins/tree/main/workspaces/adr/plugins/adr) | 2.1.2 and 3.x                         | plugin to explore and search ADRs within a backstage based developer portal. Search at scale across mutliple orgs/repos |
| [Hugo Markdown ADR Tools](https://github.com/butonic/adr-tools)                                             | 2.1.2.                                | CLI to create and update ADRs                                                                                           |
| [Log4brains](https://github.com/thomvaill/log4brains)                                                       | 2.1.2 without numbers in the filename | Supports both nice rendering of ADRs and creation of ADRs in a command line.                                            |
| [pyadr](https://github.com/opinionated-digital-center/pyadr)                                                | 2.1.2                                 | CLI to help with an ADR process lifecycle (proposal/acceptance/rejection/deprecation/superseding)                       |

### Nygard template

- [adr-tools](https://github.com/npryce/adr-tools) - bash scripts to manage ADRs in the [Nygard format](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions.html). [example](https://github.com/npryce/adr-tools/blob/master/doc/adr/0002-implement-as-shell-scripts.md).
  - Ansible script to install adr-tools: [ansible-adr-tools](https://github.com/escalate/ansible-adr-tools)
  - C# rewrite: [adr-cli](https://github.com/GingerTommy/adr-cli)
  - Go rewrite: [adr](https://github.com/marouni/adr)
  - Java rewrite: [adr-j](https://github.com/adoble/adr-j)
  - ESM Node.js port: [adr-tools](https://github.com/meza/adr-tools)
  - Node.js rewrite: [adr](https://github.com/phodal/adr)
  - PHP version: [phpadr](https://github.com/bellangelo/phpadr)
  - Powershell module: [adr-ps](https://github.com/rdagumampan/adr-ps)
  - Python rewrite: [adr-tools-python](https://pypi.org/project/adr-tools-python/)
  - Python rewrite: [ADR-py](https://github.com/AlTosterino/ADR-py)
  - Another Powershell module: [ArchitectureDecisionRecords](https://github.com/ajoberstar/ArchitectureDecisionRecords)
  - Rust rewrite: [adrs](https://github.com/joshrotenberg/adrs)
- [adr-viewer](https://github.com/mrwilson/adr-viewer) - python application to generate a website from a set of ADRs.
- [architectural-decision](https://github.com/cspray/architectural-decision): PHP library to create ADRs using PHP8 Attributes.
- [Loqbooq](https://loqbooq.app): Commerical Web App with Slack integration to record ADR-inspired decision logs
- [Talo](https://github.com/canpolat/talo): CLI (and dotnet tool) to manage and export ADRs, RFCs and custom software design document types.

#### Renderings

- [adr-viewer](https://pypi.org/project/adr-viewer/) - renders ADRs in a web page

## Tooling close to the code

- [(Java) Embedded Architectural Decision Records](https://github.com/adr/e-adr#embedded-architectural-decision-records), which shows how a distributed AD log can be embedded in Java Code via ADR annotations.

## Tooling related to architecture management

- [ArchUnit](https://github.com/TNG/ArchUnit): unit tests for architecture
- [docToolchain](https://doctoolchain.github.io/docToolchain/): docToolchain is an implementation of the [docs-as-code](https://www.writethedocs.org/guide/docs-as-code/) approach for software architecture plus some additional automation.
- [Structurizr](https://www.structurizr.com/): Structurizr is a collection of tooling to help you visualise, document and explore your software architecture using the [C4 model](https://c4model.com/).

## Interesting, but unmaintained tooling

- [adr-log](https://github.com/adr/adr-log): Generates an architectural decision log out of MADRs.
- [ADMentor](https://github.com/IFS-HSR/ADMentor) Architectural Decision Modeling Add-In for [Sparx Enterprise Architect](https://www.sparxsystems.de/uml/neweditions/)
- [eadlsync](https://adr.github.io/eadlsync/): Synchronizes embedded architectural decision records with a repository of architectural decisions.
- [SE Repo](https://github.com/adr/serepo): Software Engineering Repository. A repository for versioning software engineering artifacts, which can be architectural decisions, patterns, and others.
