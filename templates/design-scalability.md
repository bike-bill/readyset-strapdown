[Design](design.html) &gt; Scalability {#design-scalability}
--------------------------------------

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
LINKS TO RELEVANT STANDARDS
</div>
<div>
LINKS TO OTHER DOCUMENTS
</div></td>
</tr>
</tbody>
</table>

### Overview {#overview}

TODO: Briefly describe the approach to scalability. Rank your
scalability goals for this design.

2-4 SENTENCES.

### Relevant parameters {#relevant-parameters}

| Parameter         | Description                                                                           |
|-------------------|---------------------------------------------------------------------------------------|
| registered\_users | Number of registered users in the database.                                           |
| concurrent\_users | Number of users logged into the system at a given time.                               |
| map\_size         | Number of game squares in the playing area. E.g., a 10 x 25 map would be 250 squares. |
| game\_pieces      | Number of game pieces on the playing area at a given time.                            |

### Scalability Mechanisms {#scalability-mechanisms}

### Performance Goals and Estimates {#performance-goals-and-estimates}

| Action       | Goal       | Time Formula                | Description                                                               |
|--------------|------------|-----------------------------|---------------------------------------------------------------------------|
| login        | 1 second   | O(Log(registered\_users))   | Time that it takes to look up a user by their login name in the database. |
| display\_map | 1/5 second | O(map\_size + game\_pieces) | Time that it takes to redraw the game map and all game pieces.            |

### System Scalability Checklist {#system-scalability-checklist}

How well do these mechanisms support the achievement of your goals?
:   2-4 SENTENCES

Have these scalability mechanisms been communicated to the development team and other stakeholders?
:   Yes, everyone understands. Feedback is welcome.
:   No, this is a risk that is noted in the [Risk
    Management](plan.html#risks) section.

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/design-scalability.html)
and discuss ways to improve this template.

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


