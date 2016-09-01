[SRS](srs) &gt; [Feature Set](feature-set) &gt; Feature Specification Format {#srs-feature-set-feature-specification-format}
--------------------------------------------------------------------------------------

**Process impact:** This reference page documents the format of feature
descriptions and gives tips on writing them. You can copy and paste the
feature specification template into your [Features](features)
document. This file itself should not be edited to hold specific
features.

TODO: Copy and paste this feature specification template as many times
as needed in your [Features](features) document.

### F-00: FEATURE NAME {#f-00-feature-name}

Priority:
:   Essential | Expected | Desired | Optional

Effort:
:   Months | Weeks | Days | Hours

Risk:
:   Dangerous | 3-Risk | 2-Risk | 1-Risk | Safe

Functional area(s):
:   WORD, WORD, WORD

Use case(s):
:   [UC-01](use-cases#UC-01)

Description:
:   1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:   Precise Details:
    
    - LOGICAL CONSTRAINT  
    - LOGICAL CONSTRAINT

Notes and Questions:
:   

    - NOTE
    - NOTE
    - QUESTION
    - QUESTION

### Feature Attribute Values {#feature-attribute-values}

-   Priority
    -   Essential: The system could not or would never be used without
        this feature. It would be much harder to test, document, or
        package the product without this feature.
    -   Expected: Key stakeholders strongly desire and expect
        this feature. It may have been promised to them in a certain
        release. It's absence would substantially reduce the success of
        the project.
    -   Desired: Stakeholders desire this feature. It's absence would
        reduce the success of the project.
    -   Optional: This feature would be nice to have. Adding it could
        have some advantage, but delaying it would not have a big effect
        on the success of the project.
-   Effort
    -   Months: A very large feature that is too big to estimate and
        should be broken in to smaller, better-defined features.
    -   Weeks: A large feature that will take 40 to 160 hours to add.
    -   Days: An average or easy feature that would take less than 40
        hours to add.
    -   Hours: A very easy feature that would take less than 8 hours to
        add
    -   Note that "adding" a feature means doing all of it's design,
        implementation, technical documentation, user documentation,
        and testing. Even the easiest feature takes hours to add.
-   Risk
    -   Dangerous: Implementing this feature successfully would require
        overcoming risk factors that are more than three or unknown
        in number. It should be broken down into parts, better
        specified, or risk factors should be eliminated prior
        to implementation.
    -   3-Risks: Implementing this feature would require three risk
        factors to be overcome. Any single release should contain at
        most a few such high-risk features, and contingency plans should
        be considered. You should be able to list the risks.
    -   2-Risks: Implementing this feature would require two risk
        factors to be overcome. This is normal for challenging features.
        You should be able to list the risks.
    -   1-Risk: Implementing this feature as specified would require one
        risk factor to be overcome. This is normal for many features.
        You should be able to describe the risk.
    -   Safe: Implementing this feature as specified is just a matter of
        time and effort, there is no real risk of failure.
    -   A "risk factor" is a task or fact that is currently in doubt,
        but that must turn out well in order for the feature to be
        successfully implemented. See tips on managing risk below.

### Further Information {#further-information}

For more information on advice, see:

-   Words of wisdom on [feature
    sets](http://readyset.tigris.org/words-of-wisdom/feature-set.html).
-   Words of wisdom on [feature
    specifications](http://readyset.tigris.org/words-of-wisdom/features.html).

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


