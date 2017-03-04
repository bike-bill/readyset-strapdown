Legal Issues {#legal-issues}
------------

### Project Information {#project-information}


Project:
:	[PROJECTNAME](index)

Internal Release Number:
:	X.Y.Z

Release Audience:
:	General availability release ||
:	Customer-specific release: CUSTOMER(S) ||
:	Developer release (Internal usage only) ||
:	Early access release (Controlled external access)

Intended Product License:
:	Commercial license

Related Documents:
:	[Project proposal](proposal) &gt; [Target audience and benefits](target-and-benefits)
:	[Plan](plan) &gt; [Resource needs](resource-needs)
:	[Glossary](glossary)


**Process impact:** This document outlines legal issues that may affect
this release. Failure to carefully consider these issues may put the
development organization at risk for legal action.

TODO: Fill in the information above and below. Add or remove rows as
needed. Use the worksheet to help identify legal issues. Seek
professional counsel for review as needed.

### Ownership of Intellectual Property {#ownership-of-intellectual-property}

| Component                | Owner      | License            | Status                                      | Comments                                                     |
|--------------------------|------------|--------------------|---------------------------------------------|--------------------------------------------------------------|
| Product name             | Us         | Trademark          | Registration pending                        | We must use "(TM)", not "(R)"                                |
| Database                 | VENDOR     | Commercial license | In compliance, paid normal fee              | Limits us to 2 CPUs/server                                   |
| Encryption library       | VENDOR     | Commercial license | In compliance, signed partnership agreement |                                                              |
| Clip-art graphics        | None       | Public Domain      | In compliance                               |                                                              |
| Sound driver library     | OS Project | BSD                | In compliance                               |                                                              |
| Search engine indexer    | OS Project | GPL                | In compliance                               | Indexer runs in separate process, does not make our code GPL |
| Other library            | OS Project | BSD                | In compliance                               |                                                              |
| Other data               | Us         | Copyrighted        | In compliance                               |                                                              |
| Special algorithm patent | Us         | Patent pending     | In compliance                               | Patent search done, patent application submitted             |

### Regulatory Compliance {#regulatory-compliance}

| Type                   | Regulation                                      | Status        | Comments                                                |
|------------------------|-------------------------------------------------|---------------|---------------------------------------------------------|
| Export                 | Strong encryption exports must be declared      | In compliance | We will not distribute out of country                   |
| Privacy                | Cannot collect personal information from minors | In compliance | We ask for user age before asking for other information |
| Industry certification | Game industry rating                            | In compliance | We follow guidelines for "Everyone" rating              |

#### Possible Status Values {#possible-status-values}

-   In compliance: we are OK to go ahead with this release
-   Waived: we decided not to consider this aspect for this release
-   Violated: we are not conforming. Comment should describe impact.

### Legal Issues Checklist {#legal-issues-checklist}

The goal of this checklist is to help expose legal issues that might
otherwise be missed. It does not help with the actual management of
legal issues.

TODO: Answer the questions below. If multiple sample answers are
provided, delete the ones that do not apply. Edit any provided answers
as needed.

Does the development organization hold trademarks on the product name and any other names used in marketing the product?
:   Yes. Make sure to defend your ownership.
:   No. Make sure not to impinge on the trademarks of others.

Does the development organization hold or license patents on intellectual property that is used in the product?
:   Yes. Make sure to defend your ownership.
:   No. Make sure not to impinge on the patents of others.

Does the development organization hold or license copyrights on source code that is used in the product?
:   Yes. Make sure to defend your ownership.
:   No. Make sure not to impinge on the patents of others.

For each component in the product, is that component being used in a way that complies with its license?
:   Fill in details in table above.

For each piece of copyrighted data in the product, is that data being used in a way that complies with its license?
:   Fill in details in table above.

Was any component or data produced by another organization under contract?
:   Yes. Review the contract details for ownership and licensing.
:   No. No action required.

Does the product use technologies that are under export control?
:   Yes. But, we have no plans to export.
:   Yes. Take steps to obtain needed export permissions.
:   No. No action required.

Does the product need to meet industry-specific regulations?
:   Yes. Take steps to meet them. Specifically...
:   No. No action needed.

Does the product satisfy corporate policies (e.g., on privacy and security)?
:   Yes. Describe how each policy is satisfied..
:   No. Describe steps to bring the product into compliance.
:   No. No policies apply.

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/legal.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional legal issues
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


