# Monetization via Paid Commercial Use
AKA: Dual-Licensing, Multi-Licensing, Hybrid licensing,Resticted License, Proprietary Licences, License Exceptions

Different licenses forcing commercial users to pay a license fee to the open source project. Enables recurring payments often with support guarantees or SLAs.

Requires:
* Setup of a payment mechanism (hosted or self-build)
* Setup of a license for commercial-use
* Probably a legal entity needs to be founded to receive the payments
* Recurring "observation activites" to check if the OSS is in use by companies not paying

Variants & Options:
* Dual License: Single license for entities with a commercial use of the OSS
* Multi License: Different licenses for startups, freelancer, companies, universities, etc. 

## Platforms
* [Fareness.dev](https://fareness.dev/) (programmatic payment checking system based on licences)
* None required?: Only one codebase and commercial users directly pay to OSS project's bank account

## Evaluation

| Characteristics                   | Value  | Note |
| --------------------------------- |:------ |:---- |
| Effort to set-up                  | Weeks  | Creation of a commercial license and legal documents
| Effort to maintain                | Low    | Maybe reminders that commercial use is needed
| Cost to set-up                    | Medium | Will require a lawyer to setup the license and contracts
| Cost to maintain                  | Low    | Will cause costs for legal or tax related stuff (but should be covered by income)
| One-time Income                   | High   | Few companies might pay large amounts if the OSS is essential
| Recurring Income                  | High   | License can enforce recurring payments per month or year
| Income Predictability             | High   | Companies probably need OSS for several years
| Full income Threshold             | 10+    | 
| Recipient                         | C      | 
| Additional Work                   | Medium | Will cause communication and SLA related work
| Visibility                        | Medium | Easy to overlook but should stand out in a tech due dilligence
| Necessity to pay                  | High   | However, companies might look for other solutions
| Entry Threshold                   | Medium | Individual contracts between every OSS and company might be necessary
| Countervalue                      | None   | Legal commercial use
| Scalability                       | Medium | Scales with the number of commercial users (who must pay)
| Effort for marketing              | Low    | 
| Competitors                       | O      | Depends on the original OSS licence: other companies could fork and develop it further with a proprietary license.
| Software types                    | Special| Best for libraries or programs companies build tools upon

> NOTE: A CLA (Contributor License Agreement) may be required to accept code contributions from third parties to the source code while retaining the ability to dual-license those contributions under the proprietary license.