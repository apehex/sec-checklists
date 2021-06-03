# Questionnaires

## Objectives

| Description                                                            | Ok |
| ---------------------------------------------------------------------- | -- |
| Why is the customer requesting a pentest? | |
| Is the test required for a specific compliance requirement? | |
| When does the customer want the active operations conducted? | |

## Networks

| Description                                                            | Ok |
| ---------------------------------------------------------------------- | -- |
| How many IPs are being tested? | |
| Are the firewalls, IDS, WAF, load balancers? | |
| What happens if / after a system is compromised? | |
| &rarr; Perform a local vulnerability assessment on the compromised machine? | |
| &rarr; Attempt to gain the highest privileges? | |
| &rarr; Perform no, minimal, dictionary, or exhaustive password attacks? | |
| Is the data transmitted in scope? (\*) | |

## Wireless

| Description                                                            | Ok |
| ---------------------------------------------------------------------- | -- |
| How many wireless networks are in place? | |
| Is a guest wireless network used? If so: | |
| &rarr; Does the guest network require authentication? | |
| &rarr; What type of encryption is used on the wireless networks? | |
| &rarr; What is the square footage of coverage? | |
| &rarr; Will enumeration of rogue devices be necessary? | |
| &rarr; Will the team be assessing wireless attacks against clients? | |
| Approximately how many clients will be using the wireless network? | |

\* health, business, personal data for example

## Web applications

| Description                                                            | Ok |
| ---------------------------------------------------------------------- | -- |
| How many web applications are being assessed? | |
| How many login systems are being assessed? | |
| How many static pages are being assessed? (approximate) | |
| How many dynamic pages are being assessed? (approximate) | |
| Will the source code be made readily available? | |
| Will there be any kind of documentation? | |
| Will static analysis be performed on this application? | |
| Does the client want fuzzing performed against this application? | |
| Does the client want role-based testing performed against this application? | |
| Does the client want credentialed scans of web applications performed? | |

## Physical penetration testing

| Description                                                            | Ok |
| ---------------------------------------------------------------------- | -- |
| How many locations are being assessed? | |
| Is this physical location a shared facility? If so: | |
| &rarr; How many floors are in scope? | |
| &rarr; Which floors are in scope? | |
| Are there any security guards that will need to be bypassed? If so: | |
| &rarr; Are the security guards employed through a 3rd party? | |
| &rarr; Are they armed? | |
| &rarr; Are they allowed to use force? | |
| How many entrances are there into the building? | |
| Is the use of lock picks or bump keys allowed? (also consider local laws) | |
| Is the purpose of this test to verify compliance or for performing an audit? | |
| What is the square footage of the area in scope? | |
| Are all physical security measures documented? | |
| Are video cameras being used? | |
| &rarr; Are the cameras client-owned? If so: | |
| &rarr; Should the team attempt to gain access to the video camera data? | |
| Is there an armed alarm system being used? If so: | |
| &rarr; Is the alarm a silent alarm? | |
| &rarr; Is the alarm triggered by motion? | |
| &rarr; Is the alarm triggered by opening of doors and windows? | |

## Social engineering

| Description                                                            | Ok |
| ---------------------------------------------------------------------- | -- |
| List the target email addresses | |
| List the target phone numbers | |
| Are the emails / phones company owned? | |
| Is the purpose of gaining unauthorized physical access approved? If so: | |
| &rarr; How many people will be targeted? | |

## Questions for Business Unit Managers

| Description                                                            | Ok |
| ---------------------------------------------------------------------- | -- |
| Is the manager aware that a test is about to be performed? | |
| What is the main datum that would create the greatest risk? | |
| Are there procedures to verify that business applications are functioning properly? | |
| Will the testers have access to the Quality Assurance testing procedures? | |
| Are Disaster Recovery Procedures in place for the application data? | |

## Questions for Systems Administrators

| Description                                                            | Ok |
| ---------------------------------------------------------------------- | -- |
| Are there any systems which could be characterized as fragile? | |
| Are there systems on the network which the client does not own? | |
| Are there systems that may require additional approval to test? | |
| Are Change Management procedures in place? | |
| What is the mean time to repair systems outages? | |
| Is any system monitoring software in place? | |
| What are the most critical servers and applications? | |
| Are backups tested on a regular basis? | |
| When was the last time the backups were restored? | |
