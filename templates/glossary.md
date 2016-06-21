Glossary {#glossary}
--------

|               |                                     |
|---------------|-------------------------------------|
| Project terms | [Standard terms](glossary-std.html) |

**Process impact:** This file as a dictionary of terms defined as they
are used during the project. Writing out the definitions of terms and
acronyms here helps keep other documents more concise and precise. A
shared glossary helps prevent misunderstandings and makes it easier for
new team members to be productive.

Jump to: [A](#A) | [B](#B) | [C](#C) | [D](#D) | [E](#E) | [F](#F) |
[G](#G) | [H](#H) | [I](#I) | [J](#J) | [K](#K) | [L](#L) | [M](#M) |
[N](#N) | [O](#O) | [P](#P) | [Q](#Q) | [R](#R) | [S](#S) | [T](#T) |
[U](#U) | [V](#V) | [W](#W) | [X](#X) | [Y](#Y) | [Z](#Z) |
[Other](#Other)

### Project-specific Terms {#project-specific-terms}

TIPs:
-   Define HTML anchors on your terms with id="TERMNAME" so that other
    documents can link to the definition of specific terms.
-   If there is any question about the meaning of a term, note it here.
    If someone (e.g., the customer) gave you a definition to use, note
    that here too. If something is best defined by using a hyperlink to
    another document or website, include a hyperlink in the definition.
-   If a term was used in the past, but is no longer going to be used,
    you should keep it in the list, mark it as "deprecated", and link to
    the term or terms that replace it. E.g., deprecated standard term
    [bug](glossary-std.html#bug).
-   Define only project-specific terms, or ones that a new team member
    would not know. Don't define standard textbook terms that can be
    easily found elsewhere.
-   This glossary can serve as simple domain model or data dictionary.
    You can define important data objects by describing their meaning
    and key attributes. For example, see [student](#student) and
    [GPA](#gpa).

Class standing
:   Computed attribute of [student](#student) based on number of
    academic units completed. Used to determine priority in
    course enrollment.
:   Real-world meaning of values:
    |           |                               |
    |-----------|-------------------------------|
    | Freshman  | Less than 90 units            |
    | Sophomore | Between 90 and 180 units      |
    | Junior    | Between 180 and 270 units     |
    | Senior    | More than 270 units completed |

GEF
:   *n.* The [Graph Editing Framework](http://gef.tigris.org/). An open
    source library for editing diagrams (boxes and arrows).

GPA
:   *n.* Grade Point Average. GPA is a float between 0.00 and 4.00,
    accurate to 2 decimal places. Computed from average of completed
    course grades in transcript weighted by course units. Used to
    determine student ranking, and to trigger Dean's List and
    academic probation.

ICS
:   *n.* Acronym for the [School of Information and Computer
    Science](http://www.ics.uci.edu/) at [UC
    Irvine](http://www.uci.edu/).

Student
:   *n.* A person who attends a school to earn a degree. Persistent
    attributes include: student\_id\_number (primary key), GPA, major,
    and years\_at\_school.

Senior
:   *n.* A senior is special type of [undergraduate](#undergraduate) who
    has a certain number of course credits on his or her transcript.
    Years\_at\_school does not determine senior standing. TODO: how many
    credits needed?

Term1
:   Definition1

Term2
:   Definition2a
:   Definition2b

Term3
:   Definition3

Term4
:   Definition4

Term5
:   Definition5

Term6
:   Definition6

Undergraduate
:   A type of [student](#student). TODO: add more detail.

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/glossary.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional project glossary
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


