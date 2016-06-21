Implementation Notes {#implementation-notes}
--------------------

### Product Release Information {#product-release-information}

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
<td>Release(s)</td>
<td>X.Y.Z</td>
</tr>
<tr class="odd">
<td>Related Documents:</td>
<td><div>
<a href="srs.html">Software Requirements Specification</a>
</div>
<div>
<a href="release-notes.html">Release notes</a>
</div>
<div>
<a href="faq.html">FAQ</a>
</div>
<div>
<a href="glossary.html">Glossary</a>
</div></td>
</tr>
</tbody>
</table>

**Process impact:** This document is a brief and fairly technical
discussion of how the system works under ideal conditions. It is also
known as a "theory of operation" document. It should describe key
algorithms, technology dependencies, and operational issues. Much of the
content of this document can be drawn from design documents. This
document will be used by the QA, technical support, and operations
groups. The goal is to give those groups the information they need to
understand, manage, or begin to troubleshoot the system (i.e., recognize
certain behavior as normal or abnormal). If significantly more
information is needed, it should be organized into a larger "operations
guide".

### Type of Implementation {#type-of-implementation}

TODO: Fill in information that will help other engineers understand this
system at-a-glance. Feel free to use relevant technical terms and name
specific technology platforms.

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Type of system:</td>
<td><div class="sample1">
Desktop GUI application
</div>
<div class="sample2">
Unix-style command
</div>
<div class="sample3">
Server-side web application
</div>
<div class="sample4">
Web service
</div>
<div class="sample1">
Client-side applet
</div>
<div class="sample2">
Embedded application
</div>
<div class="sample3">
Reusable library
</div>
<div class="sample4">
Reusable class framework
</div>
<div class="sample1">
Browser Plug-in
</div></td>
</tr>
<tr class="even">
<td>Programming Language(s):</td>
<td><div class="sample1">
Java
</div>
<div class="sample2">
Perl, Unix shell scripts
</div></td>
</tr>
<tr class="odd">
<td>Data Storage:</td>
<td><div class="sample1">
Flat files using XML
</div>
<div class="sample2">
Flat files using Java properties file format
</div>
<div class="sample3">
Flat files using Java object serialization format
</div>
<div class="sample4">
SQL database: MySQL
</div></td>
</tr>
<tr class="even">
<td>UI Technologies:</td>
<td><div class="sample1">
Java Swing
</div>
<div class="sample2">
XHTML, CSS, JavaScript
</div></td>
</tr>
<tr class="odd">
<td>Security Technologies:</td>
<td><div class="sample1">
Authentication: None needed
</div>
<div class="sample2">
Authentication: Local username and password file
</div>
<div class="sample3">
Authentication: LDAP
</div>
<div class="sample4">
Authorization: Operating system file ownership and read-write-execute flags
</div>
<div class="sample1">
Authorization: Access control lists
</div>
<div class="sample2">
Encryption: None needed
</div>
<div class="sample3">
Encryption: SSL
</div></td>
</tr>
</tbody>
</table>

### Runtime Environment {#runtime-environment}

TODO: List and describe runtime objects that make up a running system.
These objects may be referred to by name in the sections below.

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Processes:</td>
<td><div class="sample1">
Main application process
</div>
<div class="sample2">
Client and server processes
</div>
<div class="sample3">
Cron tasks
</div>
<div class="sample4">
Operating system services or drivers
</div></td>
</tr>
<tr class="even">
<td>Configuration Files:</td>
<td><div>
PRODUCTNAME.conf: stores application configuration in Java properties file format.
</div>
<div>
Section of httpd.conf: configures components of the Apache webserver
</div></td>
</tr>
<tr class="odd">
<td>Database Tables:</td>
<td><div>
TABLE_ONE: Each row represents a ...
</div>
<div>
TABLE_TWO: Each row represents a ...
</div>
<div>
TABLE_THREE: Each row represents a ...
</div>
<div>
See the <a href="design-persistence.html">persistence design document</a>.
</div></td>
</tr>
<tr class="even">
<td>Data files:</td>
<td><div>
*.ext: Data files saved by the user on their local hard disk.
</div>
<div>
/var/PRODUCTNAME/upload-XXXX.dat: Files uploaded to the server.
</div></td>
</tr>
<tr class="odd">
<td>Temporary files:</td>
<td><div>
/tmp/PRODUCTNAME.pid: Process ID of the currently running server process.
</div>
<div>
/tmp/upload-XXXX.dat: Files uploaded to the server before they are processed.
</div></td>
</tr>
<tr class="even">
<td>Log files:</td>
<td><div>
error.log: Serious errors are put in the normal Apache error log. Must be writable by Unix user <code>httpd</code>.
</div>
<div>
PRODUCTNAME.log: Messages indicating the progress of normal operations and some errors. Must be writable by Unix user <code>httpd</code>.
</div>
<div>
Log files are rotated nightly. Old logs are archived in ANOTHER LOCATION.
</div></td>
</tr>
</tbody>
</table>

### Implementation of Specific Features {#implementation-of-specific-features}

TODO: Write short descriptions of interesting or unexpected algorithms,
limiting assumptions, or any other implementation detail that will
impact the work of other groups. E.g., long-running operations that must
not be interrupted. E.g., start up or shutdown scripts that are
automatically run by the operating system.

-   **Feature name:** 1-3 SENTENCE DESCRIPTION
-   **Feature name:** 1-3 SENTENCE DESCRIPTION
-   **Feature name:** 1-3 SENTENCE DESCRIPTION
    -   DETAILS
    -   DETAILS
    -   DETAILS
-   **Feature name:** 1-3 SENTENCE DESCRIPTION
    -   DETAILS
    -   DETAILS
    -   DETAILS

### Operational Procedures {#operational-procedures}

TODO: Briefly describe procedures that should be followed by operations
engineers when the system is being run in an ASP production environment.

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Install:</td>
<td>See the <a href="install.html">Installation guide</a></td>
</tr>
<tr class="even">
<td>Upgrade:</td>
<td>See the <a href="install.html">Installation guide</a></td>
</tr>
<tr class="odd">
<td>Start Server:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="even">
<td>Stop Server:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="odd">
<td>Reload Config Files:</td>
<td><ol>
<li>STEP</li>
<li>STEP</li>
<li>STEP</li>
</ol></td>
</tr>
<tr class="even">
<td>Monitor Activity:</td>
<td>Watch the PRODUCTNAME.log and error.log.</td>
</tr>
<tr class="odd">
<td>Periodic Cleanup:</td>
<td>On rare occasion, /tmp/upload-XXXX.dat files can be left behind. Any such files that are more than a day old can safely be removed.</td>
</tr>
</tbody>
</table>

### Security {#security}

TODO: Write notes on security to help operations engineers keep the
system secure while it is in operation.

We take the following precautions to make the system secure:

-   STEP
-   STEP
-   STEP

The security of the system depends on the following external factors:

-   STEP
-   STEP
-   STEP

### Performance and Scalability {#performance-and-scalability}

TODO: Write notes on performance and scalability to help operations
engineers operate the system efficiently.

NOTES ON PERFORMANCE.

NOTES ON SCALABILITY.

### Implementation Notes Checklist {#implementation-notes-checklist}

Do these implementation notes provide enough information for operations engineers?
:   Yes, these notes have been reviewed by the operations team and
    requested changes have been incorporated.
:   No, these notes only summarize parts of a larger [operations
    manual](LINK-TO-OPERTIONS-MANUAL).
:   No, a member of the development team is available on-call whenever
    the operations team may need help. This is listed in the [Resource
    Needs](resource-needs.html) document and in the [on-call
    schedule](LINK-TO-ON-CALL-SCHEDULE).

Have these implementation notes been communicated to the operations and development teams and other stakeholders?
:   Yes, everyone has had a chance to review them. Feedback is welcome.
:   Yes, it has been posted to the project website.
:   No, some developers or operations engineers are not aware of
    this document. This is a risk that is noted in the [Risk
    Management](plan.html#risks) section of the [Project
    Plan](plan.html).

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/implementation-notes.html)
and discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional implementation notes
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


