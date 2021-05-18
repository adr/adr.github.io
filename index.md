# Architectural Decision Records

An [Architectural Decision (AD)](https://en.wikipedia.org/wiki/Architectural_decision) is a software design choice that addresses a functional or non-functional requirement that is architecturally significant.
An [Architecturally Significant Requirement (ASR)](https://en.wikipedia.org/wiki/Architecturally_significant_requirements) is a requirement that has a measurable effect on a software system’s architecture and quality.
An *Architectural Decision Record (ADR)* captures a single AD, such as often done when writing personal notes or meeting minutes; the collection of ADRs created and maintained in a project constitute its *decision log*.
All these are within the topic of Architectural Knowledge Management (AKM).

The aim of the [GitHub adr organization](http://github.com/adr) is to:

1. Motivate the need for and benefits of AD capturing and establish a common vocabulary
2. Strengthen the tooling around ADRs, in support of agile practices as well as iterative and incremental software engineering processes
3. Provide pointers to public knowledge in the context of AKM and ADRs (for instance, [this website](https://www.ifs.hsr.ch/index.php?id=13201&L=4))

> Note: The term "architecture decision record" can be used interchangeably.

## ADRs in the media

* (German) [Gut dokumentiert: Architecture Decision Records](https://www.heise.de/hintergrund/Gut-dokumentiert-Architecture-Decision-Records-4664988.html) by [@obfischer](https://github.com/obfischer) published at [heise online](https://www.heise.de/).

{: .long}
## Lightweight Architectural Decision Records Should be Adopted

[ThoughtWorks](https://www.thoughtworks.com/) lists architectural decision records as "adopt" at their [technology radar vol. 18](https://assets.thoughtworks.com/assets/technology-radar-vol-18-en.pdf).
[It is still listed as "adopt"](https://www.thoughtworks.com/de/radar/techniques/lightweight-architecture-decision-records).

A "lightweight" ADR consists of [title, status, context, decision, and consequences](https://github.com/joelparkerhenderson/architecture_decision_record/blob/master/adr_template_by_michael_nygard.md) (according to [@mtnygard](https://github.com/mtnygard)). 
<!-- [W] changed, certainly not the first, as my "History" section shows: https://www.ozimmer.ch/practices/2020/04/27/ArchitectureDecisionMaking.html -->

We think that the considered options are crucial to understand the reason of a chosen option. Thus, we propose [MADR](https://adr.github.io/madr/) --- The Markdown Architecture Decision Records (MADR: `[ˈmæɾɚ]`) as alternative in this ADR organization.

## Relation of ADRs, MADR, and Others

![ADR](ADR.png)

## Sustainable Architectural Decisions

We base our work on the guidelines and principles in [Sustainable Architectural Decisions](https://www.infoq.com/articles/sustainable-architectural-design-decisions) by Zdun et al., for instance the Y-statement format suggested in that article.

However, we are open to other formats of ADRs as shown at [@joelparkerhenderson's repository](https://github.com/joelparkerhenderson/architecture_decision_record).

In short, the Y-statement is as follows:

> In the context of `<use case/user story u>`, facing `<concern c>` we decided for `<option o>` to achieve `<quality q>`, accepting `<downside d>`.

The long form of it is as follows (extra section "because"):

> In the context of `<use case/user story u>`,
> facing `<concern c>`
> we decided for `<option o>`
> and neglected `<other options>`,
> to achieve `<system qualities/desired consequences>`,
> accepting `<downside d/undesired consequences>`,
> because `<additional rationale>`.

You can find more explanations and examples on Medium [Y-Statements --- A Light Template for Architectural Decision Capturing](https://medium.com/@docsoc/y-statements-10eb07b5a177). 

[A Definition of Done for Architectural Decision Making](https://www.ozimmer.ch/practices/2020/05/22/ADDefinitionOfDone.html) proposes five criteria and a checklist to decide when it is time to set the status of a single decision to "done": evidence, criteria and alternatives, agreement, documentation, and realization/review plan. Here, we focus on the 'D' in *ecADR*.


## Offered Projects

- [MADR](https://adr.github.io/madr/): The Markdown Architecture Decision Records (MADR: `[ˈmæɾɚ]`). Lean ADRs to quickly document architectural decisions in code. - Slogan: architectural decisions that [matter `[ˈmæɾɚ]`](https://en.wiktionary.org/wiki/matter#Pronunciation).
- [adr-log](https://adr.github.io/adr-log/): Generates a architectural decision log out of MADRs.
- [Embedded Architectural Decision Records](https://adr.github.io/e-adr/), which shows how a distributed AD log can be embedded in Java Code via ADR annotations.
- [eadlsync](https://adr.github.io/eadlsync/): Synchronizes embedded architectural decision records with a repository of architectural decisions.
- [SE Repo](https://github.com/adr/serepo): Software Engineering Repository. A repository for versioning software engineering artifacts, which can be architectural decisions, patterns, and others.

## Related Projects

### Existing ADR Templates

- Overview: [Architectural Decision Records](https://github.com/joelparkerhenderson/architecture_decision_record): collection of markdown templates converted to Markdown
- Comparison of seven templates: Zimmermann et al.: [Architectural Decision Guidance Across Projects - Problem Space Modeling, Decision Backlog Management and Cloud Computing Knowledge](http://www.ifs.hsr.ch/fileadmin/user_upload/customers/ifs.hsr.ch/Home/projekte/ADMentor-WICSA2015ubmissionv11nc.pdf). WICSA 2015: 85-94. 
- Context, background and examples of good and bad justifications can be found in [this blog post](https://www.ozimmer.ch/practices/2020/04/27/ArchitectureDecisionMaking.html). 
- [DecisionCapture](https://schubmat.github.io/DecisionCapture/): Templates for agile projects and explanation of the ADR universe. [example](https://github.com/schubmat/DecisionCapture/blob/master/samples/samples_simpleTemplate_secondSprint.md).


### Tooling

- [ADMentor](https://github.com/IFS-HSR/ADMentor) Architectural Decision Modeling Add-In for [Sparx Enterprise Architect](https://www.sparxsystems.de/uml/neweditions/)
- [adr-tools](https://github.com/npryce/adr-tools) - bash scripts to manage ADRs in the [Nygard format](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions.html).
[example](https://github.com/npryce/adr-tools/blob/master/doc/adr/0002-implement-as-shell-scripts.md).
- Java rewrite: [adr-j](https://github.com/adoble/adr-j)
- C# rewrite: [adr-cli](https://github.com/GingerTommy/adr-cli)
- Go rewrite: [adr](https://github.com/marouni/adr)
- Node.js rewrite: [adr](https://github.com/phodal/adr)
- Ansible script to install adr-tools: [ansible-adr-tools](https://github.com/escalate/ansible-adr-tools)
- `adr-tools` based tools: other tools to manage ADRs (with a different syntax)
- PHP version: [phpadr](https://github.com/globtec/phpadr)
- A Powershell module: [adr-ps](https://github.com/rdagumampan/adr-ps)
- Another Powershell module: [ArchitectureDecisionRecords](https://github.com/ajoberstar/ArchitectureDecisionRecords)
- [adr-viewer](https://github.com/mrwilson/adr-viewer) - python application to generate a website from a set of ADRs.
- [ArchUnit](https://github.com/TNG/ArchUnit); unit tests for architecture
- [docToolchain](https://doctoolchain.github.io/docToolchain/): docToolchain is an implementation of the [docs-as-code](http://www.writethedocs.org/guide/docs-as-code/) approach for software architecture plus some additional automation.
- [Structurizr](https://www.structurizr.com/): Structurizr is a collection of tooling to help you visualise, document and explore your software architecture using the [C4 model](https://c4model.com/).
- [Log4brains](https://github.com/thomvaill/log4brains): CLI and web UI to log and publish your ADRs as a static website


### More Related Work

- [Documenting Architecture Decisions by Michael Nygard](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions.html)
- [Architectural Knowledge Management (AKM) overview by HSR FHO](https://www.ifs.hsr.ch/index.php?id=13191&L=4)
- [Sustainable Architectural Decisions](https://www.infoq.com/articles/sustainable-architectural-design-decisions)
- [Overview on all variants of ADRs](https://github.com/joelparkerhenderson/architecture_decision_record#sources)
- [Method Selection and Tailoring](https://www.ifs.hsr.ch/Method-Selection-and-Tailoring.13195.0.html?&L=4)
- [Work by Daniel Popescu](https://scholar.google.com/citations?user=dASv28sAAAAJ)
- [Architecture Decision Records in Action by Michael Keeling (IBM Watson Group) and Joe Runde (IBM)](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=497744) - presentation including empirical numbers.
- [Documenting Architecture Decisions](https://www.fabian-keller.de/blog/documenting-architecture-decisions) - Blog entry by Fabian Keller
