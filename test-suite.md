[QA Plan](qa-plan) &gt; Test Suite {#qa-plan-test-suite}
---------------------------------------

### Release Information {#release-information}

Project:
:   [PROJECTNAME](index)

Internal Release Number:
X.Y.Z

Related Documents:
:   [Test case format](test-case-format)
:   LINKS TO RELEVANT STANDARDS
:   LINKS TO OTHER DOCUMENTS

**Process impact:** This is a test suite for manual system testing. It
is just one activity in the overall [QA plan](qa-plan.). A test case
suite is simply a table of contents for the individual test cases.
Organizing the suite of test cases by priority, functional area, actor,
business object, or release can help identify parts of the system that
need additional test cases.

TODO: Before writing individual test cases, list the test cases that you
think you will need. Organize them in a way that will purposely leave
visible blanks on this page if you are missing use cases. Choose one or
more of the organizations show below.

TIP: Refer back to your [use cases](use-cases) document. Use them
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

<table>
    <thead>
        <tr>
            <th>BO \ Action</th>
            <th>add</th>
            <th>list/browse</th>
            <th>edit</th>
            <th>delete</th>
            <th>search</th>
            <th>other</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Student</td>
            <td><a href="test-cases#student-add-1">student-add-1</a><br />
                <a href="test-cases#student-add-2">student-add-2</a><br /> 
                <a href="test-cases#student-add-3">student-add-3</a></td>
            <td><a href="test-cases#student-list-1">student-list-1</a></td>
            <td><a href="test-cases#student-edit-1">student-edit-1</a><br /> 
                <a href="test-cases#student-edit-2">student-edit-2</a></td>
            <td><a href="test-casesstudent-delete-1">student-delete-1</a></td>
            <td><a href="test-cases#student-search-1">student-search-1</a><br />
                <a href="test-cases#student-search-2">student-search-2</a></td>
            <td><a href="#enroll-grid">See grid below</a></td>
        </tr>
        <tr>
            <td>Course</td>
            <td><a href="test-cases#course-add-1">course-add-1</a><br />
                <a href="test-cases#course-add-2">course-add-2</a></td>
            <td><a href="test-cases#course-list-1">course-list-1</a></td>
            <td><a href="test-cases#course-edit-1">course-edit-1</a><br />
                <a href="test-cases#course-move-1">course-move-1</a><br />
                <a href="test-cases#course-add-prereq-1">course-add-prereq-1</a></td>
            <td><a href="test-cases#course-cancel-1">course-cancel-1</a></td>
            <td><a href="test-cases#course-search-1">course-search-1</a></td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Room</td>
            <td><a href="test-cases#room-add-1">room-add-1</a><br />
                <a href="test-cases#room-add-2">room-add-2</a></td>
            <td><a href="test-cases#room-list-1">room-list-1</a></td>
            <td>TODO</td>
            <td>TODO</td>
            <td>TODO</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Instructor</td>
            <td><a href="test-cases#inst-add-1">inst-add-1</a></td>
            <td>N/A</td>
            <td><a href="test-cases#inst-edit-1">inst-edit-1</a></td>
            <td><a href="test-cases#inst-delete-1">inst-delete-1</a></td>
            <td>N/A</td>
            <td><a href="test-cases#inst-eval-1">inst-eval-1</a><br />
                <a href="test-cases#inst-eval-2">inst-eval-2</a></td>
        </tr>
    </tbody>
</table>

### Test Cases for Enrolling in Courses {#test-cases-for-enrolling-in-courses}

<table>
    <thead>
        <tr>
            <th>Course \ Student</th>
            <th>New Freshman</th>
            <th>Senior</th>
            <th>Any Honors</th>
            <th>Other</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>In Major</td>
            <td><a href="test-cases#enroll-priority-2">enroll-priority-2</a></td>
            <td><a href="test-cases#enroll-priority-1">enroll-priority-1</a></td>
            <td><a href="test-cases#enroll-priority-1">enroll-priority-1</a></td>
            <td><a href="test-cases#enroll-1">enroll-1</a><br />
                <a href="test-cases#enroll-2">enroll-2</a><br />
                <a href="test-cases#enroll-3">enroll-3</a></td>
        </tr>
        <tr>
            <td>Non-Major</td>
            <td><a href="test-cases#enroll-priority-2">enroll-priority-2</a></td>
            <td><a href="test-cases#enroll-priority-1">enroll-priority-1</a></td>
            <td><a href="test-cases#enroll-priority-1">enroll-priority-1</a></td>
            <td><a href="test-cases#enroll-1">enroll-1</a><br />
                <a href="test-cases#enroll-2">enroll-2</a><br />
                <a href="test-cases#enroll-3">enroll-3</a></td>
        </tr>
        <tr>
            <td>Honors Course</td>
            <td><a href="test-cases#enroll-priority-1">enroll-priority-1</a></td>
            <td><a href="test-cases#enroll-priority-1">enroll-priority-1</a></td>
            <td><a href="test-cases#enroll-priority-1">enroll-priority-1</a></td>
            <td><a href="test-cases#enroll-restricted-1">enroll-restricted-1</a></td>
        </tr>
    </tbody>
</table>

### Test Cases by Feature Priority {#test-cases-by-feature-priority}

TODO: Use this outline to make sure that high priority features are
adequately tested. List features by priority, and then list the test
cases for each feature. If a feature needs more test cases, note that
with "TODO".

-   Essential
    -   [F-01](features#F-01):
        [student-add-1](test-cases#student-add-1)
        [student-add-2](test-cases#student-add-2)
        [student-add-3](test-cases#student-add-3)
    -   [F-02](features#F-02): [enroll-1](test-cases#enroll-1)
        [enroll-2](test-cases#enroll-2)
        [enroll-3](test-cases#enroll-3)
        [enroll-priority-1](test-cases#enroll-priority-1)
        [enroll-priority-2](test-cases#enroll-priority-2)
        [enroll-restricted-1](test-cases#enroll-restricted-1)
-   Expected
    -   [F-22](features#F-22):
        [student-search-1](test-cases#student-search-1)
        [student-search-2](test-cases#student-search-2)
        [course-search-1](test-cases#course-search-1)
    -   [F-23](features#F-23):
        [room-add-1](test-cases#room-add-1)
        [room-add-2](test-cases#room-add-2)
        [room-edit-1](test-cases#room-edit-1) TODO
-   Desired
    -   [F-31](features#F-31):
        [inst-eval-1](test-cases#inst-eval-1)
        [inst-eval-2](test-cases#inst-eval-2)

### Test Cases by Use Case Priority {#test-cases-by-use-case-priority}

TODO: Use this outline to make sure that high priority use cases are
adequately tested. List use cases by priority, and then list the test
cases for each use case. If a use case needs more test cases, note that
with "TODO".

-   Essential
    -   [UC-01](use-cases#UC-01):
        [student-add-1](test-cases#student-add-1)
        [student-add-2](test-cases#student-add-2)
    -   [UC-01](use-cases#UC-01):
        [student-add-3](test-cases#student-add-3)
    -   [UC-02](use-cases#UC-02):
        [enroll-1](test-cases#enroll-1)
    -   [UC-03](use-cases#UC-03):
        [enroll-2](test-cases#enroll-2)
    -   [UC-04](use-cases#UC-04):
        [enroll-3](test-cases#enroll-3)
    -   [UC-05](use-cases#UC-05):
        [enroll-priority-1](test-cases#enroll-priority-1)
        [enroll-priority-2](test-cases#enroll-priority-2)
    -   [UC-06](use-cases#UC-06):
        [enroll-restricted-1](test-cases#enroll-restricted-1)
-   Expected
    -   [UC-22](use-cases#UC-22):
        [student-search-1](test-cases#student-search-1)
        [student-search-2](test-cases#student-search-2)
    -   [UC-23](use-cases#UC-23):
        [course-search-1](test-cases#course-search-1)
    -   [UC-30](use-cases#UC-30):
        [room-add-1](test-cases#room-add-1)
        [room-add-2](test-cases#room-add-2)
    -   [UC-31](use-cases#UC-31):
        [room-edit-1](test-cases#room-edit-1) TODO
    -   [UC-32](use-cases#UC-32): TODO
    -   [UC-33](use-cases#UC-33): TODO
-   Desired
    -   [UC-40](use-cases#UC-40):
        [inst-eval-1](test-cases#inst-eval-1)
        [inst-eval-2](test-cases#inst-eval-2)

TODO: Check for [words of wisdom](http://readyset.tigris.org/words-of-wisdom/test-suite.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional test plan template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License terms](readyset-license.html). Retain this copyright statement whenever this file is used as a template.


