[SRS](srs) &gt; Use Case Suite {#srs-use-case-suite}
-----------------------------------

### Release Information {#release-information}

|Project:                            |PROJECTNAME     |
|:-----------------------------------|:-------------  |
| Internal Release Number:           | X.Y.Z          |
| Related Documents:                 |[Project proposal](proposal) > [User needs](user-needs), [SRS](srs) > [Feature set](feature-set), [Use case format](use-case-format), LINK TO USE CASE DIAGRAM, LINKS TO RELEVANT STANDARDS, LINKS TO OTHER DOCUMENTS      |

**Process impact:** A use case suite is simply a table of contents for
the individual use cases. Much like a test suite, organizing the suite
of use cases by priority, functional area, actor, business object, or
release can help identify parts of the system that need additional use
cases.

TODO: Before writing individual use cases, list the use cases that you
think you will need. Organize them in a way that will purposely leave
visible blanks on this page if you are missing use cases. E.g., see
"Scalability and availability". Choose one or more of the organizations
show below.

TIP: Refer back to the user stories in your [user
needs](user-needs) document. Use them for ideas and make sure that
you cover all of them. Remember that use cases are more precise than
user stories, and there may be several use cases for a given user story.

TIP: The use case suite can be organized into nested lists according to
other coverage criteria, e.g., by actor. Or, it can be organized into
tables that consider two aspects at a time, e.g., business objects vs.
actor. If a certain section of the tree or table does not need use
cases, explicitly mark it "N/A". Otherwise, mark it "TODO".

### Use Cases by Functional Area {#use-cases-by-functional-area}

-   User account management
    -   [UC-00](use-cases.html#UC-00) Configure the site
    -   [UC-01](use-cases.html#UC-01) Register as a new user
    -   [UC-02](use-cases.html#UC-02) Request new password
    -   [UC-03](use-cases.html#UC-03) Edit user profile
    -   [UC-04](use-cases.html#UC-04) View user profile
-   Course management
    -   [UC-10](use-cases.html#UC-10) Create course
    -   [UC-11](use-cases.html#UC-11) View catalog description
    -   [UC-31](use-cases.html#UC-31) Assign course to room
-   Course enrollment
    -   [UC-20](use-cases.html#UC-20) Enroll in course
    -   [UC-21](use-cases.html#UC-21) Drop course
-   Scalability and availability
    -   N/A: These features are completely automated and internal, users
        never interact with them
-   Facilities management
    -   [UC-30](use-cases.html#UC-30) View room description
    -   [UC-31](use-cases.html#UC-31) Assign course to room
-   Grading and transcripts
    -   TODO: need to write use cases here
-   FUNCTIONAL AREA SEVEN
    -   [UC-70](use-cases.html#UC-70) NAME OF USE CASE
    -   [UC-71](use-cases.html#UC-71) NAME OF USE CASE
-   FUNCTIONAL AREA EIGHT
    -   [UC-80](use-cases.html#UC-80) NAME OF USE CASE
    -   [UC-81](use-cases.html#UC-81) NAME OF USE CASE
-   FUNCTIONAL AREA NINE
    -   [UC-90](use-cases.html#UC-90) NAME OF USE CASE
    -   [UC-91](use-cases.html#UC-91) NAME OF USE CASE

### Use Cases by Stakeholder {#use-cases-by-stakeholder}

This information is shown in the [use case diagram](LINK-TO-DIAGRAM),
but it is shown here as a list or table so that missing use cases are
more noticeable.

-   All Stakeholders
    -   [UC-11](use-cases.html#UC-11) View catalog description
    -   [UC-30](use-cases.html#UC-30) View room description
-   Students
    -   [UC-01](use-cases.html#UC-01) Register as a new user
    -   [UC-02](use-cases.html#UC-02) Request new password
    -   [UC-03](use-cases.html#UC-03) Edit user profile
    -   [UC-20](use-cases.html#UC-20) Enroll in course
    -   [UC-21](use-cases.html#UC-21) Drop course
-   Instructors
    -   [UC-04](use-cases.html#UC-04) View user profile
-   Administrators
    -   [UC-00](use-cases.html#UC-00) Configure the site
    -   [UC-10](use-cases.html#UC-10) Create course
    -   [UC-31](use-cases.html#UC-31) Assign course to room
-   Executives
    -   N/A: this stakeholder never directly interacts with the system
-   Vendors
    -   TODO: need to write use cases here
-   STAKEHOLDER
    -   [UC-70](use-cases.html#UC-70) NAME OF USE CASE
    -   [UC-71](use-cases.html#UC-71) NAME OF USE CASE
-   STAKEHOLDER
    -   [UC-80](use-cases.html#UC-80) NAME OF USE CASE
    -   [UC-81](use-cases.html#UC-81) NAME OF USE CASE
-   STAKEHOLDER
    -   [UC-90](use-cases.html#UC-90) NAME OF USE CASE
    -   [UC-91](use-cases.html#UC-91) NAME OF USE CASE

### Use Cases by Priority {#use-cases-by-priority}

-   Essential
    -   [UC-00](use-cases.html#UC-00) Configure the site
    -   [UC-01](use-cases.html#UC-01) Register as a new user
    -   [UC-10](use-cases.html#UC-10) Create course
    -   [UC-11](use-cases.html#UC-11) View catalog description
    -   [UC-20](use-cases.html#UC-20) Enroll in course
    -   [UC-21](use-cases.html#UC-21) Drop course
    -   [UC-30](use-cases.html#UC-30) Assign course to room
    -   [UC-31](use-cases.html#UC-31) Assign course to room
-   Expected
    -   [UC-02](use-cases.html#UC-02) Request new password
    -   [UC-03](use-cases.html#UC-03) Edit user profile
    -   [UC-04](use-cases.html#UC-04) View user profile
    -   [UC-70](use-cases.html#UC-70) NAME OF USE CASE
    -   [UC-71](use-cases.html#UC-71) NAME OF USE CASE
    -   [UC-80](use-cases.html#UC-80) NAME OF USE CASE
    -   [UC-81](use-cases.html#UC-81) NAME OF USE CASE
-   Desired
    -   N/A: There are no use cases with Priority = Desired
-   Optional
    -   [UC-30](use-cases.html#UC-30) View room description
    -   [UC-90](use-cases.html#UC-90) NAME OF USE CASE
    -   [UC-91](use-cases.html#UC-91) NAME OF USE CASE

### Use Cases by Business Object and Actor {#use-cases-by-business-object-and-actor}

| BO \\ Actor    | All                                              | Student                                                                                                                             | Instructor                                | Admin                                                                     |
|----------------|--------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------|---------------------------------------------------------------------------|
| Student record | N/A                                              | [Register as new user](use-cases.html#UC-01) [Request new password](use-cases.html#UC-02) [Edit user profile](use-cases.html#UC-03) | [View user profile](use-cases.html#UC-04) | N/A                                                                       |
| Course         | [View catalog description](use-cases.html#UC-11) | [Enroll in course](use-cases.html#UC-20) [Drop course](use-cases.html#UC-21)                                                        | TODO                                      | [Create course](use-cases.html#UC-10) [Assign room](use-cases.html#UC-31) |
| Room           | [View room description](use-cases.html#UC-30)    | N/A                                                                                                                                 | N/A                                       | [Assign room](use-cases.html#UC-31)                                       |

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/use-case-suite.html)
and discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional use case suite template](http://www.readysetpro.com/).

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


