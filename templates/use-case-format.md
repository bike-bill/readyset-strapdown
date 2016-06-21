[SRS](srs.html) &gt; [Use Case Suite](use-case-suite.html) &gt; Use Case Format {#srs-use-case-suite-use-case-format}
-------------------------------------------------------------------------------

**Process impact:** This reference page documents the format of use
cases and gives tips on writing use cases. You can copy and paste the
sample use case into your [Use Cases](use-cases.html) document. This
file itself should not be edited to hold specific use cases.

TODO: Use this template once in your [Use Cases](use-cases.html)
document. Anything you mention here will apply to all use cases in that
file.

### Aspects common to all use cases {#aspects-common-to-all-use-cases}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Direct Actors:</td>
<td><div>
User: end-user in any role
</div>
<div>
System: The system being built
</div>
<div>
When actors are not listed, assume User is doing it.
</div>
<div>
Items beginning with &quot;see&quot; indicate that System has presented a new screen.
</div></td>
</tr>
<tr class="even">
<td>Stakeholders:</td>
<td>The user who is entering the data, and those who will read it</td>
</tr>
<tr class="odd">
<td>Prereq:</td>
<td>Project is set up</td>
</tr>
</tbody>
</table>

TODO: Copy and paste this use case template as many times as needed in
your [Use Cases](use-cases.html) document. Only use those fields that
are not the same as the default for all use cases.

### UC-00: USE CASE NAME {#uc-00-use-case-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Summary:</td>
<td>1-3 SENTENCES</td>
</tr>
<tr class="even">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="odd">
<td>Use Frequency:</td>
<td>Always | Often | Sometimes | Rarely | Once</td>
</tr>
<tr class="even">
<td>Direct Actors:</td>
<td>ACTOR1, ACTOR2, ACTOR3</td>
</tr>
<tr class="odd">
<td>Stakeholders:</td>
<td>STAKEHOLDER, STAKEHOLDER, STAKEHOLDER</td>
</tr>
<tr class="even">
<td>Prereq:</td>
<td><div>
PRECONDITION
</div>
<div>
PRECONDITION
</div>
<div>
PRECONDITION
</div></td>
</tr>
<tr class="odd">
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="even">
<td>Alternative Scenario Extensions:</td>
<td><ul>
<li>If CONDITION, then ALTERNATIVE STEPS.
<ul>
<li>NOTES or DETAILS.</li>
</ul></li>
<li>If CONDITION, then ALTERNATIVE STEPS.
<ul>
<li>NOTES or DETAILS.</li>
</ul></li>
</ul></td>
</tr>
<tr class="odd">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>NOTE</li>
<li>QUESTION</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### Format of Use Case Steps {#format-of-use-case-steps}

Try to start each step with one of these action words:

login \[as ROLE or USER\]
:   Log into the system with a given user or a user of the given type.
    Usually usually only stated explicitly when the test case involves a
    workflow between different users.

visit LOCATION
:   Visit a page or GUI window. State the user's intention, don't say
    too much about UI choices that could change later. E.g., WRONG:
    "Press the 'Advanced...' button on the File | Page Setup dialog".
    RIGHT: "Visit the page margin configuration dialog".

enter INFORMATION
:   Fill in specific information. Try to state the information in
    some detail. E.g., WRONG: "Enter customer information." RIGHT:
    "Enter customer shipping address and discount code." Don't commit to
    details of a particular UI, i.e., don't name specific UI fields that
    might change later.

COMMAND
:   Describe a command that the user can tell the system to do. State
    the user's intent, not the label on a particular UI widget. This
    will usually be followed by a "see" step where the user sees a
    confirmation of their action. E.g., WRONG: "Control-P, OK". RIGHT:
    "Print the current document with default settings".

see CONTENT
:   The user should see the specified information on the currently
    presented web page or GUI window. Try to be specific about the
    information that is seen, but try not to refer to specific
    UI elements. E.g., WRONG: "see UserList.jsp" (what is the user
    supposed to notice on that page?) RIGHT: "see list of users with the
    newly added user in the list".

perform USE-CASE-NAME
:   This is like a subroutine call. The user will do all the steps of
    the named use case and then continue on with the next step of this
    use case.

### Further Information {#further-information}

For more information on advice, see:

-   Words of wisdom on [use case
    suites](http://readyset.tigris.org/words-of-wisdom/use-case-suite.html).
-   Words of wisdom on [use
    cases](http://readyset.tigris.org/words-of-wisdom/use-cases.html).

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/use-case-format.html)
and discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional use case format
document](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


