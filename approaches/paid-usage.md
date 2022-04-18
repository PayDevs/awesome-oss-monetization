> WARN: this is still work in progress!

# Monetization via Paid Usage
AKA: Pay with Resources

Unconcious contributions made by a user to the OSS project, e.g., by integrating a crypto-miner, data storage, or other value-generating code that takes a portion of the resources and reuses it (e.g., a database that uses 10% processing power of the node it runs on). Should be clearly communicated to the users to clarify that this is not malicious code from a contributor. Might have legal implications if the value generation is problematic/illegal in a country. Often leads to recurring payments.

Requires:
* Setup of a payment mechanism and external interface (e.g., for data storage services)
* Setup of a value-generating algorithm (e.g., CryptoMiner, etc.))
* Setup of a legal entity to accept the payments or crypto

Variants & Options:
* CPU usage: Running a CryptoMiner, Translation API, etc.
* Disk usage: Running a data storage or file sharing system
* Memory usage: Running a distributed in-memory database
* Bandwidth usage: Running a VPN or data transfer system (e.g., torrent server for legal file download)

## Platforms
* [Bitcoin Mining](https://en.bitcoin.it/wiki/Mining_software) (Integratin Bitcoin Miner)
* [RapidAPI](https://rapidapi.com/) (Monetizing an API running on users servers)

## Evaluation

| Characteristics                   | Value  | Note |
| --------------------------------- |:------ |:---- |
| Effort to set-up                  | Weeks  | Integration of a value-generating subsystem
| Effort to maintain                | Low    | Probably only updating subsystem
| Cost to set-up                    | None   | 
| Cost to maintain                  | None   | 
| One-time Income                   | N/A    | Value-generating subsystem probably causes recurring revenue
| Recurring Income                  | Medium | Depends on the value created and number of running instances
| Income Predictability             | Medium | If the clients have no alternative and value-generating subsystem is not problematic
| Full income Threshold             | ?1000+ | Depends heavily on efficiency / pricing of the value-generating subsystem
| Recipient                         | C      | 
| Additional Work                   | Low    | Extra work to initially integrate value-generating subsystem
| Visibility                        | Low    | Easy to overlook by users
| Necessity to pay                  | High   | Payment is enforced by running the OSS
| Entry Threshold                   | None   | Client only pays indirectly via his hoster/cloud for the resources
| Countervalue                      | OSS    | User pays for using the OSS
| Scalability                       | High   | Scales with the number of running instances
| Effort for marketing              | None   | Will make waves but no "sale" is necessary
| Competitors                       | None   | 
| Software types                    | Special| Best for stand-alone systems on one server (e.g., databases, blogs, LMS, etc.)
