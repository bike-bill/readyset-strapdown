[QA Plan](qa-plan.html) &gt; Review Meeting Notes {#qa-plan-review-meeting-notes}
-------------------------------------------------

### Review Meeting Information {#review-meeting-information}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Product:</td>
<td><a href="http://www.COMPANY.com/products/PRODUCTNAME/">PRODUCTNAME</a></td>
</tr>
<tr class="even">
<td>Release Number:</td>
<td>X.Y.Z</td>
</tr>
<tr class="odd">
<td>Location of Meeting:</td>
<td>LOCATION, BUILDING, ROOM</td>
</tr>
<tr class="even">
<td>Date and Time of Meeting:</td>
<td>YEAR/MONTH/DAY HH:MM</td>
</tr>
<tr class="odd">
<td>Attendees:</td>
<td><div>
PERSONNAME
</div>
<div>
PERSONNAME
</div>
<div>
PERSONNAME
</div>
<div>
PERSONNAME
</div></td>
</tr>
<tr class="even">
<td>Related documents:</td>
<td><div>
<a href="review-meeting-checklists.html">Review Meeting Checklists</a>
</div></td>
</tr>
</tbody>
</table>

### Documents and Code Reviewed at this Meeting {#documents-and-code-reviewed-at-this-meeting}

-   [Feature list section of
    requirements](/requirements.html#functional)
-   [Multi-user section of requirements](/requirements.html#multiuser)
-   [Hello.java](/source/browse/PROJECTNAME/src/Hello.java)
-   [HelloStream.java](/source/browse/PROJECTNAME/src/HelloStream.java)
-   [HelloPanel.java](/source/browse/PROJECTNAME/src/HelloPanel.java)

### Meeting Minutes {#meeting-minutes}

TODO: Fill in the information above and write a brief summary of what
happened at the meeting. The text below is just a sample.

We started on time with 3 members and the other team members arrived
shortly thereafter.

In the first hour of the review meeting, we went over issues that the
team had entered individually. Most of the issues raised questions about
the error handling capability of Hello.java, but there were also issues
about multi-user robustness requirements and UI.

In the second hour, we read through all of the methods of
HelloStream.java. All team members agreed that they understood each
method and thought is was correct before we moved on to the next method.
We raised issues of consistency between the constructors in that class
and other classes. The checklist was helpful in identifying the fact
that we needed to implement hash() and equals(). All raised issues were
entered into the issue tracker and marked with the word "review".

Although, some issues were found, we do not feel that Hello.java and
HelloStream.java need to be inspected again. HelloPanel was not
inspected, it still needs review.

### Action Items {#action-items}

All defects and tasks identified in this review are being tracked in the
issue tracker.

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/review-meeting-notes.html)
and discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional review report
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


