[QA Plan](qa-plan.html) &gt; Test Suite {#qa-plan-test-suite}
---------------------------------------

### Release Information {#release-information}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Project:</td>
<td><a href="index.html">PROJECTNAME</a></td>
</tr>
<tr class="even">
<td>Internal Release Number:</td>
<td>X.Y.Z</td>
</tr>
<tr class="odd">
<td>Related Documents:</td>
<td><div>
<a href="test-case-format.html">Test case format</a>
</div>
<div>
LINKS TO RELEVANT STANDARDS
</div>
<div>
LINKS TO OTHER DOCUMENTS
</div></td>
</tr>
</tbody>
</table>

**Process impact:** This is a test suite for manual system testing. It
is just one activity in the overall [QA plan](qa-plan.html). A test case
suite is simply a table of contents for the individual test cases.
Organizing the suite of test cases by priority, functional area, actor,
business object, or release can help identify parts of the system that
need additional test cases.

TODO: Before writing individual test cases, list the test cases that you
think you will need. Organize them in a way that will purposely leave
visible blanks on this page if you are missing use cases. Choose one or
more of the organizations show below.

TIP: Refer back to your [use cases](use-cases.html) document. Use them
for ideas and make sure that you cover all of them. Remember that test
cases are more precise than use cases, test cases should reference
specific details of your implementation, and there may be several test
cases for a given use case.

TIP: The test case suite can be organized into nested lists according to
other coverage criteria, e.g., by actor. Or, it can be organized into
tables that consider two aspects at a time, e.g., business objects vs.
actor. If a certain section of the tree or table does not need test
cases, explicitly mark it "N/A". Otherwise, if a section needs more test
cases than you have written yet, mark it "TODO". If one cell or list
item contains many tests, break that section out into its own table, as
done for the enrollment feature below.

### Test Cases by Business Object and Operation {#test-cases-by-business-object-and-operation}

| BO \\ Action | add                                                                                                                                          | list/browse                                      | edit                                                                                                                                                     | delete                                              | search                                                                                                    | other                                                                                 |
|--------------|----------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| Student      | [student-add-1](test-cases.html#student-add-1) [student-add-2](test-cases.html#student-add-2) [student-add-3](test-cases.html#student-add-3) | [student-list-1](test-cases.html#student-list-1) | [student-edit-1](test-cases.html#student-edit-1) [student-edit-2](test-cases.html#student-edit-2)                                                        | [student-delete-1](test-cases.htmlstudent-delete-1) | [student-search-1](test-cases.html#student-search-1) [student-search-2](test-cases.html#student-search-2) | [See grid below](#enroll-grid)                                                        |
| Course       | [course-add-1](test-cases.html#course-add-1) [course-add-2](test-cases.html#course-add-2)                                                    | [course-list-1](test-cases.html#course-list-1)   | [course-edit-1](test-cases.html#course-edit-1) [course-move-1](test-cases.html#course-move-1) [course-add-prereq-1](test-cases.html#course-add-prereq-1) | [course-cancel-1](test-cases.html#course-cancel-1)  | [course-search-1](test-cases.html#course-search-1)                                                        | N/A                                                                                   |
| Room         | [room-add-1](test-cases.html#room-add-1) [room-add-2](test-cases.html#room-add-2)                                                            | [room-list-1](test-cases.html#room-list-1)       | TODO                                                                                                                                                     | TODO                                                | TODO                                                                                                      | N/A                                                                                   |
| Instructor   | [inst-add-1](test-cases.html#inst-add-1)                                                                                                     | N/A                                              | [inst-edit-1](test-cases.html#inst-edit-1)                                                                                                               | [inst-delete-1](test-cases.html#inst-delete-1)      | N/A                                                                                                       | [inst-eval-1](test-cases.html#inst-eval-1) [inst-eval-2](test-cases.html#inst-eval-2) |

#### Test Cases for Enrolling in Courses {#test-cases-for-enrolling-in-courses}

| Course \\ Student | New Freshman                                           | Senior                                                 | Any Honors                                             | Other                                                                                                          |
|-------------------|--------------------------------------------------------|--------------------------------------------------------|--------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| In Major          | [enroll-priority-2](test-cases.html#enroll-priority-2) | [enroll-priority-1](test-cases.html#enroll-priority-1) | [enroll-priority-1](test-cases.html#enroll-priority-1) | [enroll-1](test-cases.html#enroll-1) [enroll-2](test-cases.html#enroll-2) [enroll-3](test-cases.html#enroll-3) |
| Non-Major         | [enroll-priority-2](test-cases.html#enroll-priority-2) | [enroll-priority-1](test-cases.html#enroll-priority-1) | [enroll-priority-1](test-cases.html#enroll-priority-1) | [enroll-1](test-cases.html#enroll-1) [enroll-2](test-cases.html#enroll-2) [enroll-3](test-cases.html#enroll-3) |
| Honors Course     | [enroll-priority-1](test-cases.html#enroll-priority-1) | [enroll-priority-1](test-cases.html#enroll-priority-1) | [enroll-priority-1](test-cases.html#enroll-priority-1) | [enroll-restricted-1](test-cases.html#enroll-restricted-1)                                                     |

### Test Cases by Feature Priority {#test-cases-by-feature-priority}

TODO: Use this outline to make sure that high priority features are
adequately tested. List features by priority, and then list the test
cases for each feature. If a feature needs more test cases, note that
with "TODO".

-   Essential
    -   [F-01](features.html#F-01):
        [student-add-1](test-cases.html#student-add-1)
        [student-add-2](test-cases.html#student-add-2)
        [student-add-3](test-cases.html#student-add-3)
    -   [F-02](features.html#F-02): [enroll-1](test-cases.html#enroll-1)
        [enroll-2](test-cases.html#enroll-2)
        [enroll-3](test-cases.html#enroll-3)
        [enroll-priority-1](test-cases.html#enroll-priority-1)
        [enroll-priority-2](test-cases.html#enroll-priority-2)
        [enroll-restricted-1](test-cases.html#enroll-restricted-1)
-   Expected
    -   [F-22](features.html#F-22):
        [student-search-1](test-cases.html#student-search-1)
        [student-search-2](test-cases.html#student-search-2)
        [course-search-1](test-cases.html#course-search-1)
    -   [F-23](features.html#F-23):
        [room-add-1](test-cases.html#room-add-1)
        [room-add-2](test-cases.html#room-add-2)
        [room-edit-1](test-cases.html#room-edit-1) TODO
-   Desired
    -   [F-31](features.html#F-31):
        [inst-eval-1](test-cases.html#inst-eval-1)
        [inst-eval-2](test-cases.html#inst-eval-2)

### Test Cases by Use Case Priority {#test-cases-by-use-case-priority}

TODO: Use this outline to make sure that high priority use cases are
adequately tested. List use cases by priority, and then list the test
cases for each use case. If a use case needs more test cases, note that
with "TODO".

-   Essential
    -   [UC-01](use-cases.html#UC-01):
        [student-add-1](test-cases.html#student-add-1)
        [student-add-2](test-cases.html#student-add-2)
    -   [UC-01](use-cases.html#UC-01):
        [student-add-3](test-cases.html#student-add-3)
    -   [UC-02](use-cases.html#UC-02):
        [enroll-1](test-cases.html#enroll-1)
    -   [UC-03](use-cases.html#UC-03):
        [enroll-2](test-cases.html#enroll-2)
    -   [UC-04](use-cases.html#UC-04):
        [enroll-3](test-cases.html#enroll-3)
    -   [UC-05](use-cases.html#UC-05):
        [enroll-priority-1](test-cases.html#enroll-priority-1)
        [enroll-priority-2](test-cases.html#enroll-priority-2)
    -   [UC-06](use-cases.html#UC-06):
        [enroll-restricted-1](test-cases.html#enroll-restricted-1)
-   Expected
    -   [UC-22](use-cases.html#UC-22):
        [student-search-1](test-cases.html#student-search-1)
        [student-search-2](test-cases.html#student-search-2)
    -   [UC-23](use-cases.html#UC-23):
        [course-search-1](test-cases.html#course-search-1)
    -   [UC-30](use-cases.html#UC-30):
        [room-add-1](test-cases.html#room-add-1)
        [room-add-2](test-cases.html#room-add-2)
    -   [UC-31](use-cases.html#UC-31):
        [room-edit-1](test-cases.html#room-edit-1) TODO
    -   [UC-32](use-cases.html#UC-32): TODO
    -   [UC-33](use-cases.html#UC-33): TODO
-   Desired
    -   [UC-40](use-cases.html#UC-40):
        [inst-eval-1](test-cases.html#inst-eval-1)
        [inst-eval-2](test-cases.html#inst-eval-2)

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/test-suite.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional test plan
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


