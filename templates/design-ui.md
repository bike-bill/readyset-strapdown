[Design](design.html) &gt; User Interface {#design-user-interface}
-----------------------------------------

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

TODO: Answer the questions below to help you design the user interface
features of your system. Some example text is provided. Add or delete
text as needed.

What are the most important facts that a developer should know about the user interface of this system?
:   PARAGRAPH OR BULLETS

What are the ranked goals for the user interface of this system?

:   1.  [Understandability and
        learnability](glossary-std.html#dg_use_understand){.def}
    2.  [Task support and
        efficiency](glossary-std.html#dg_use_efficiency){.def}
    3.  [Safety](glossary-std.html#dg_use_safety){.def}
    4.  [Consistency and
        familiarity](glossary-std.html#dg_use_consistency){.def}

### Metaphors, Exemplars, and Standards {#metaphors-exemplars-and-standards}

What is the central metaphor of this UI design?
:   PARAGRAPH

What existing systems have user interfaces similar to the UI you want to build? What specific aspects are similar?

:   -   [amazon.com](http://www.amazon.com): Our e-commerce site will
        have stores and departments, and search like this site.
    -   [Microsoft
        Office](http://www.microsoft.com/office/using/default.asp): We
        will use configurable toolbars the same way Office 2000 does.
    -   [EXISTING-UI](LINK-TO-SYSTEM): DESCRIPTION

What UI design standards, guidelines, and styles are you following?

:   -   [Microsoft UI
        guidelines](http://msdn.microsoft.com/library/default.asp?url=/library/en-us/dnwue/html/welcome.asp)
    -   [Java UI
        guidelines](http://java.sun.com/products/jlf/ed1/guidelines.html)
    -   [Mac UI
        guidelines](http://developer.apple.com/techpubs/macosx/Essentials/AquaHIGuidelines/AHIGHIGs/index.html)
    -   [W3C Accessibility guidelines](http://www.w3.org/TR/WCAG10/)

### Task Models {#task-models}

What types of users will use this system?
:   See the [user needs document](user-needs.html).

What types of tasks will those users perform?
:   See the [use case suite](use-case-suite.html).

### Content Model / Interaction Contexts {#content-model-interaction-contexts}

TODO: List interaction contexts. Each interaction context is a "place"
where users see information and where they select commands or options.
In a graphical user interface, a interaction context will eventually be
implemented as a window or dialog box. In other applications, an
interaction context may be implemented as, e.g., a web page, a voice
menu prompt, or a physical control panel.

TIP: Each interaction context is an exclusive mode: the user can only
use one interaction context at a time. All the components within one
context are visible and usable at the same time. E.g., if a window has
three tabs, that is three interaction contexts because only one tab can
be used at a time.

TODO: For each interaction context, list the abstract components within
that context. Each component is a piece of information, or a user
interface affordance. In a GUI, each abstract component will eventually
become a widget, but the choice of specific widgets happens later.
Choice of abstract components corresponds to step 2 in the [HTML
prototyping
example](http://www.ics.uci.edu/~jrobbins/htmlproto/index.html)
demonstrated in class.

TIP: Most high frequency use cases should be carried out in only one
interaction contexts. A use case that requires three interaction
contexts could be hard to use. However, interaction contexts with too
many components can also be hard to use.

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th><div>
Interaction Context
</div>
<div>
--Abstract UI Components
</div></th>
<th>Purpose</th>
<th>Contents / Constraints / Behavior</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="LINK-TO-MOCKUP">Login dialog</a></td>
<td>Verify that the current user is actually the person that they claim to be.</td>
<td></td>
</tr>
<tr class="even">
<td>--Prompt</td>
<td>Tell the user that this dialog is to log in.</td>
<td>&quot;Please log in&quot;.</td>
</tr>
<tr class="odd">
<td>--Message area</td>
<td>Give the user some feedback about the login process.</td>
<td>Initially blank. Changes to &quot;Checking username and password&quot; when the user presses &quot;Login&quot;. Changes to &quot;Invalid username or password, please try again&quot;, if login fails.</td>
</tr>
<tr class="even">
<td>--Username</td>
<td>Identify the user account that the current user is trying to access.</td>
<td>The name of the user account. Regex: <code>[-_a-z0-9]{1-16}</code>. The application should not do anything that would help users guess usernames. E.g., this should not be a combo-box with recent users listed, and it should not offer auto-complete.</td>
</tr>
<tr class="odd">
<td>--Password</td>
<td>Verify that the current user knows a secret password that only the true user of that user account should know.</td>
<td>The password of 4-16 characters. Do not display the password on the screen. The application should not do anything that would help users guess passwords.</td>
</tr>
<tr class="even">
<td>--Login</td>
<td>Allow the user to indicate that they have completed entry of their username and password.</td>
<td>&quot;Login&quot; Only enabled when Username != &quot;&quot;. If the username or password is incorrect, delay a few seconds, and then clear all fields.</td>
</tr>
<tr class="odd">
<td>--Lost Password</td>
<td>Allow the current user to start a process of generating a new password for a given username.</td>
<td>&quot;Forgot your password? Click here.&quot; Only enabled when Username != &quot;&quot;.</td>
</tr>
<tr class="even">
<td><a href="LINK-TO-MOCKUP">PAGE-NAME</a></td>
<td>PURPOSE</td>
<td></td>
</tr>
<tr class="odd">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="even">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="odd">
<td><a href="LINK-TO-MOCKUP">PAGE-NAME</a></td>
<td>PURPOSE</td>
<td></td>
</tr>
<tr class="even">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="odd">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="even">
<td><a href="LINK-TO-MOCKUP">MAIN-WINDOW-NAME</a></td>
<td>PURPOSE</td>
<td></td>
</tr>
<tr class="odd">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="even">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="odd">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="even">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="odd">
<td><a href="LINK-TO-MOCKUP">DIALOG-NAME</a></td>
<td>PURPOSE</td>
<td></td>
</tr>
<tr class="even">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="odd">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="even">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="odd">
<td><a href="LINK-TO-MOCKUP">DIALOG-NAME</a></td>
<td>PURPOSE</td>
<td></td>
</tr>
<tr class="even">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="odd">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
<tr class="even">
<td>--ABSTRACT-COMPONENT-NAME</td>
<td>PURPOSE</td>
<td>CONTENTS</td>
</tr>
</tbody>
</table>

### Technical Constraints / Operational Contextualization {#technical-constraints-operational-contextualization}

What are your assumptions about the output devices?
:   We assume that the user has a 17-inch or larger screen with 1024x768
    pixels that can display thousands of colors (16 bit or more). We
    assume basic audio that can play simple sound files.
:   We make very few assumptions about the user's screen or web browser,
    other than the assumption that they can view page somehow. We will
    not use any audio features.
:   This "pay-at-the-pump" system has a 320x200 16-color display and
    can beep.

What are your assumptions about the input devices that you will use?
:   We assume only that the user has a standard keyboard and mouse.
:   This "pay-at-the-pump" system has digits 0-9, "OK", "Cancel", and
    four menu buttons along the right-hand edge of the screen.

What are your assumptions about the amount of time users will spend on tasks?
:   Use cases UC-02 and UC-04 are expected to take a few minutes each.
    Use case UC-00 should take less than 5 seconds each. All other use
    cases should take less than 30 seconds each.

What windowing systems, UI libraries, or other UI technologies will you use?
:   Standard Java Swing with no extra libraries.
:   Simple HTML and CSS with simple GIF images.

### User Interface Checklist {#user-interface-checklist}

TODO: Answer the following questions to help evaluate the design. You
may add or remove questions to fit your project.

#### Understandability and learnability {#understandability-and-learnability}

Are there any labels of icons that are likely to be misunderstood?
:   1-3 SENTENCES

Is the user's current place and state clearly visible? E.g., wizard step 2 of 5, or edit-mode vs. play-mode.
:   1-3 SENTENCES

Are advanced options clearly separated from the most commonly used options?
:   1-3 SENTENCES

Are there no invisible options or commands? E.g., hold down the control key when opening a dialog box to see advanced options.
:   1-3 SENTENCES

#### Task Support and Efficiency {#task-support-and-efficiency}

Which use cases force the user to work through more than two interaction contexts?
:   1-3 SENTENCES

Which use cases force the user to perform slow or difficult UI steps? E.g., entering a long code number like an ISBN. E.g., long mouse-drag operations.
:   1-3 SENTENCES

#### Safety {#safety}

Are there any dangerous or irreversible actions that are done with only one step?
:   1-3 SENTENCES

#### Consistency and Familiarity {#consistency-and-familiarity}

Do UI elements in your system work the same as they do in the existing example systems you identified?
:   1-3 SENTENCES

Do all elements in your system that appear the same, actually function the same?
:   1-3 SENTENCES

Do all elements in your system that appear the same, actually function the same?
:   1-3 SENTENCES

Are all elements share consistent visual characteristics such as font and color scheme, unless there is a reason for them to differ?
:   1-3 SENTENCES

Are labels used consistently throughout the system? E.g., not "forward/back" in some contexts and "next/prev" in others.
:   1-3 SENTENCES

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/design-ui.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional UI design
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


