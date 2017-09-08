# Architectural Decision Records

An [Architectural Decision (AD)](https://en.wikipedia.org/wiki/Architectural_decision) is a software design choice that addresses a functional or non-functional requirement that is architecturally significant. 
An [architecturally significant requirement (ASR)](https://en.wikipedia.org/wiki/Architecturally_significant_requirements) is a requirement that has a measurable effect on a software system’s architecture and quality. 
An Architectural Decision Record (ADR) captures a single AD, such as often done when writing personal notes or meeting minutes.
All these are within the topic of Architectural Knowledge Management (AKM). Note: this short intro to ADRs is based on information in [this repo](https://github.com/joelparkerhenderson/architecture_decision_record/blob/01cc3c801b1cc61f82391a0a08986e4145e21c56/README.md)

The aim of the [GitHub adr organization](http://github.com/adr) is to
(i) strenghten the tooling around ADRs and to
(ii) provide provide pointers to public knowledge in the context of ADRs.

We currently focus on the [Sustainable Architectural Decisions](https://www.infoq.com/articles/sustainable-architectural-design-decisions) by Zdun et al., but are open to other formats of ADRs as shown at <https://github.com/joelparkerhenderson/architecture_decision_record>.

We offer one tool for sustainable ADs: [Embedded Architectural Decisions](https://github.com/adr/embedded-adl), which shows how ADRs can be embedded in Java Code.

## Related Projects

- Existing ADR templates 
  - Overview: [Architectural Decision Records](https://github.com/joelparkerhenderson/architecture_decision_record)
  - [Sustainable Architectural Decisions](https://www.infoq.com/articles/sustainable-architectural-design-decisions)
  - Comparison of seven templates: Zimmermann et al.: [Architectural Decision Guidance Across Projects - Problem Space Modeling, Decision Backlog Management and Cloud Computing Knowledge](http://www.ifs.hsr.ch/fileadmin/user_upload/customers/ifs.hsr.ch/Home/projekte/ADMentor-WICSA2015ubmissionv11nc.pdf). WICSA 2015: 85-94. 
  - [DecisionCapture](https://github.com/schubmat/DecisionCapture) - Templates for agile projects. [example](https://github.com/schubmat/DecisionCapture/blob/master/samples/samples_simpleTemplate_secondSprint.md).

- Tooling
  - [ADMentor] - Architectural Decision Modeling Add-In for [Sparx Enterprise Architect](https://www.sparxsystems.de/uml/neweditions/)
  - [adr-tools](https://github.com/npryce/adr-tools) - bash scripts to manage ADRs in the [Nygard format](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
  [example](https://github.com/npryce/adr-tools/blob/master/doc/adr/0002-implement-as-shell-scripts.md).
  - [ArchUnit](https://github.com/TNG/ArchUnit) - unit tests for architecture

  [ADMentor]: https://www.ifs.hsr.ch/index.php?id=13201&L=4
