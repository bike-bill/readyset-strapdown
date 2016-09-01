[SRS](srs) &gt; [Feature Set](feature-set) &gt; Features {#srs-feature-set-features}
------------------------------------------------------------------

### Release Information {#release-information}

Project
:	PROJECTNAME

Internal Release Number
:	X.Y.Z

Related Documents
:	[Project proposal](proposal) > [User needs](user-needs)
:	[SRS](srs) > [Use case suite](use-case-suite)
:	[Feature format](feature-format)
:	LINKS TO RELEVANT STANDARDS
:	LINKS TO OTHER DOCUMENTS

**Process impact:** This is a set of detailed feature descriptions.

TODO: For each feature listed in the [feature set](feature-set),
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

### F-00: Site Configuration {#F-00}


Priority:
:	Essential

Effort:
:Days

Risk:
:	Safe

Functional area(s):
:	Administration

Use case(s):
:	[UC-00](use-cases#UC-00) [UC-11](use-cases#UC-11)

Description:</td>
:	The site administrators will be able to configure:

	- The site appearance by choosing a predefined CSS file</li>
	- Whether the site makes new clans public or private by default</li>
	- The email address to be used to send critical error reports</li>

Notes and Questions:
:	NOTE
:	QUESTION

Priority
:	Essential

Effort
:   Days

Risk:
:	Safe

Functional Areas:
:	Administration

Use case(s):
:	UC-00 UC-11

Description:
:	The site administrators will be able to configure:

	-The site appearance by choosing a predefined CSS file
	-Whether the site makes new clans public or private by default
	-The email address to be used to send critical error reports

### F-01: User registration {#F-01-user-registration}

Priority:
:	Essential

Effort:
:	Days

Risk:
:	Safe

Functional area(s):
:	Administration

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	Visitors can come to the site and register themselves. They must provide the following information:

	- username
	- email address (twice to catch typos)
	- real name

Precise Details:
:

	- username must be unique (not equal to any other existing user name)
	- username must be of the form ~~~[a-zA-Z0-9]{2,16}~~~ and is not case sensitive
	- email address must be of the form ~~~[-a-zA-Z0-9_.]{2,16}@[-a-zA-Z0-9_.]{6,64}~~~
	- both entries of the email address must match
	- email address will be verified by sending the user's initial password there
	- real name must not be empty
	- leading and trailing spaces are stripped from all fields

Notes and Questions:
:	NOTE
:	QUESTION


### F-02: FEATURE NAME {#F-02}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION


### F-03: FEATURE NAME {#F-03}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

### F-10: FEATURE NAME {#F-10}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

### F-11: FEATURE NAME {#F-11}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

### F-12: FEATURE NAME {#F-12}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

### F-13: FEATURE NAME {#F-13}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

### F-20: FEATURE NAME {#F-20}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

### F-21: FEATURE NAME {#F-21}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

### F-22: FEATURE NAME {#F-22}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

### F-23: FEATURE NAME {#F-23}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

### F-30: FEATURE NAME {#F-30}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

### F-31: FEATURE NAME {#F-31}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

### F-32: FEATURE NAME {#F-32}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

### F-33: FEATURE NAME {#F-33}

Priority:
:	Essential | Expected | Desired | Optional

Effort:
:	Months | Weeks | Days | Hours

Risk:
:	Dangerous | 3-Risks | 2-Risks | 1-Risk | Safe

Functional area(s):
:	WORD, WORD, WORD

Use case(s):
:	[UC-01](use-cases#UC-01)

Description:
:	1-4 PARAGRAPHS. USE BULLETS OR TABLES TO ORGANIZE INFORMATION. LINK TO WORKSHEETS OR ADDITIONAL INFORMATION.
:
:	Precise Details:
:

	- LOGICAL CONSTRAINT
	- LOGICAL CONSTRAINT

Notes and Questions:
:	NOTE
:	QUESTION

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/features.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional feature specification
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


