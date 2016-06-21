[QA Plan](qa-plan.html) &gt; Test Run Suite {#qa-plan-test-run-suite}
-------------------------------------------

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
<a href="test-suite.html">Test suite</a>
</div>
<div>
LINKS TO RELEVANT STANDARDS
</div>
<div>
LINKS TO OTHER DOCUMENTS
</div></td>
</tr>
</tbody>
</table>

**Process impact:** This is a test run log for manual system testing. A
test run is logged whenever the manual system test suite is carried out.
The log overview helps visualize the set of system configurations that
have been tested and those that have not. Clearly understanding the
degree to which the system has been tested helps to assess progress,
assess risk, and focus ongoing testing efforts.

TODO:
-   Review the [target audience](target-and-benefits.html),
    [environmental requirements](srs.html#environmental), and [possible
    deployments](design-architecture.html#deployment) to understand the
    set of possible system configurations that could be tested.
-   Use a table or list to describe that set of possible configurations.
    Mark each possibility with Pending, N/A, or Waived.
-   Track each test run with an issue in the issue tracker or an item in
    the [test-runs](test-runs.html) document.
-   Periodically review the set of possible system configurations to
    identify any additional needed test runs.

### Test Runs by Operating System and Browser {#test-runs-by-operating-system-and-browser}

| OS \\ Browser | IE                             | Netscape/Mozilla               | Konqueror/Safari               | other   |
|---------------|--------------------------------|--------------------------------|--------------------------------|---------|
| Windows       | [Passed](test-runs.html#TR-01) | [Passed](test-runs.html#TR-02) | N/A                            | N/A     |
| Linux         | N/A                            | [Passed](test-runs.html#TR-03) | Pending                        | N/A     |
| Mac           | [FAILED](test-runs.html#TR-10) | Pending                        | [Passed](test-runs.html#TR-11) | N/A     |
| Palm          | N/A                            | N/A                            | N/A                            | Pending |

### Test Runs by Locale {#test-runs-by-locale}

TIP: Use this outline to guide the testing of internationalized
applications. Each locale indicates a native language as well as formats
for presenting money, dates, times, etc.

-   English US: [Passed](test-runs.html#TR-00)
-   English UK: [Passed](test-runs.html#TR-01)
-   English CA: [Passed](test-runs.html#TR-02)
-   Japanese: [Passed](test-runs.html#TR-10)
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
    -   ATA drive: [Passed](test-runs.html#TR-00)
    -   SCSI drive: [Passed](test-runs.html#TR-01)
    -   SATA drive: [Passed](test-runs.html#TR-02)
    -   USB drive: [FAILED](test-runs.html#TR-03)
-   Macs
    -   EIDE drive: [Passed](test-runs.html#TR-10)
    -   SCSI drive: [Passed](test-runs.html#TR-11)
    -   Firewire drive: Pending
    -   USB drive: [FAILED](test-runs.html#TR-12)

TODO: Check for [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/test-runs.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional test runs
template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary

Copyright © 2003-2004 Jason Robbins. All rights reserved. [License
terms](readyset-license.html). Retain this copyright statement whenever
this file is used as a template.


