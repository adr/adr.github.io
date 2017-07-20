# Architectural Decision Records

An architectural decision (AD) is a software design choice that addresses a significant requirement.
An architectural decision record (ADR) is a way to track an AD, such as by writing notes, or logging information.
An architecturally significant requirement (ASR) is a requirement that has a measurable effect on a software system’s architecture.
All these are within the topic of architectural knowledge management (AKM). [source](https://github.com/joelparkerhenderson/architecture_decision_record/blob/01cc3c801b1cc61f82391a0a08986e4145e21c56/README.md)

The aim of the [GitHub adr organization](http://github.com/adr) is to
(i) strenghten the tooling around ADRs and to
(ii) provide provide pointers to all avaiable public knowledge in the context of ADRs.

We currently focus on the [Sustainable Architectural Decisions](https://www.infoq.com/articles/sustainable-architectural-design-decisions) by Zdun et al., but are open to other formats of ADRs as shown at <https://github.com/joelparkerhenderson/architecture_decision_record>.

We offer one tool for sustainable ADs: [Embedded Architectural Decisions](https://github.com/adr/embedded-adl), which shows how ADRs can be embedded in Java Code.

## Related Projects

- Existing Architectural Decision Records
  - Overview: [Architectural Decision Records](https://github.com/joelparkerhenderson/architecture_decision_record)
  - Overview: Zimmermann et al.: Architectural Decision Guidance Across Projects - Problem Space Modeling, Decision Backlog Management and Cloud Computing Knowledge. WICSA 2015: 85-94.
    Author's copy available at [ADMentor].
  - [DecisionCapture](https://github.com/schubmat/DecisionCapture) - Templates for agile projects. [example](https://github.com/schubmat/DecisionCapture/blob/master/samples/samples_simpleTemplate_secondSprint.md).
  - [Sustainable Architectural Decisions](https://www.infoq.com/articles/sustainable-architectural-design-decisions)
- Tooling
  - [ADMentor] - Architectural Decision Modeling Add-In for [Sparx Enterprise Architect](https://www.sparxsystems.de/uml/neweditions/)
  - [adr-tools](https://github.com/npryce/adr-tools) - bash scripts to manage ADRs in the [Nygard format](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
  [example](https://github.com/npryce/adr-tools/blob/master/doc/adr/0002-implement-as-shell-scripts.md).
  - [ArchUnit](https://github.com/TNG/ArchUnit) - unit tests for architecture

  [ADMentor]: https://www.ifs.hsr.ch/index.php?id=13201&L=4
