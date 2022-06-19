# Monetization by selling Telemetry
AKA: Pay with user data

Contributions in form of user data which is send to a server of the maintainers, who then sell this data. Should be clearly communicated to the users to clarify that this is not malicious code from a contributor. Might have legal implications (GDPR) if the value generation is problematic/illegal in a country. Often leads to recurring payments.

Requires:
* Setup of an account at a data buying platform
* Integration of data collection mechanism that sends data to specific servers
* Setup of a legal entity to accept the payments or crypto

Variants & Options:
* Anonymized Data: Collecting only anonymous data has less legal problems

## Platforms
* [LeapYear](https://leapyear.io/data-monetization/) (Data monetization)
* [Tealium](https://tealium.com/lp/monetize-customer-data/) (Data monetization with Customer Data Platform)

## Evaluation

| Characteristics                   | Value  | Note |
| --------------------------------- |:------ |:---- |
| Effort to set-up                  | Weeks  | Integration of a data collection system
| Effort to maintain                | Low    | Probably only updating subsystem
| Cost to set-up                    | None   | 
| Cost to maintain                  | Low    | Platform used to collect telemetry data might cost a little (or take a share of the income)
| One-time Income                   | N/A    | Value-generating subsystem probably causes recurring revenue
| Recurring Income                  | Medium | Depends on the data value and number of end-users
| Income Predictability             | Medium | Easier if the clients have no alternative systems
| Full income Threshold             | ?1000+ | Depends heavily on the user data value
| Recipient                         | C      | 
| Additional Work                   | Low    | Extra work to initially integrate telemetry system
| Visibility                        | Low    | Easy to overlook by users
| Necessity to pay                  | High   | Payment is enforced by running the OSS
| Entry Threshold                   | Low    | Client only pays indirectly via his hoster/cloud for the resources. Client might need to disclose data usage to his users
| Countervalue                      | OSS    | User pays for using the OSS
| Scalability                       | High   | Scales with the number of end-users
| Effort for marketing              | None   | Will make waves but no "sale" is necessary
| Competitors                       | None   | 
| Software types                    | Special| Best for stand-alone systems with third-party users (e.g., blogs, LMS, etc.)
