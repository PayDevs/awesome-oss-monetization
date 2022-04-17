> WARN: this is still work in progress!

# Monetization by Paid Data Storage
AKA: Pay for Data Hosting

Payment for centrally storing data used in the OSS on a remote server - e.g., passwords for a password manager. Often leads to recurring payments for long-time data storage, but can also be a singular payment for time-constrained or lifetime storage.

Requires:
* Setup of a data storage platform (hosted of self-hosted)
* Integration of payment mechanism
* Setup of a legal entity to accept the payments

Variants & Options:
* Freemium Data Storage: A small amount of data is free to store but larger amounts must be paid

## Platforms
* Storage can be realized in many Clouds by using a hosted Database with Backup mechanism
* Payment system requires website or in-app mechanism connected to payment system

## Evaluation

| Characteristics                   | Value  | Note |
| --------------------------------- |:------ |:---- |
| Effort to set-up                  | Medium | Implement data storage and payment system
| Effort to maintain income         | Low    | Backup and maintain data storage
| Visibility                        | Medium | Gets harder the more the system is used (more data created)
| Necessity to pay                  | Low    | The base version can probably work without paid data storage (or few people would try it) 
| Scalability                       | High   | Scales with the number of end-users and data created.
| One-time Income                   | Medium | If data storage is bought for life, etc.
| Recurring Income                  | Medium | 
| Income Stability / Predictability | Medium | Client might go back to free
| Entry Threshold for client        | Low    | If starting with free storage
| Clients needed for full income    | 1000+  | Depends heavily on the data storage price

| Effort for marketing              | Low    | Users probably increase their data volume
| Countervalue                      | Storage| User pays for data storage, backups, and access from multiple devices
| Perfect for software type         | Special| Best for tools that create or handle user data

| Additional Work                   | Medium | Extra work to setup data storage
| Upfront Cost                      | Low    | Maybe for DB and backup
| Continuous Cost                   | Low    | Cost of data storage & backup
| Recipient                         | C      | 
| Competitors                       | None   | Could be opened for compeitors within OSS
