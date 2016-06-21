[Design](design.html) &gt; Security {#design-security}
-----------------------------------

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

TODO: Answer the questions below to help you design needed security
features. Some example text is provided. Add or delete text as needed.

What are the most important facts that a developer should know about the security of this system?
:   PARAGRAPH OR BULLETS

What are the ranked goals for security in this system?

:   1.  [Data security](glossary-std.html#dg_data_security){.def}
    2.  [Intrusion prevention](glossary-std.html#dg_no_intrusion){.def}
    3.  [Abuse prevention](glossary-std.html#dg_no_abuse){.def}
    4.  [Auditability](glossary-std.html#dg_auditability){.def}

### Security Mechanisms {#security-mechanisms}

What physical security mechanisms will be used?

:   -   Servers will be kept in a locked room with door code known only
        to administrators.
    -   Servers will be kept in a locked equipment rack.
    -   Server case itself has a security cable that prevents the case
        from being opened (so the hard-disk with sensitive data cannot
        be removed).
    -   Backup tapes are stored in a locked cabinet in a locked room.

What network security mechanisms will be used?

:   -   A firewall device limits access to specific network ports (e.g.,
        port 80 for web server access).
    -   Firewall software limits access to specific network ports (e.g.,
        port 80 for web server access).
    -   Only the front-end machines are accessible over the Internet.
        Other machines in the server cluster communicate over a private
        LAN only.
    -   Users can only connect to the server from specific ranges of
        IP-address (e.g., university-owned computers in networks
        on campus).
    -   Certain users (e.g., administrators) can only connect from
        specific ranges of IP-addresses.
    -   All network communication takes place over a virtual private
        network (VPN) that is encrypted and not accessible to outsiders.
    -   All network communication takes place over a LAN that does not
        have any connections to the Internet.

What operating system security will be used?

:   -   Operating system user accounts will never be created on the
        servers, other than those needed by the application itself.
    -   Different components in the application execute as different
        operating system users, have only the least possible privileges,
        and may only access the particular files needed by
        that component.
    -   Operating system permissions on files and directories are set to
        prevent undesired access or modification.
    -   Intrusion detection software will be used on the server to
        detect any modifications made by hackers.
    -   Administrators will monitor security mailing lists for
        announcements of security holes in any components that we use
        and security patches and upgrades will be applied quickly.
    -   Data on disks and backup tapes is stored using an encrypted file
        system so that the data is protected if the media itself is
        stolen or somehow accessed.

What application security mechanisms will be used?

:   -   Values input into every field are validated before use
    -   Usernames and passwords are required for access
    -   Passwords are stored encrypted
    -   Verification of user email address
    -   The quality of passwords is checked
    -   Users must have certificate files on their client machine before
        they can connect to the server
    -   Users must have physical security tokens (e.g., hasp, dongle,
        smartcard, or fingerprint reader)
    -   Users are given roles that define their permissions. Those roles
        are:
        -   Guest: Visitor to the site is not logged in, no permissions
            to change anything
        -   Guest: Visitor to the site is not logged in, can post
            messages anonymously
        -   RegisteredUser: User is logged in, has permissions for X, Y,
            and Z
        -   Administrator: Permission to change anything, even on behalf
            of other regular users
    -   Each action (information display or change) requires that the
        user has a role with proper permissions
    -   Compromised or abused accounts can be quickly disabled
        by administrators.
    -   Administrators can review user permissions
    -   Administrators can audit all accesses and changes
    -   All communications with the user are encrypted (e.g., SSL)
    -   Some communications with the user (e.g., the username
        and password) are encrypted (e.g., SSL)
    -   Sessions are tied to a particular client IP-address so that
        stolen cookies cannot be used.
    -   Session cookies are long random strings that cannot be guessed.
    -   Sessions time out so that unattended terminals cannot be abused.
    -   Actions that seem to destroy data actually move it to a place
        where it can still be reviewed by administrators.
    -   Sensitive data, such as credit card numbers, are processed but
        not retained in any database or file
    -   The data access layer will be responsible for preventing SQL
        injection attacks (i.e., hackers attempting to enter SQL
        statements through application UI fields).
    -   The data access layer will allow read-only connections, which
        will be used for most requests, as well as write connections for
        requests that update the database.
    -   The HTML generation layer will be responsible for preventing
        cross-site-scripting (XSS) attacks.
    -   The application will prevent CSRF attacks. It will do this by
        performing updates to the database only after a POST, and
        checking that the referring page was served by the system for
        every POST. Browsers that do not report HTTP-Referrer will not
        be supported.

### Security Checklist {#security-checklist}

Protection of data: To what extent has this been achieved?
:   2-4 SENTENCES

Prevention of intrusion: To what extent has this been achieved?
:   2-4 SENTENCES

Prevention of abuse: To what extent has this been achieved?
:   2-4 SENTENCES

Accountability/auditing: To what extent has this been achieved?
:   2-4 SENTENCES

Have these security mechanisms been communicated to the development team and other stakeholders?
:   Yes, everyone understands. Feedback is welcome.
:   No, this is a risk that is noted in the [Risk
    Management](plan.html#risks) section.

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/design-security.html)
and discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional security design
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


