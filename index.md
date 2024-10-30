---
layout: default
title: Architectural Decision Records (ADRs)
toc: true
---

## Motivation and Definitions

An [Architectural Decision (AD)](https://en.wikipedia.org/wiki/Architectural_decision) is a justified design choice that addresses a functional or non-functional requirement that is architecturally significant.
An [Architecturally Significant Requirement (ASR)](https://en.wikipedia.org/wiki/Architecturally_significant_requirements) is a requirement that has a measurable effect on the architecture and quality of a software and/or hardware system.
An *Architectural Decision Record (ADR)* captures a single AD and its rationale;
Put it simply, ADR can help you understand the reasons for a chosen architectural decision, along with its trade-offs and consequences.
The collection of ADRs created and maintained in a project constitute its *decision log*.
All these are within the topic of Architectural Knowledge Management (AKM), but ADR usage can be extended to design and other decisions ("any decision record").

The aim of the [GitHub adr organization](https://github.com/adr) is to:

1. Motivate the need for and benefits of AD capturing and establish a common vocabulary.
2. Strengthen the tooling around ADRs, in support of agile practices as well as iterative and incremental engineering processes.
3. Provide pointers to public knowledge in the context of AKM and ADRs.

## ADRs in the Media

- The [Azure Well-Architected Framework](https://learn.microsoft.com/en-us/azure/well-architected/architect-role/architecture-decision-record) features ADRs and this website (10/11/2024).
- [Love Unrequited: The Story of Architecture, Agile, and How Architecture Decision Records Brought Them Together](https://ieeexplore.ieee.org/document/9801811), Michael Keeling in the Pragmatic Designer column of IEEE Software Vol. 39 Issue 4 (2022) ([PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9801811))
- Architectural decision capturing is positioned as one of the essential activities in [Design Practice Reference](https://leanpub.com/dpr), a LeanPub e-Book.
- Chapter 3 of ["Patterns for API Design: Simplifying Integration with Loosely Coupled Message Exchanges"](https://api-patterns.org/book/) in the Addison Wesley Signature Series at Pearson features six narratives guiding through the conceptual level of API design: 29 recurring decisions with  options and criteria. Learn more in this [blog post](https://medium.com/nerd-for-tech/api-patterns-website-redesigned-and-sample-book-chapter-available-df9daf4b5e15).
- (in German) [Gut dokumentiert: Architecture Decision Records](https://www.heise.de/hintergrund/Gut-dokumentiert-Architecture-Decision-Records-4664988.html) by [@obfischer](https://github.com/obfischer) published at [heise online](https://www.heise.de/).

## Background Information

<!-- ## Sustainable Architectural Decisions -->
The work in the adr organization is based on the guidelines and principles in [Sustainable Architectural Decisions](https://www.infoq.com/articles/sustainable-architectural-design-decisions) by Zdun et al., for instance the Y-statement format suggested in that article.

More general background information and ADR guidance is available:

- A comparison of seven templates can be found in ["Architectural Decision Guidance Across Projects --- Problem Space Modeling, Decision Backlog Management and Cloud Computing Knowledge"](https://www.ost.ch/fileadmin/dateiliste/3_forschung_dienstleistung/institute/ifs/cloud-application-lab/admentor-wicsa2015ubmissionv11nc.pdf), a WICSA 2015 conference paper.
- [Architectural Decisions — The Making Of](https://www.ozimmer.ch/practices/2020/04/27/ArchitectureDecisionMaking.html) provides a history on architecture decision recording since the late 1990, as well as examples and guidance for providing decision rationale.
- [Documenting Architecture Decisions](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions.html) is the blog post from 2011 by Michael Nygard that popularized the concept.
- [Architectural Decision Records (ADR): Open & Transparent Decision History](https://openpracticelibrary.com/practice/architectural-decision-records-adr/) is a practice in the Open Practice Library.
- An AWS Prescriptive Guidance recommends [using architectural decision records to streamline technical decision-making for a software development project](https://docs.aws.amazon.com/prescriptive-guidance/latest/architectural-decision-records/welcome.html).
- [Architecture Decision Records in Action by Michael Keeling (IBM Watson Group) and Joe Runde (IBM) [YouTube]](https://www.youtube.com/watch?v=41NVge3_cYo) is a presentation that includes empirical numbers.
- [ADRs and Architecture Stories](https://www.developertoarchitect.com/lessons/lesson168.html) is part of a video series by Mark Richards explaining ADRs, starting from Nygard's template.
<!-- - [Work by Daniel Popescu](https://scholar.google.com/citations?user=dASv28sAAAAJ) -->
- Additional pointers and resources can be found on the web page [Architectural Knowledge Management (AKM)](https://www.ost.ch/en/research-and-consulting-services/computer-science/ifs-institute-for-software-new/cloud-application-lab/architectural-knowledge-management-akm).
