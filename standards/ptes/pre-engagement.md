# 1 Pre-engagement

## Main questions

### Objectives

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Why is the customer requesting a pentest? | |
| | | Is the test required for compliance? | |
| | | What happens if/after a system is compromised? | |

### Scope: IPs

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | How many IPs are being tested? | |

### Scope: web applications

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | How many web apps are being tested? | |
| | | Is static analysis expected? | |
| | | How many dynamic / static web pages? | |

### Scope: networks

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | How many networks (wifi) are being tested? | |
| | | Is the data transmitted in scope? (health, business data) | |

### Threats: Social engineering

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | List email addresses | |
| | | List phone numbers | |
| | | Are the emails / phones business? | |

### Threats: data

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | What data is most critical? (when exposed) | |
| | | Are there procedures in place in case of disaster? | |
| | | How often do you backup? | |

### Controls

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Are there validation / protection / monitoring processes? | |
| | | Are there fragile systems? (to avoid) | |

### Authority

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Is the manager aware that a test is performed? | |
| | | Are there systems that are leased / not owned? | |

## Metrics for time estimation

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Consider: tester mileage, size of scope, type of tests | |
| | | Check the disponibility of the actual testers | |

methods:
- comparing to previous work / experience
- top/down approach
- bottom/up approach
- model estimation

## Goals

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Compliance should not be the main goal | |
| | | The client should already have a mature security policy in place | |
| | | Vulnerability analysis & hardening come before pentesting | |

## Non-disclosure agreement

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Specify time period | |
| | | Seek legal advice | |

## Establishing lines of communication


### Means of communications

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Contact information is available for all parties in the test scope | |
| | | These informations are shared with everyone on the list | |
| | | Secured communication channels for messaging and data | |
| | | Encrypt all means of communication | |

### Shared informations

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Full name | |
| | | Title and operational responsibility | |
| | | Authorization to discuss details of the testing activities | |
| | | Two forms of 24/7 immediate contact | |
| | | One form of secure communication and data transfer | |

### Parties involved

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | All testers | |
| | | The managers of the test group | |
| | | Two technical staff from the customer | |
| | | One upper management of business contact from the customer | |

### Incident reporting

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Notify the security team of the upcoming pentesting | |
| | | Discuss the modalities of incident reporting | |

### Status reports

## Scoping

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Agree on a status reporting frequency | |
| | | Report planning changes if any | |
| | | Report on progress | |
| | | Report problems | |

### Meeting

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Agenda for the meeting & concret objectives | |
| | | Explain legal ramifications for out-of-scope attacks | |
| | | Explain business implications of unwanted attacks | |
| | | Assertain everyone understands well-defined scoping is critical | |
| | | List all the client's assets | |
| | | Test the staff? Physical or remote? | |
| | | Test the hardware / infrastructure? | |
| | | Test the networks? | |
| | | Test web-apps? | |
| | | Rank the assets by criticality | |
| | | Size according to available workforce too | |
| | | In / out of scope | |
| | | Review with the client | |
| | | List excluded work: retesting, additional tests | |

### Business considerations

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Warn about downtime | |
| | | Explore the implications of downtime on each asset | |
| | | Agenda for the meeting & concret objectives | |

### Legal considerations

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Sign the non-disclosure agreement first | |
| | | Verify legal limitations in the area | |
| | | Verify third party contracts | |
| | | Check the dates of the permission to test | |
| | | Check the authority of the approver (owner) | |
| | | Check whether the actual testers are approved | |
| | | Seek approval from superiors | |
| | | Have any engagement countersigned | |
| | | Be specific: dates, staff, scope, attacks | |
| | | Ask for permission for: infrastructure, software, data | |
| | | Verify ownership of each item of the scope | |
| | | No active operations until the scope is defined, verified, | |

### Creep

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Put additional work at the end | |
| | | Sign the non-disclosure agreement first | |

### Internal

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Check who has authority on the assets | |

- same as external:
  - document
  - don't make assumptions based on your understanding
  - communicate with authoritative personel
  - coordinate

### Third parties

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Detail the actions planned | |
| | | Get specific, signed permission | |
| | | Establish a communication channe l | |
| | | Give advance notice: time period, specific target | |
| | | Always question permissions / ownership | |

Could be:
- ISP
- MSP MSSP
- cloud provider
- software vendor
- marketing agency

## Attacks

### Social engineering

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Target specifically authorized phone numbers / people | |
| | | Verify the phones / emails are company owned| |
| | | List acceptable attacks | |
| | | Ask for specific permissions(\*) | |
| | | Validate phishing email templates | |

\* getting angry, impersonating, swearing, etc

### DoS

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Check the client's understanding of DoS | |
| | | Check the tolerance for downtime | |
| | | Have an objective which distinctly requires DoS attacking (\*)| |

\* testing the load balencing, recovery systems for example

## Additional support

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Check for signed permission | |
| | | Require a contractual addition, countersigned | |
| | | Additional work is performed AFTER completion | |
| | | Make sure management & testers don't cross the boundaries | |

like:
- additional testing
- assistance in remediation
- explaining findings / remediation
- re-testing after remediation
- additional meetings with vendors / shareholders / etc

## Rules of engagement

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Identify data handling limitations and protections | |
| | | Report illegal data to law enforcement immediately | |
| | | Encrypt all the customer's data | |
| | | Sanitize test machines before engagement | |
| | | Never reuse reports for another customer (\*) | |
| | | Define the time of day when attacking is authorized | |
| | | IF reporting is evaluated | |
| | | Otherwise notify the security team | |
| | | Sign a permission to test | |

\* as a template, for marketing...

## Timing

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Can you test all the scope in time? | |
| | | Set a start date | |
| | | Set an end date | |
| | | Actually set an agenda / schedule | |
| | | Make time for the actual outcome/reporting | |
| | | Validate & size according to an agreed-on level of details | |
| | | Add 20% padding | |
| | | Bound time phases with drop dead dates | |
| | | Bound technical work with a scope | |
| | | Bound reporting & deliverables with specifications | |
| | | Explicitely state the work excluded (remediation, asset) | |
| | | If included perform retesting AFTER completion | |

## Payment terms

| # | ID | Description | Ok |
| -- | -------- | ---------------------- | - |
| | | Specify the completion terms | |
| | | Define when the payment is due | |
| | | Write explicitly the discount | |
| | | Detail the work / volume that justify the price | |
| | | Specify how/what expanses are accounted for | |
| | | Also specify what is not included in the agreement | |
| | | Explicitely choose between fixed & hourly rates | |
| | | Match the work / scope with budget | |
| | | Specify terms for additional work | |

## References

[ptes-pre-engagement]: http://www.pentest-standard.org/index.php/Pre-engagement
[un-cybercrime-precedents]: https://sherloc.unodc.org/
