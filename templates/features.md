[SRS](srs.html) &gt; [Feature Set](feature-set.html) &gt; Features {#srs-feature-set-features}
------------------------------------------------------------------

### Release Information {#release-information}

|Project:                  |PROJECTNAME                        |
|:-------------------------|:----------------------------------|
|Internal Release Number:  |X.Y.Z                              |
|Related Documents:        |[Project proposal](proposal) > [User needs](user-needs), [SRS](srs) > [Use case suite](use-case-suite), [Feature format](feature-format), LINKS TO RELEVANT STANDARDS, LINKS TO OTHER DOCUMENTS|

**Process impact:** This is a set of detailed feature descriptions.

TODO: For each feature listed in the [feature set](feature-set.html),
give a detailed description of the feature here. Describe each feature
in enough detail that it could be implemented by any member of the
development team (not only someone who already informally knows what to
do).

TIP: Start with a short textual description of each feature. Then, add
more formal information as needed to make each description precise and
unambiguous. E.g.,
-   Precisely define valid inputs, and error handling
-   Specify data structures with UML or logical schema
-   Specify UI aspects of features with tiny mock-ups
-   Specify key decisions with decision trees or tables
-   Specify key algorithms with pseudo-code or flow charts
-   Specify state-based behavior with state machines or tables
-   Specify sequences of events with scenario diagrams

### F-00: Site Configuration {#f-00-site-configuration}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Days</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>Administration</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-00">UC-00</a> <a href="use-cases.html#UC-11">UC-11</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td>The site administrators will be able to configure:
<ul>
<li>The site appearance by choosing a predefined CSS file</li>
<li>Whether the site makes new clans public or private by default</li>
<li>The email address to be used to send critical error reports</li>
</ul></td>
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

### F-01: User registration {#f-01-user-registration}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Days</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>Administration</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td>Visitors can come to the site and register themselves. They must provide the following information:
<ul>
<li>username</li>
<li>email address (twice to catch typos)</li>
<li>real name</li>
</ul>
<p>Precise Details:</p>
<ul>
<li>username must be unique (not equal to any other existing user name)</li>
<li>username must be of the form <code>[a-zA-Z0-9]{2,16}</code> and is not case sensitive</li>
<li>email address must be of the form <code>[-a-zA-Z0-9_.]{2,16}@[-a-zA-Z0-9_.]{6,64}</code></li>
<li>both entries of the email address must match</li>
<li>email address will be verified by sending the user's initial password there</li>
<li>real name must not be empty</li>
<li>leading and trailing spaces are stripped from all fields</li>
</ul></td>
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

### F-02: FEATURE NAME {#f-02-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-03: FEATURE NAME {#f-03-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-10: FEATURE NAME {#f-10-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-11: FEATURE NAME {#f-11-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-12: FEATURE NAME {#f-12-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-13: FEATURE NAME {#f-13-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-20: FEATURE NAME {#f-20-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-21: FEATURE NAME {#f-21-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-22: FEATURE NAME {#f-22-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-23: FEATURE NAME {#f-23-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-30: FEATURE NAME {#f-30-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-31: FEATURE NAME {#f-31-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-32: FEATURE NAME {#f-32-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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

### F-33: FEATURE NAME {#f-33-feature-name}

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Priority:</td>
<td>Essential | Expected | Desired | Optional</td>
</tr>
<tr class="even">
<td>Effort:</td>
<td>Months | Weeks | Days | Hours</td>
</tr>
<tr class="odd">
<td>Risk:</td>
<td>Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe</td>
</tr>
<tr class="even">
<td>Functional area(s):</td>
<td>WORD, WORD, WORD</td>
</tr>
<tr class="odd">
<td>Use case(s):</td>
<td><a href="use-cases.html#UC-01">UC-01</a></td>
</tr>
<tr class="even">
<td>Description:</td>
<td><p>1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.</p>
<p>Precise Details:</p>
<ul>
<li>LOGICAL CONSTRAINT</li>
<li>LOGICAL CONSTRAINT</li>
</ul></td>
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
wisdom](http://readyset.tigris.org/words-of-wisdom/features.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional feature specification
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


