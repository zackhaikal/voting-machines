# voting-machines
A repo for exploring the software quality of electronic voting machines

This repository provides a breakdown of the software validation process as performed to certify electronic voting equipment. Each device's Certificate of Conformance and Final Test Report are included in the appropriate folder, organized by manufacturer. These reports are provided for convenience; copyright on these documents remains unchanged, and no guarantee is made that these documents are current.

## A Summary of the Software Review Process for all Certified Electronic Voting Systems

The comments here are not consistent per se; they are the nearest brief synopsis of the test procedure described in the Source Code Review section of the test reports.

This information is public and can be found on [the Testing and Certification Program page](https://www.eac.gov/testing_and_certification/default.aspx) of [the Election Assistance Commission's website](https://www.eac.gov/default.aspx).

| Manufacturer | Device Name            | Standard  | Test Lab                | Certification Date | Software Review Comments                                        |
|--------------|------------------------|-----------|-------------------------|--------------------|-----------------------------------------------------------------|
| Dominion     | Democracy Suite 4.0    | VVSG 2005 | NTS Huntsville          | 10-May-12          | Style guide validation using Beyond Compare and Crimson Editor  |
| Dominion     | Democracy Suite 4.14   | VVSG 2005 | NTS Huntsville          | 7-Jul-13           | Style guide validation using Beyond Compare and Crimson Editor  |
| Dominion     | Democracy Suite 4.14a  | VVSG 2005 | NTS Huntsville          | 20-Sep-13          | Software testing deemed not necessary                           |
| Dominion     | Democracy Suite 4.14a1 | VVSG 2005 | NTS Huntsville          | 16-Jun-14          | Software compared to previous revision and verified unchanged   |
| Dominion     | Democracy Suite 4.14b  | VVSG 2005 | NTS Huntsville          | 7-Jan-14           | Style guide validation using Beyond Compare and Crimson Editor  |
| Dominion     | Democracy Suite 4.14d  | VVSG 2005 | NTS Huntsville          | 25-Nov-14          | Validated styles in 6 code modules                              |
| Dominion     | Democracy Suite 4.14e  | VVSG 2005 | NTS Huntsville          | 2-Jul-15           | Validated styles in 3 code modules                              |
| Dominion     | Assure 1.3             | VSS 2002  | SLI Compliance          | 29-Jun-12          | Reviewed 141 LOC for VVSG 2005 formatting, delta from previous rev |
| ES&S         | EVS 5.0.0.0            | VVSG 2005 | NTS Huntsville          | 16-May-13          | Style guide validation using Beyond Compare and Crimson Editor, manual visual scan, evaluation against mfg supplied coding standards |
| ES&S         | EVS 5.0.1.0            | VVSG 2005 | NTS Huntsville          | 18-Mar-14          | Style guide validation using Beyond Compare and Crimson Editor, manual visual scan, evaluation against mfg supplied coding standards" |
| ES&S         | EVS 5.2.0.0            | VVSG 2005 | NTS Huntsville          | 2-Jul-14           | Style guide validation using Beyond Compare and Crimson Editor, manual visual scan of non-java code, review of 10% of comments and headers, evaluation against mfg supplied coding standards | 
| ES&S         | EVS 5.2.0.3            | VVSG 2005 | NTS Huntsville          | 5-Aug-15           | Compared to ver 5.2.0.0 and evaluated against style guide       |
| ES&S         | EVS 5.2.0.4            | VVSG 2005 | NTS Huntsville          | 27-Apr-16          | Compared to ver 5.2.0.3 and evaluated against style guide, 291 LOC modified |
| ES&S         | EVS 5.2.1.0            | VVSG 2005 | NTS Huntsville          | 18-Dec-15          | Code from v 5.2.0.2 and 5.3.0.0-IL used for review | 
| ES&S         | EVS 5.2.1.1            | VVSG 2005 | NTS Huntsville          | 15-Jul-16          | Reviewed for adherence to style guide | 
| ES&S         | Unity 3.2.0.0          | VSS 2002  | NTS Huntsville          | 16-May-12          | Visual scan                                                     |
| ES&S         | Unity 3.2.1.0          | VSS 2002  | NTS Huntsville          | 29-Mar-11          | Functionality and regression tests following anomaly            |
| ES&S         | Unity 3.4.0.0          | VSS 2002  | NTS Huntsville          | 31-Oct-12          | Visual scan                                                     |
| ES&S         | Unity 3.4.1.0          | VSS 2002  | NTS Huntsville          | 4-Apr-14           | Style guide validation using Beyond Compare and Crimson Editor, manual visual scan, evaluation against mfg supplied coding standards |
| ES&S         | Unity 3.4.1.4          | VVSG 2005 | NTS Huntsville          | 26-Aug-16          | Reviewed 1552 LOC for style adherence                           |
| ES&S         | Assure 1.2             | VSS 2002  | iBeta Quality Assurance | 6-Aug-09           | Reviewed 3% of code, focused on functions that handle vote data, audits, reporting |
| Hart         | Verity 1.0             | VVSG 2005 | SLI Compliance          | 12-May-15          | Verified modularity, integrity, and style |
| Hart         | Verity 2.0             | VVSG 2005 | SLI Compliance          | 27-Apr-16          | Verified modularity, integrity, and style |
| MicroVote    | EMS 4.0                | VVSG 2005 | iBeta Quality Assurance | 6-Feb-09           | Verified for standards compliance |
| MicroVote    | EMS 4.0b               | VVSG 2005 | NTS Huntsville          | 23-Aug-10          | Verified for standards compliance |
| MicroVote    | EMS 4.1                | VVSG 2005 | NTS Huntsville          | 16-Jul-15          | Compared to 4.0B baseline and reviewed for adherence |
| Unisyn       | OpenElec 1.0           | VVSG 2005 | NTS Huntsville          | 13-Jan-10          | Adherence review, peer review of 10% of codebase |
| Unisyn       | OpenElec 1.0.1         | VVSG 2005 | NTS Huntsville          | 21-Jul-11          | Compared to 1.0 baseline, visual review of changes |
| Unisyn       | OpenElec 1.1           | VVSG 2005 | NTS Huntsville          | 9-Apr-12           | Visual scan of every line for compliance |
| Unisyn       | OpenElec 1.2           | VVSG 2005 | NTS Huntsville          | 23-Dec-13          | "Validation using Eclipse and Checkstyle, 10% manual review of headers and comments |
| Unisyn       | OpenElec 1.3           | VVSG 2005 | NTS Huntsville          | 12-Jan-15          | "Validation using Eclipse and Checkstyle, 10% manual review of headers and comments |
