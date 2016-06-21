[QA Plan](qa-plan.html) &gt; [Test Suite](test-suite.html) &gt; Test Cases {#qa-plan-test-suite-test-cases}
--------------------------------------------------------------------------

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
<a href="test-case-format.html">System test case format</a>
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

### login-1: Normal User Login {#login-1-normal-user-login}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Purpose:</td>
<td>Test that users can log in with the proper username or email address and their password.</td>
</tr>
<tr class="even">
<td>Prereq:</td>
<td><div>
User is not already logged in.
</div>
<div>
User testuser exists, and account is in good standing.
</div></td>
</tr>
<tr class="odd">
<td>Test Data:</td>
<td><div>
usernameOrEmail = {testuser, bogususer, testuser@nospam.com, test@user@nospam.com, empty}
</div>
<div>
password = {valid, invalid, empty}
</div></td>
</tr>
<tr class="even">
<td>Steps:</td>
<td><ol>
<li>visit LoginPage</li>
<li>enter usernameOrEmail</li>
<li>enter password</li>
<li>click Login</li>
<li>see the terms-of-use page</li>
<li>click Agree at page bottom</li>
<li>click Submit</li>
<li>see PersonalPage</li>
<li>verify welcome message is correct username</li>
</ol></td>
</tr>
<tr class="odd">
<td>Notes and Questions:</td>
<td><ul>
<li>This assumes that user has not agreed to terms-of-use already.</li>
<li>Does this work without browser cookies?</li>
</ul></td>
</tr>
</tbody>
</table>

### login-2: Locked-out User Login {#login-2-locked-out-user-login}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Purpose:</td>
<td>Test that a user who has been locked out by a moderator, cannot log in, They should see a message indicating that they were locked out.</td>
</tr>
<tr class="even">
<td>Prereq:</td>
<td><div>
User is not already logged in.
</div>
<div>
User testuser2 exists, and has been locked out
</div></td>
</tr>
<tr class="odd">
<td>Test Data:</td>
<td><div>
usernameOrEmail = {testuser2, testuser2@nospam.com}
</div>
<div>
password = {valid}
</div></td>
</tr>
<tr class="even">
<td>Steps:</td>
<td><ol>
<li>visit LoginPage</li>
<li>enter usernameOrEmail</li>
<li>enter password</li>
<li>click Login</li>
<li>see LoginPage</li>
<li>verify warning message is the locked-out message</li>
</ol></td>
</tr>
<tr class="odd">
<td>Notes and Questions:</td>
<td><ul>
<li>Does this work without browser cookies?</li>
</ul></td>
</tr>
</tbody>
</table>

### unique-test-case-id1: Test Case Title {#unique-test-case-id1-test-case-title}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Purpose:</td>
<td></td>
</tr>
<tr class="even">
<td>Prereq:</td>
<td></td>
</tr>
<tr class="odd">
<td>Test Data:</td>
<td><div>
VAR = {VALUES}
</div>
<div>
VAR = {VALUES}
</div></td>
</tr>
<tr class="even">
<td>Steps:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
<li>verify ...</li>
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

### unique-test-case-id2: Test Case Title {#unique-test-case-id2-test-case-title}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Purpose:</td>
<td>SENTENCES</td>
</tr>
<tr class="even">
<td>Prereq:</td>
<td>SENTENCES</td>
</tr>
<tr class="odd">
<td>Test Data:</td>
<td><div>
VAR = {VALUES}
</div>
<div>
VAR = {VALUES}
</div></td>
</tr>
<tr class="even">
<td>Steps:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
<li>verify ...</li>
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

### unique-test-case-id3: Test Case Title {#unique-test-case-id3-test-case-title}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Purpose:</td>
<td>SENTENCES</td>
</tr>
<tr class="even">
<td>Prereq:</td>
<td>SENTENCES</td>
</tr>
<tr class="odd">
<td>Test Data:</td>
<td><div>
VAR = {VALUES}
</div>
<div>
VAR = {VALUES}
</div></td>
</tr>
<tr class="even">
<td>Steps:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
<li>verify ...</li>
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

### unique-test-case-id4: Test Case Title {#unique-test-case-id4-test-case-title}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Purpose:</td>
<td>SENTENCES</td>
</tr>
<tr class="even">
<td>Prereq:</td>
<td>SENTENCES</td>
</tr>
<tr class="odd">
<td>Test Data:</td>
<td><div>
VAR = {VALUES}
</div>
<div>
VAR = {VALUES}
</div></td>
</tr>
<tr class="even">
<td>Steps:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
<li>verify ...</li>
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

### unique-test-case-id5: Test Case Title {#unique-test-case-id5-test-case-title}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Purpose:</td>
<td>SENTENCES</td>
</tr>
<tr class="even">
<td>Prereq:</td>
<td>SENTENCES</td>
</tr>
<tr class="odd">
<td>Test Data:</td>
<td><div>
VAR = {VALUES}
</div>
<div>
VAR = {VALUES}
</div></td>
</tr>
<tr class="even">
<td>Steps:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
<li>verify ...</li>
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

### unique-test-case-id6: Test Case Title {#unique-test-case-id6-test-case-title}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Purpose:</td>
<td>SENTENCES</td>
</tr>
<tr class="even">
<td>Prereq:</td>
<td>SENTENCES</td>
</tr>
<tr class="odd">
<td>Test Data:</td>
<td><div>
VAR = {VALUES}
</div>
<div>
VAR = {VALUES}
</div></td>
</tr>
<tr class="even">
<td>Steps:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
<li>verify ...</li>
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

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/test-runs.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional test case
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.
