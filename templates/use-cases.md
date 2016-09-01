[SRS](srs) &gt; [Use Case Suite](use-case-suite) &gt; Use Cases {#srs-use-case-suite-use-cases}
-------------------------------------------------------------------------

### Release Information {#release-information}

| Project:                      | PROJECTNAME |
|-------------------------------|-------------|
| Internal Release Number:      | X.Y.Z       |
| Related Documents:            |[Project proposal](proposal) > [User needs](user-needs), [SRS](srs) > [Feature set](feature-set), [Use case format](use-case-format), LINK TO USE CASE DIAGRAM, LINKS TO RELEVANT STANDARDS, LINKS TO OTHER DOCUMENTS:  |

TODO: Note any aspects that are common to all use cases here. This helps
keep the use cases themselves short. If any use case is an exception,
note it's specific value to replace or add to the default.

### Default Aspects of All Use Cases {#default-aspects-of-all-use-cases}
|   |   |
|---|---|
|Direct Actors:| User: end-user in any role<BR>
System: The system being built<BR>
When actors are not listed, assume User is doing it.<BR>
Items beginning with "see" indicate that System has presented a new screen.|
|Stakeholders:| xxx |
|Prereq:| yyy |

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
<td>Project Owners and other members</td>
</tr>
<tr class="odd">
<td>Prereq:</td>
<td>User is logged in</td>
</tr>
</tbody>
</table>

TODO: For each use case listed in the [use case
suite](use-case-suite.html), create an HTML anchor and heading with it's
unique ID, then fill in the rows of the table to specify the use case in
detail.

TIP: It is OK to simply list the names of a lot of use cases without
actually writing the use case in detail. Document the most important use
cases first and come back to less important ones later.

TIP: See detailed tips in the [guidelines for writing use
cases](use-case-format.html#guidelines).

### UC-00: Configure the site {#uc-00-configure-the-site}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Summary:</td>
<td>The administrator navigates to the site configuration page and uses it to change the behavior of the web application. Specifically, the user-visible timezone is being set.</td>
</tr>
<tr class="even">
<td>Priority:</td>
<td>Essential</td>
</tr>
<tr class="odd">
<td>Use Frequency:</td>
<td>Rarely</td>
</tr>
<tr class="even">
<td>Direct Actors:</td>
<td><div>
Admin: Web-site administrator
</div></td>
</tr>
<tr class="odd">
<td>Main Success Scenario:</td>
<td><ol>
<li>visit SiteConfiguration page</li>
<li>see site configuration options</li>
<li>enter timezone abbreviation for date displays</li>
<li>submit form</li>
<li>confirm changes</li>
<li>see SiteConfiguration page again, with updated values</li>
</ol></td>
</tr>
<tr class="even">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
<td><ul>
<li>If the timezone abbreviation is incorrect, an error message will be displayed and no changes will be made.</li>
</ul></td>
</tr>
<tr class="odd">
<td>Notes and Questions</td>
<td><ul>
<li>How will administrators know the right timezone abbreviation? They would know it if they live in that timezone. Maybe we could provide a drop-down list of all choices, but each would need some explanation.</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-01: Register as a new user {#uc-01-register-as-a-new-user}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Summary:</td>
<td>Users need to register themselves in this web application.</td>
</tr>
<tr class="even">
<td>Priority:</td>
<td>Essential</td>
</tr>
<tr class="odd">
<td>Use Frequency:</td>
<td>Once per user</td>
</tr>
<tr class="even">
<td>Main Success Scenario:</td>
<td><ol>
<li>visit Login page</li>
<li>click to register as new user</li>
<li>enter identifying information: username, email, real name, password (twice)</li>
<li>submit form</li>
<li>check email</li>
<li>reply to confirmation message</li>
<li>log in</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
<td><ul>
<li>If the username is taken, then the system will suggest an available username based on the user's email address and/or real name.</li>
</ul></td>
</tr>
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-02: Request new password {#uc-02-request-new-password}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Summary:</td>
<td>If a user forgets their password, they can request a new one be emailed to them.</td>
</tr>
<tr class="even">
<td>Priority:</td>
<td>Expected</td>
</tr>
<tr class="odd">
<td>Use Frequency:</td>
<td>Rarely</td>
</tr>
<tr class="even">
<td>Main Success Scenario:</td>
<td><ol>
<li>TODO</li>
</ol></td>
</tr>
<tr class="odd">
<td>Notes and Questions</td>
<td><ul>
<li>Alternatively, we could use password hints.</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-03: Edit user profile {#uc-03-edit-user-profile}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Summary:</td>
<td>Users can edit their own account preferences.</td>
</tr>
<tr class="even">
<td>Priority:</td>
<td>Expected</td>
</tr>
<tr class="odd">
<td>Use Frequency:</td>
<td>Rarely</td>
</tr>
<tr class="even">
<td>Main Success Scenario:</td>
<td><ol>
<li>TODO</li>
</ol></td>
</tr>
</tbody>
</table>

### UC-04: View user profile {#uc-04-view-user-profile}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Summary:</td>
<td>Users can view the profiles of other users under certain circumstances.</td>
</tr>
<tr class="even">
<td>Direct Actors:</td>
<td><div>
Admin: Web-site administrator
</div></td>
</tr>
<tr class="odd">
<td>Priority:</td>
<td>Expected</td>
</tr>
<tr class="even">
<td>Use Frequency:</td>
<td>Rarely</td>
</tr>
<tr class="odd">
<td>Main Success Scenario:</td>
<td><ol>
<li>TODO</li>
</ol></td>
</tr>
</tbody>
</table>

### UC-10: Create course {#uc-10-create-course}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Summary:</td>
<td>An administrator creates dozens of course offerings before the beginning of each school term.</td>
</tr>
<tr class="even">
<td>Direct Actors:</td>
<td><div>
Admin: Web-site administrator
</div></td>
</tr>
<tr class="odd">
<td>Priority:</td>
<td>Essential</td>
</tr>
<tr class="even">
<td>Use Frequency:</td>
<td>Often</td>
</tr>
<tr class="odd">
<td>Main Success Scenario:</td>
<td><ol>
<li>visit administrative function menu</li>
<li>click add course</li>
<li>enter course information: name, number, instructor, capacity</li>
<li>submit form</li>
<li>see course list with new course added</li>
</ol></td>
</tr>
</tbody>
</table>

### UC-11: View catalog description {#uc-11-view-catalog-description}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Summary:</td>
<td>Students may view the course catalog description of a course before registering. They are especially likely to view it if they are prevented from enrolling in a course because of a missing prerequisite.</td>
</tr>
<tr class="even">
<td>Priority:</td>
<td>Essential</td>
</tr>
<tr class="odd">
<td>Use Frequency:</td>
<td>Sometimes</td>
</tr>
<tr class="even">
<td>Main Success Scenario:</td>
<td><ol>
<li>visit one of several in application pages that deal with courses</li>
<li>click link to course description</li>
<li>see course description in pop-up window</li>
<li>close pop-up window to continue using application</li>
</ol></td>
</tr>
<tr class="odd">
<td>Notes and Questions</td>
<td><ul>
<li>How do we accommodate users that configure their browsers to block pop-ups?</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-20: Enroll in course {#uc-20-enroll-in-course}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Summary:</td>
<td>Students will enroll in courses</td>
</tr>
<tr class="even">
<td>Priority:</td>
<td>Essential</td>
</tr>
<tr class="odd">
<td>Use Frequency:</td>
<td>Often</td>
</tr>
<tr class="even">
<td>Main Success Scenario:</td>
<td><ol>
<li>visit main menu</li>
<li>click link to enroll in courses</li>
<li>enter major and course number</li>
<li>select course section from list of available sections</li>
<li>submit choice</li>
<li>confirm choice</li>
<li>see list of current enrolled courses</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
<td><ul>
<li>If a course is full, then the student may join the wait-list.
<ul>
<li>Course capacity and number of students currently waiting should be shown so that students may choose the section that they are most likely to be able to get into.</li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

### UC-21: Drop a course {#uc-21-drop-a-course}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Summary:</td>
<td>A student may drop a course that they are enrolled in.</td>
</tr>
<tr class="even">
<td>Priority:</td>
<td>Essential</td>
</tr>
<tr class="odd">
<td>Use Frequency:</td>
<td>Sometimes</td>
</tr>
<tr class="even">
<td>Main Success Scenario:</td>
<td><ol>
<li>visit list of currently enrolled courses</li>
<li>select course from list</li>
<li>click button to drop course</li>
<li>see warning that they may not be able to add this course again</li>
<li>confirm choice</li>
<li>see revised list of currently enrolled courses</li>
</ol></td>
</tr>
<tr class="odd">
<td>Notes and Questions</td>
<td><ul>
<li>Only one course can be dropped at a time. There is no need to allow students to quickly drop more than one course.</li>
<li>It would be nice to offer an atomic &quot;switch sections&quot; operation that drops and adds another, or does nothing.</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-30: View room description {#uc-30-view-room-description}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Summary:</td>
<td>Users can view descriptions of classrooms. E.g., is it a lecture hall or a lab? E.g., does it have a built-in LCD projector?</td>
</tr>
<tr class="even">
<td>Priority:</td>
<td>Optional</td>
</tr>
<tr class="odd">
<td>Use Frequency:</td>
<td>Rarely</td>
</tr>
<tr class="even">
<td>Main Success Scenario:</td>
<td><ol>
<li>TODO</li>
</ol></td>
</tr>
</tbody>
</table>

### UC-31: Assign course to room {#uc-31-assign-course-to-room}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Summary:</td>
<td>An administrator assigns each course to a room. This is often done after a course is created, but it can be redone at any time.</td>
</tr>
<tr class="even">
<td>Priority:</td>
<td>Essential</td>
</tr>
<tr class="odd">
<td>Use Frequency:</td>
<td>Often</td>
</tr>
<tr class="even">
<td>Main Success Scenario:</td>
<td><ol>
<li>TODO</li>
</ol></td>
</tr>
</tbody>
</table>

### UC-40: USE CASE NAME {#uc-40-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-41: USE CASE NAME {#uc-41-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-42: USE CASE NAME {#uc-42-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-50: USE CASE NAME {#uc-50-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-51: USE CASE NAME {#uc-51-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-52: USE CASE NAME {#uc-52-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-60: USE CASE NAME {#uc-60-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-61: USE CASE NAME {#uc-61-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-62: USE CASE NAME {#uc-62-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-70: USE CASE NAME {#uc-70-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-71: USE CASE NAME {#uc-71-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-72: USE CASE NAME {#uc-72-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-80: USE CASE NAME {#uc-80-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-81: USE CASE NAME {#uc-81-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-82: USE CASE NAME {#uc-82-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-90: USE CASE NAME {#uc-90-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

### UC-91: USE CASE NAME {#uc-91-use-case-name}

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
<td>Main Success Scenario:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td><div>
Alternative
</div>
Scenario Extensions:</td>
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
<tr class="even">
<td>Notes and Questions</td>
<td><ul>
<li>NOTE</li>
<li>QUESTION</li>
</ul></td>
</tr>
</tbody>
</table>

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/use-cases.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional use case template](http://www.readysetpro.com/).

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


