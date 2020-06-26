# Guarda Mobile Wallet v2 beta

## About

Guarda Wallet is non-custodial cryptocurrency storage, that supports the most popular coins and their tokens including BTC, BCH, BSV, ETH, Ethereum-based tokens (ERC-20, ERC-721), ETC, ZEC, LTC, XRP, NEO, EOS, DASH and the others.

Guarda developers created digital wallets that provide complete security. Everyone can use our software for easy storing and managing cryptocurrencies. We respect, appreciate, and sincerely love blockchain technology. Our priority is the decentralization of the Guarda software in accordance with the basic principles of blockchain. User privacy and anonymity are the main postulates for us, that is why we do not store your private keys, backup files, or any other data on Guarda servers. All your private data is stored only by you. Our wallet is lightweight, has a convenient and intuitive interface.


## Program overview

Guarda is planning to release a completely redesigned mobile application for Android and iOS platforms, and invites everyone to take part in beta testing and bug bounty program.

This program is aimed at finding bugs and vulnerabilities in Guarda mobile wallet v2.0 Beta for Android and iOS.

Guarda's primary goal is to offer users an exceptional experience in crypto asset management, with a focus on security. According to it all submitted issues will be evaluated based on the impact to our users and the Guarda ecosystem and used for the purposes of improving Guarda security and user experience.

This bounty brief describes the rules of the Guarda bug bounty program. Please review, understand, and agree to the following terms and conditions before conducting any testing for Guarda and before submitting a report.


## Program rules

- Please do not publicly disclose any vulnerabilities which have not been fixed
- Do not intentionally harm the experience of Guarda service to others, including degradation of services and denial of service attacks.
- Do not attempt non-technical attacks such as social engineering, phishing, or physical attacks against our employees, users, or infrastructure.
- Please provide detailed reports with reproducible steps (see Report guidelines). If the report is not detailed enough to reproduce the issue, the issue will not be eligible for a reward
- Submit one bug per report
- Multiple bugs caused by one underlying issue will be awarded one bounty.
- In case of receiving duplicate reports of a specific bug, only the first report is eligible for a reward.

### SLA:
Time to first response - 1 business day
Time to verify report - 5 business days from first response
Time to bounty - 10 business days from verification
By submitting a bug, you agree to be bound by the rules.

### Resources

### Beta applications:
- Android: https://play.google.com/apps/testing/com.crypto.multiwallet
- iOS: https://testflight.apple.com/join/zCE6fKV5

### Found Bugs:
Github: https://github.com/guardaco/guarda-mobile-beta/issues

### Guarda Support team:
Guarda support: https://guarda.freshdesk.com/support/tickets/new


## Guarda Vulnerability Classifications

### In scope:
- Guarda Mobile Wallet Beta 2.* Android
- Guarda Mobile Wallet Beta 2.* iOS

### Out of scope:
*.guarda.com
*.guarda.co
*.simplexcc.com

### Examples of issues that we are looking for:

### High
- bugs that can cause a loss of user funds/assets
- bugs that can cause exposure of private keys or mnemonic seed phrase 
- bugs of cryptographic implementation for sensitive functions such as wallet generation, transaction signing etc.


### Medium
- denial of service of the wallet app
- password lock screen bypass
- remote code execution
- third party service partner bugs (exchange, purchase) that could result in the loss of user funds

### Low
- bugs related to wallet generation, wallet access, wallet import / export
- bugs related to main wallet functionality - send, receive
- functional application bugs - inaccessible controls, missed links etc

### Ineligible issues:
- bugs that have no impact on main wallet functionality
- bugs that require root/jailbreak
- UI / usability bugs
- unavailable token rates
- bad internet connection / unavailability to access nodes or explorers or guarda api
- 3rd party library dependencies
- web vulnerabilities for *.guarda.com and *.guarda.co and 3rd party services
- password complexity policies
- internally known issues (https://github.com/guardaco/guarda-mobile-beta/issues/2), duplicate issues, or issues which have already been made public 
- bugs only exploitable on out-of-date browsers or platforms
- crashes due to malformed Intents
- any activity that could lead to the disruption of our service (DoS)
- distributed denial of service attacks (DDOS).

## Report guidelines

All reports should be submitted as a Guarda Github Issue https://github.com/guardaco/guarda-mobile-beta/issues

### Report should contain:
- Name of bug
- Platform and app version used during testing
- Steps to reproduce reported issue
- Visual proofs (video, screenshots etc) if needed. All attachments should be linked to the issue, no links to external services allowed.



## Bounty resolution

- Each report is checked manually. 
- It is up to Guarda to decide the severity of the bug, as well as the decision to award a payment
- Total funding for bounty program - 1000$
- Bug severity / Rewards:
- High: 200$
- Medium: 25$
- Low: 5$
- Once Guarda verifies the issue, please provide your ETH wallet address
- Rewards will be paid out in ETH at the exchange rate on the date of payment


## Fine print

We reserve the right to modify the Bug Bounty Program or cancel the Bug Bounty Program at any time.


## Safe harbor

Any activities conducted in a manner consistent with the law and our bounty policy will be considered authorized conduct and we will not initiate legal action against you. If legal action is initiated by a third party against you in connection with activities conducted under this policy, we will take steps to make it known that your actions were conducted in compliance with this policy
