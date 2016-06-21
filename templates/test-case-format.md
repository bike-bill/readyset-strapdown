[QA Plan](qa-plan.html) &gt; [Test Suite](test-suite.html) &gt; Test Case Format {#qa-plan-test-suite-test-case-format}
--------------------------------------------------------------------------------

**Process impact:** This reference page documents the format of test
cases and gives tips on writing test cases. You can copy and paste the
sample test case into your test-cases.html file. This file itself should
not be edited to hold specific test cases.
This test case format is suitable for manual system test cases.

The test cases should be written in enough detail that they could be
given to a new team member who would be able to quickly start to carry
out the tests and find defects.

### unique-test-case-id: Test Case Title {#unique-test-case-id-test-case-title}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Purpose:</td>
<td>Short sentence or two about the aspect of the system is being tested. If this gets too long, break the test case up or put more information into the feature descriptions.</td>
</tr>
<tr class="even">
<td>Prereq:</td>
<td>Assumptions that must be met before the test case can be run. E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;, &quot;user testuser exists&quot;.</td>
</tr>
<tr class="odd">
<td>Test Data:</td>
<td>List of variables and their possible values used in the test case. You can list specific values or describe value ranges. The test case should be performed once for each <em>combination</em> of values. These values are written in set notation, one per line. E.g.:
<div>
loginID = {Valid loginID, invalid loginID, valid email, invalid email, empty}
</div>
<div>
password = {valid, invalid, empty}
</div></td>
</tr>
<tr class="even">
<td>Steps:</td>
<td>Steps to carry out the test. See step formating rules below.
<ol>
<li>visit LoginPage</li>
<li>enter userID</li>
<li>enter password</li>
<li>click login</li>
<li>see the terms of use page</li>
<li>click agree radio button at page bottom</li>
<li>click submit button</li>
<li>see PersonalPage</li>
<li>verify that welcome message is correct username</li>
</ol></td>
</tr>
<tr class="odd">
<td>Notes and Questions:</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### Format of test steps {#format-of-test-steps}

Each step can be written very tersely using the following keywords:

login \[as ROLE-OR-USER\]
:   Log into the system with a given user or a user of the given type.
    Usually only stated explicitly when the test case depends on the
    permissions of a particular role or involves a workflow between
    different users.

visit LOCATION
:   Visit a page or screen. For web applications, LOCATION may be
    a hyperlink. The location should be a well-known starting point
    (e.g., the Login screen), drilling down to specific pages should be
    part of the test.

enter FIELD-NAME \[as VALUE\] \[in SCREEN-LOCATION\]
:   Fill in a named form field. VALUE can be a literal value or the name
    of a variable defined in the "Test Data" section. The FIELD-NAME
    itself can be a variable name when the UI field for that value is
    clear from context, e.g., "enter password".

enter FIELDS
:   Fill in all fields in a form when their values are clear from
    context or when their specific values are not important in this
    test case.

click "LINK-LABEL" \[in SCREEN-LOCATION\]
:   Follow a labeled link or press a button. The screen location can be
    a predefined panel name or English phrase. Predefined panel names
    are based on GUI class names, master template names, or titles of
    boxes on the page.

click BUTTON-NAME \[in SCREEN-LOCATION\]
:   Press a named button. This step should always be followed by a "see"
    step to check the results.

see SCREEN-OR-PAGE
:   The tester should see the named GUI screen or web page. The general
    correctness of the page should be testable based on the
    feature description.

verify CONDITION
:   The tester should see that the condition has been satisfied. This
    type of step usually follows a "see" step at the end of the
    test case.

verify CONTENT \[is VALUE\]
:   The tester should see the named content on the current page, the
    correct values should be clear from the test data, or
    given explicitly. This type of step usually follows a "see" step at
    the end of the test case.

perform TEST-CASE-NAME
:   This is like a subroutine call. The tester should perform all the
    steps of the named test case and then continue on to the next step
    of this test case.

Every test case must include a verify step at the end so that the
expected output is very clear. A test case can have multiple verify
steps in the middle or at the end. Having multiple verify steps can be
useful if you want a smaller number of long tests rather than a large
number of short tests.

### Further Information {#further-information}

For more information on advice, see:

-   Words of wisdom on [test case
    suites](http://readyset.tigris.org/words-of-wisdom/test-case-suites.html).
-   Words of wisdom on [test
    cases](http://readyset.tigris.org/words-of-wisdom/test-cases.html).

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


