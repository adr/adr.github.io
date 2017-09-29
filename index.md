# Architectural Decision Records

An [Architectural Decision (AD)](https://en.wikipedia.org/wiki/Architectural_decision) is a software design choice that addresses a functional or non-functional requirement that is architecturally significant. 
An [Architecturally Significant Requirement (ASR)](https://en.wikipedia.org/wiki/Architecturally_significant_requirements) is a requirement that has a measurable effect on a software system’s architecture and quality. 
An *Architectural Decision Record (ADR)* captures a single AD, such as often done when writing personal notes or meeting minutes; the collection of ADRs created and maintained in a project constitute its *decision log*.
All these are within the topic of Architectural Knowledge Management (AKM).
Note: this short intro to ADRs is based on information in [Joel Parkerhenderson's GitHub repo](https://github.com/joelparkerhenderson/architecture_decision_record/blob/01cc3c801b1cc61f82391a0a08986e4145e21c56/README.md).

The aim of the [GitHub adr organization](http://github.com/adr) is to:

1. Motivate the need for and benefits of AD capturing and establish a common vocabulary 
2. Strengthen the tooling around ADRs, in support of agile practices as well as iterative and incremental software engineering processes
3. Provide pointers to public knowledge in the context of AKM and ADRs (for instance, [this website](https://www.ifs.hsr.ch/index.php?id=13201&L=4))


## Sustainable Architectural Decisions

We base our work on the guidelines and principles in [Sustainable Architectural Decisions](https://www.infoq.com/articles/sustainable-architectural-design-decisions) by Zdun et al., for instance the Y-statement format suggested in that article.
However, we are open to other formats of ADRs as shown at <https://github.com/joelparkerhenderson/architecture_decision_record>.

In short, that Y-statement is as follows:

> In the context of `<use case/user story u>`, facing `<concern c>` we decided for `<option o>` to achieve `<quality q>`, accepting `<downside d>`.

The long form of it is as follows:

> In the context of `<use case/user story u>`,
> facing `<concern c>`
> we decided for `<option o>`
> and neglected `<other options>`,
> to achieve `<system qualities/desired consequences>`,
> accepting `<downside d/undesired consequences>`,
> because `<additional rationale>`.


## Offered Projects

- [MADR](https://github.com/adr/madr) - The Markdown Architecture Decision Records (MADR: `[ˈmæɾɚ]`). Lean ADRs to quickly document architectural decisions in code. - Slogan: architectural decisions that [matter `[ˈmæɾɚ]`](https://en.wiktionary.org/wiki/matter#Pronunciation).
- [Embedded Architectural Decision Records](https://github.com/adr/e-adr), which shows how a distributed AD log can be embedded in Java Code via ADR annotations.
- [eadlsync](https://github.com/adr/eadlsync) - Synchronizes embedded architectural decision records with a repository of architectural decitions.


## Relation of ADRs, MADR, and others

![ADR](ADR.png)


## Related Projects

- Existing ADR templates 
  - Overview: [Architectural Decision Records](https://github.com/joelparkerhenderson/architecture_decision_record) - collection of markdown templates converted to markdown
  - [Sustainable Architectural Decisions](https://www.infoq.com/articles/sustainable-architectural-design-decisions)
  - Comparison of seven templates: Zimmermann et al.: [Architectural Decision Guidance Across Projects - Problem Space Modeling, Decision Backlog Management and Cloud Computing Knowledge](http://www.ifs.hsr.ch/fileadmin/user_upload/customers/ifs.hsr.ch/Home/projekte/ADMentor-WICSA2015ubmissionv11nc.pdf). WICSA 2015: 85-94. 
  - [DecisionCapture](https://github.com/schubmat/DecisionCapture) - Templates for agile projects. [example](https://github.com/schubmat/DecisionCapture/blob/master/samples/samples_simpleTemplate_secondSprint.md).

- Tooling
  - [ADMentor](https://github.com/IFS-HSR/ADMentor) Architectural Decision Modeling Add-In for [Sparx Enterprise Architect](https://www.sparxsystems.de/uml/neweditions/)
  - [adr-tools](https://github.com/npryce/adr-tools) - bash scripts to manage ADRs in the [Nygard format](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
  [example](https://github.com/npryce/adr-tools/blob/master/doc/adr/0002-implement-as-shell-scripts.md).
  - [ArchUnit](https://github.com/TNG/ArchUnit) - unit tests for architecture

- More related work:
  - <https://github.com/joelparkerhenderson/architecture_decision_record#sources>
  - [Method Selection and Tailoring](https://www.ifs.hsr.ch/Method-Selection-and-Tailoring.13195.0.html?&L=4)
