## What is a HIP?
HIP stands for Hashgraph Improvement Proposal. The purpose is to provide information about Hashgraph to the Hashgraph community. The HIP author is responsible for building consensus within the community and documenting dissenting opinions.

## HIP Purpose
The goal of HIPs is to have a place to propose new features, a way to collect community thoughts and input on a particular issue and also to document all these Hashgraph subject matters in one place. It's a great way to document this discussion here on GitHub because any revisions made on these text files will be recorded. 

HIP is a convenient way for Hashgraph implementers to keep track of their process. While implementing, they will be able to list the HIPs that they are working on or which one they have already implemented. Therefore, this will be an easy way for end users to know the current status of any proposals.

## HIP Types
There are three types of HIP:
- **A Standard HIP** - describes any changes that affect most or all Hashgraph implementations, this can be a change to the network protocol, a transaction validity rules, proposed application standards/conventions, or any changes or addition that affects the interoperability of applications using Hashgraph. Standards HIPs consist of three parts, a design document, implementation, and an update to the formal specification (if warranted). Furthermore, Standard HIPs can be broken down into the following categories:
   - **Core:** This includes improvements requiring a consensus fork or as well as changes that are not necessarily consensus critical but may be relevant to core development discussions.
   - **Networking:** This includes improvements around proposed improvements to network protocol specifications.
   - **Interface:** This includes improvements around client API/RPC specifications and standards, and also certain language-level standards.
   - **HRC:**  Hedera Request For Comment. This includes application-level standards and conventions, including contract standards such as token standards, name registries, etc.

- **An Informational HIP** - describes an Hashgraph design issue, or provides general guidelines or information to the Hashgraph community, but does not propose a new feature. Informational HIPs do not necessarily represent Hashgraph community consensus or recommendation, so users and implementers are free to ignore Informational HIPs.

- **A Meta HIP** - describes a process surrounding Hashgraph or proposes a change to (or an event in) a process. Process HIPs are like Standards HIPs but apply to areas other than the Hashgraph protocol itself. They may propose an implementation, but not to Hashgraph's codebase; they often require community consensus; unlike Informational HIPs, they are more than recommendations, and users are typically not free to ignore them. Examples include procedures, guidelines, changes to the decision-making process, and changes to the tools or environment used in Hashgraph development. Any meta-HIP is also considered a Process HIP.

Each HIPs should only be one single key proposal and/or idea. The idea should be focused and only issue to one subject matter to be successful. If an issue only affects one client, it does not need a HIP. While changes that affect multiple clients, or defines a standard for multiple apps to use, it does require a HIP.

A HIP must meet certain minimum criteria. It must be clear and have a complete description of the proposed enhancement. The enhancement must represent a net improvement. The proposed implementation, if applicable, must be solid and must not complicate the protocol unduly.

## HIP Work Flow
Parties involved in this process are you, the HIP author, the HIP editors, and the Hashgraph Developers.

Evaluate your idea: Before you begin, ask the Hashgraph community first if your idea is original to save time. Make sure the idea is applicable to the entire community and not to one particular author. While it may be a good idea for an author it may not be the case for all areas of the Hashgraph community. An excellent place to discuss your proposal is here in the Issues section of this repository. You can start creating a more formalized language around your HIP.

Your role as the author is to write the HIP using the style and format described below, guide the discussions in the appropriate forums, and build community consensus around the idea. Following is the process that a successful EIP will move along:
[ WIP ] -> [ DRAFT ] -> [ LAST CALL ] -> [ ACCEPTED ] -> [ FINAL ]

The status change of each HIP is requested by the HIP author and it is to be reviewed by the HIP editors. To update the status, use a pull request. For convince, include a link for people to continue discussing your HIP. HIP editors should follow the following guidelines when reviewing requests:
- Active: 
- Work in Progress (WIP):
- Draft: 
- Last Call: 
- Accepted: 
- Final: 

Exceptional statuses:
- Deferred: A core HIPs that have been put off for a future hard fork. 
- Rejected: An HIP that is fundamentally broken or a core HIP that was rejected by the Core Devs.
- Superseded: An HIP which was previously final but is no longer considered state-of-the-art.

## Successful HIP Guidelines
For a successful HIP include the following: 
- Preamble: Provide the HIP number, a short descriptive title, and the author details
- Simple Summary: Provide a simplified and in layman terms of an explanation of the HIP.
- Abstract:  Provide a short description of the technical issue being addressed.
- Motivation (*optional): Provide motivation for HIPs that want to change the Hashgraph protocol. It should clearly explain why the existing protocol specification is inadequate to address the problem that the HIP solves.
- Specification: Provide a technical specification that describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing, interoperable implementations for any of the current Hashgraph platforms 
- Rationale: Provide a rationale describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and any related work. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.
- Backwards Compatibility: All HIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The HIP must explain how the author proposes to deal with these incompatibilities.
- Test Cases: Provide test cases for an implementation for HIPs that are affecting consensus change. 
- Implementations: Provide links to implementations. This must be completed before any HIP is given status “Final”. 
- Copyright Waiver: All HIPs must be in the public domain.
