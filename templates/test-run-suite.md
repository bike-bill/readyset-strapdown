[QA Plan](qa-plan) &gt; Test Run Suite {#qa-plan-test-run-suite}
-------------------------------------------

### Release Information {#release-information}


Project:
:   [PROJECTNAME](index)

Internal Release Number:
:   X.Y.Z

Related Documents:
:   [Test suite](test-suite)
:   LINKS TO RELEVANT STANDARDS
:   LINKS TO OTHER DOCUMENTS


**Process impact:** This is a test run log for manual system testing. A
test run is logged whenever the manual system test suite is carried out.
The log overview helps visualize the set of system configurations that
have been tested and those that have not. Clearly understanding the
degree to which the system has been tested helps to assess progress,
assess risk, and focus ongoing testing efforts.

TODO:
-   Review the [target audience](target-and-benefits),
    [environmental requirements](srs#environmental), and [possible
    deployments](design-architecture#deployment) to understand the
    set of possible system configurations that could be tested.
-   Use a table or list to describe that set of possible configurations.
    Mark each possibility with Pending, N/A, or Waived.
-   Track each test run with an issue in the issue tracker or an item in
    the [test-runs](test-runs) document.
-   Periodically review the set of possible system configurations to
    identify any additional needed test runs.

### Test Runs by Operating System and Browser {#test-runs-by-operating-system-and-browser}

<table>
    <thead>
        <tr>
            <th>OS \ Browser</th>
            <th>IE</th>
            <th>Netscape/Mozilla</th>
            <th>Konqueror/Safari</th>
            <th>other</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Windows</td>
            <td><a href="test-runs#TR-01">Passed</a></td>
            <td><a href="test-runs#TR-02">Passed</a></td>
            <td>N/A</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Linux</td>
            <td>N/A</td>
            <td><a href="test-runs#TR-03">Passed</a></td>
            <td>Pending</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Mac</td>
            <td><a href="test-runs#TR-10">FAILED</a></td>
            <td>Pending</td>
            <td><a href="test-runs#TR-11">Passed</a></td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Palm</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>Pending</td>
        </tr>
    </tbody>
</table>

### Test Runs by Locale {#test-runs-by-locale}

TIP: Use this outline to guide the testing of internationalized
applications. Each locale indicates a native language as well as formats
for presenting money, dates, times, etc.

-   English US: [Passed](test-runs#TR-00)
-   English UK: [Passed](test-runs#TR-01)
-   English CA: [Passed](test-runs#TR-02)
-   Japanese: [Passed](test-runs#TR-10)
-   Spanish: Pending
-   Russian: Pending
-   German: Pending
-   French: Pending
-   French CA: Waived, French + English Canadian is good enough

### Test Runs by Hardware Configuration {#test-runs-by-hardware-configuration}

TIP: Use this outline for products that depend on specific hardware.
E.g., a disk crash recovery product would depend on the type of drive, a
game might depend on processor speed and graphics cards, other products
might depend on memory or other hardware specs.

-   PCs
    -   IDE drive: Pending
    -   EIDE drive: Waived because we only use IDE features
    -   ATA drive: [Passed](test-runs#TR-00)
    -   SCSI drive: [Passed](test-runs#TR-01)
    -   SATA drive: [Passed](test-runs#TR-02)
    -   USB drive: [FAILED](test-runs#TR-03)
-   Macs
    -   EIDE drive: [Passed](test-runs#TR-10)
    -   SCSI drive: [Passed](test-runs#TR-11)
    -   Firewire drive: Pending
    -   USB drive: [FAILED](test-runs#TR-12)

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/test-runs.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional test runs
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


