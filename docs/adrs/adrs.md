---
title: Architectural Decision Records
permalink: /adrs

layout: post
sidenav: docs
permalink: /adrs
subnav: 
  - text: 2020-03-12-ARCH-record-architecture-decisions-simple-template
    href: /adrs/2020-03-12-ARCH-record-architecture-decisions-simple-template
  - text: 2020-03-14-ARCH-record-architecture-decisions-detailed-template
    href: /adrs/2020-03-14-ARCH-record-architecture-decisions-detailed-template
  - text: 2020-03-15-ARCH-GPU-on-GTS
    href: /adrs/2020-03-15-ARCH-GPU-on-GTS
  - text: 2020-04-16-ARCH-liferay-community-edition
    href: /adrs/2020-04-16-ARCH-liferay-community-edition

---
An architecture decision record (ADR) is a document that captures an important architectural decision made along with its context and consequences. An architecture decision (AD) is a software design choice that addresses a significant requirement.

The aim of this page is to:

1. Motivate the need for and benefits of Architectural Decision Record (ADR) capturing and establish a common vocabulary.
2. Strengthen the tooling around ADRs, in support of agile practices as well as iterative and incremental software engineering processes.
3. Provide pointers to public knowledge in the context of Architecture Decision Records (ADRs) (for instance, this website)
4. Provide a templated way to allow BCGOV Natural Resource development teams, to document critical design decisions that facilitiates and supports broader communication and collaboration on lessons learned.

### Guidance

When is an ADR needed?
1. When something is hard to undo. 
2. When it is important to communicate/justify and document to others
3. Document Initialize architecture choices
4. Significant changes to architecture
5. interim architectures that are required to get to something preferred down the road
6. emerging patterns and technologies that a team wants to investigate
7. something that challenges existing architectural principles

Where are the ADRs stored?
1. Owned by the project/product architecture owner 
2. within the project code repository ADRs should be stored in the docs/adrs subdirectory (to be curated/discoverable by a broader audience)
3. ADRs with the docs/adrs subdirectory within GitHub BCGOV repos will be currated and referenced in this repository
4. for non-agile teams, ADRs will be stored here. 


NOTE: This page uses a Jeykll template. Jekyll is a static site generator. You give it text written in your favorite markup language and it uses layouts to create a static website dynamically after each git respository commit. This repo is intended as a curation as well as a template for teams to re-use.

[Back to the Top](#)

