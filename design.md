Design {#design}
------

### Release Information {#release-information}

Project:
:   [PROJECTNAME](index) 
  
Internal Release Number: 
:   X.Y.Z 
  
Attached Worksheets:</th> 
:    Design &gt; [Architecture Worksheet](design-architecture)
:    Design &gt; [Source Organization and Build Worksheet](design-src-org)
<!-- :    Design &gt; [Scalability Worksheet](design-scalability) -->
:    Design &gt; [User Interface Worksheet](design-ui)
:    Design &gt; [Persistent Storage Worksheet](design-persistence)
:    Design &gt; [Security Worksheet](design-security)

Related Documents:
:    [SRS](srs) &gt; [Use case suite](use-case-suite)
:    [SRS](srs) &gt; [Feature set](feature-set)
:    [Glossary](glossary)
:    LINKS TO RELEVANT STANDARDS
:    LINKS TO OTHER DOCUMENTS

**Process impact:** This design document describes a system that will
satisfy the requirements of the [SRS](srs). Decisions made in
creating this design document are based on those requirements and an
understanding of available technologies and components. Once the design
has been drafted, work on the system implementation and unit testing may
begin.

TODO: Fill in the sections below. Add ore remove items as needed for
your project.

### Introduction {#introduction}

How is this design document organized?
:   This main page describes the system design in terms of packages,
    classes, relationships, and behavior. Several attached worksheets
    address specific aspects of the overall system design, such as user
    interface and database design.

What are the most important facts that a developer should know about this design?
:   PARAGRAPH or BULLETS

What are the prioritized goals of this design?

:   1.  [Correctness](glossary-std#dg_correctness){.def}
    2.  [Feasibility](glossary-std#dg_feasibility){.def}
    3.  [Understandability](glossary-std#dg_understandability){.def}
    4.  [Implementation phase
        guidance](glossary-std#dg_guidance){.def}
    5.  [Modularity](glossary-std#dg_modularity){.def}
    6.  [Extensibility](glossary-std#dg_extensibility){.def}
    7.  [Testability](glossary-std#dg_testability){.def}
    8.  [Efficiency](glossary-std#dg_efficiency){.def}

### UML Structural Design {#uml-structural-design}

TODO: Link to a design model and/or design diagrams that describe your
system's structure in detail.

The system's structural design is described in the following UML model:
[MODELNAME](LINK-TO-MODEL-FILE).

The system's structural design is described in the following UML
structural diagrams:

-   [PACKAGE OVERVIEW DIAGRAM](LINK-TO-DIAGRAM)
-   PACKAGENAME
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)
-   PACKAGENAME
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)
-   PACKAGENAME
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)

ANY ADDITIONAL NOTES OR COMMENTS

### UML Behavioral Design {#uml-behavioral-design}

TODO: Link to a design model and/or design diagrams that describe your
system's behavior in detail.

The system's behavioral design is described in the following UML model:
[MODELNAME](LINK-TO-MODEL-FILE).

The system's behavioral design is described in the following UML
behavioral diagrams:

-   State Diagrams
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)
-   Sequence Diagrams
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)
-   Collaboration Diagrams
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)
    -   [DIAGRAMNAME](LINK-TO-DIAGRAM)

ANY ADDITIONAL NOTES OR COMMENTS

### UML Design Checklist {#uml-design-checklist}

TODO: Answer the following questions to help evaluate your design. Add
or remove questions to fit your project. If you cannot answer a question
positively, that may indicate an aspect of the design that should be
revised.

Correctness: How do you know that this design is correct?
:   2-4 SENTENCES

Feasibility: What indicates that this design can be implemented and tested with the planned amount of time and effort?
:   2-4 SENTENCES

Understandability: What makes this design understandable? 
:   2-4 SENTENCES

Implementation phase guidance: Does the design suggest reasonable implementation tasks?
:   2-4 SENTENCES

Modularity: How have concerns been separated and addressed in distinct modules?
:   2-4 SENTENCES

Extensibility: How can new features can be easily added later?
:   2-4 SENTENCES

Testability: What makes this system easy to test?
:   2-4 SENTENCES

Efficiency: Does the system consume an acceptable amount of time, storage space, bandwidth, and other resources?
:   2-4 SENTENCES

Has the design been communicated to the development team and other stakeholders?
:   Yes, everyone understands. Feedback is welcome.
:   No, this is a risk that is noted in the [Risk
    Management](plan#risks) section.

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/design.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional design
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


