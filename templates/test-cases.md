[QA Plan](qa-plan) &gt; [Test Suite](test-suite) &gt; Test Cases {#qa-plan-test-suite-test-cases}
--------------------------------------------------------------------------

### Release Information {#release-information}

Project:
:   [PROJECTNAME](index)

Internal Release Number:
:   X.Y.Z

Related Documents:
:   [System test case format](test-case-format)
:   LINKS TO RELEVANT STANDARDS
:   LINKS TO OTHER DOCUMENTS

### login-1: Normal User Login {#login-1-normal-user-login}

Purpose:
:   Test that users can log in with the proper username or email address and their password.

Prereq:
:   User is not already logged in.
:	User testuser exists, and account is in good standing.

Test Data:
:   usernameOrEmail = {testuser, bogususer, testuser@nospam.com, test@user@nospam.com, empty}
:	password = {valid, invalid, empty}

Steps:
:   Steps to carry out the test. See step formating rules below.

:   - visit LoginPage
    - enter userID
    - enter password
    - click login
    - see the terms of use page
    - click agree radio button at page bottom
    - click submit button
    - see PersonalPage
    - verify that welcome message is correct username

Notes and Questions:
 
:   - This assumes that user has not agreed to terms-of-use already.
	- Does this work without browser cookies?

### login-2: Locked-out User Login {#login-2-locked-out-user-login}

Purpose:
:   Test that a user who has been locked out by a moderator, cannot log in, They should see a message indicating that they were locked out.

Prereq:
:   User is not already logged in.
:	User testuser2 exists, and has been locked out


Test Data:
:   usernameOrEmail = {testuser2, testuser2@nospam.com}
:	password = {valid}
   
Steps:
:   Steps to carry out the test. See step formating rules below.

:   - visit LoginPage
	- enter usernameOrEmail
	- enter password
	- click Login
	- see LoginPage
	- verify warning message is the locked-out message

Notes and Questions:
 
:    - Does this work without browser cookies?

### unique-test-case-id1: Test Case Title {#unique-test-case-id1-test-case-title}

Purpose:
:   Short sentence or two about the aspect of the system is being tested. If this gets too long, break the test case up or put more information into the feature descriptions.

Prereq:
:   Assumptions that must be met before the test case can be run. E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;, &quot;user testuser exists&quot;.

Test Data:
:   List of variables and their possible values used in the test case. You can list specific values or describe value ranges. The test case should be performed once for each *combination* of values. These values are written in set notation, one per line. E.g.:

    - loginID = {Valid loginID, invalid loginID, valid email, invalid email, empty}
    - password = {valid, invalid, empty}

Steps:
:   Steps to carry out the test. See step formating rules below.

:   - visit LoginPage
    - enter userID
    - enter password
    - click login
    - see the terms of use page
    - click agree radio button at page bottom
    - click submit button
    - see PersonalPage
    - verify that welcome message is correct username

Notes and Questions:

:   - NOTE
    - QUESTION

### unique-test-case-id2: Test Case Title {#unique-test-case-id2-test-case-title}

Purpose:
:   Short sentence or two about the aspect of the system is being tested. If this gets too long, break the test case up or put more information into the feature descriptions.

Prereq:
:   Assumptions that must be met before the test case can be run. E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;, &quot;user testuser exists&quot;.

Test Data:
:   List of variables and their possible values used in the test case. You can list specific values or describe value ranges. The test case should be performed once for each *combination* of values. These values are written in set notation, one per line. E.g.:

    - loginID = {Valid loginID, invalid loginID, valid email, invalid email, empty}
    - password = {valid, invalid, empty}

Steps:
:   Steps to carry out the test. See step formating rules below.

:   - visit LoginPage
    - enter userID
    - enter password
    - click login
    - see the terms of use page
    - click agree radio button at page bottom
    - click submit button
    - see PersonalPage
    - verify that welcome message is correct username

Notes and Questions:
:
 
:   - NOTE
    - QUESTION

### unique-test-case-id3: Test Case Title {#unique-test-case-id3-test-case-title}

Purpose:
:   Short sentence or two about the aspect of the system is being tested. If this gets too long, break the test case up or put more information into the feature descriptions.

Prereq:
:   Assumptions that must be met before the test case can be run. E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;, &quot;user testuser exists&quot;.

Test Data:
:   List of variables and their possible values used in the test case. You can list specific values or describe value ranges. The test case should be performed once for each *combination* of values. These values are written in set notation, one per line. E.g.:

    - loginID = {Valid loginID, invalid loginID, valid email, invalid email, empty}
    - password = {valid, invalid, empty}

Steps:
:   Steps to carry out the test. See step formating rules below.

:   - visit LoginPage
    - enter userID
    - enter password
    - click login
    - see the terms of use page
    - click agree radio button at page bottom
    - click submit button
    - see PersonalPage
    - verify that welcome message is correct username

Notes and Questions:
:
 
:   - NOTE
    - QUESTION

### unique-test-case-id4: Test Case Title {#unique-test-case-id4-test-case-title}

Purpose:
:   Short sentence or two about the aspect of the system is being tested. If this gets too long, break the test case up or put more information into the feature descriptions.

Prereq:
:   Assumptions that must be met before the test case can be run. E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;, &quot;user testuser exists&quot;.

Test Data:
:   List of variables and their possible values used in the test case. You can list specific values or describe value ranges. The test case should be performed once for each *combination* of values. These values are written in set notation, one per line. E.g.:

    - loginID = {Valid loginID, invalid loginID, valid email, invalid email, empty}
    - password = {valid, invalid, empty}

Steps:
:   Steps to carry out the test. See step formating rules below.

:   - visit LoginPage
    - enter userID
    - enter password
    - click login
    - see the terms of use page
    - click agree radio button at page bottom
    - click submit button
    - see PersonalPage
    - verify that welcome message is correct username

Notes and Questions:
 
:   - NOTE
    - QUESTION

### unique-test-case-id5: Test Case Title {#unique-test-case-id5-test-case-title}

Purpose:
:   Short sentence or two about the aspect of the system is being tested. If this gets too long, break the test case up or put more information into the feature descriptions.

Prereq:
:   Assumptions that must be met before the test case can be run. E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;, &quot;user testuser exists&quot;.

Test Data:
:   List of variables and their possible values used in the test case. You can list specific values or describe value ranges. The test case should be performed once for each *combination* of values. These values are written in set notation, one per line. E.g.:

    - loginID = {Valid loginID, invalid loginID, valid email, invalid email, empty}
    - password = {valid, invalid, empty}

Steps:
:   Steps to carry out the test. See step formating rules below.

:   - visit LoginPage
    - enter userID
    - enter password
    - click login
    - see the terms of use page
    - click agree radio button at page bottom
    - click submit button
    - see PersonalPage
    - verify that welcome message is correct username

Notes and Questions:
 
:   - NOTE
    - QUESTION

### unique-test-case-id6: Test Case Title {#unique-test-case-id6-test-case-title}

Purpose:
:   Short sentence or two about the aspect of the system is being tested. If this gets too long, break the test case up or put more information into the feature descriptions.

Prereq:
:   Assumptions that must be met before the test case can be run. E.g., &quot;logged in&quot;, &quot;guest login allowed&quot;, &quot;user testuser exists&quot;.

Test Data:
:   List of variables and their possible values used in the test case. You can list specific values or describe value ranges. The test case should be performed once for each *combination* of values. These values are written in set notation, one per line. E.g.:

    - loginID = {Valid loginID, invalid loginID, valid email, invalid email, empty}
    - password = {valid, invalid, empty}

Steps:
:   Steps to carry out the test. See step formating rules below.

:   - visit LoginPage
    - enter userID
    - enter password
    - click login
    - see the terms of use page
    - click agree radio button at page bottom
    - click submit button
    - see PersonalPage
    - verify that welcome message is correct username

Notes and Questions:
 
:   - NOTE
    - QUESTION

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/test-runs.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional test case
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.
