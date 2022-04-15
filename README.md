> WARN: this is still work in progress!
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

# Awesome OSS Monetization
A curated list of awesome monetization approaches for open source software (currently probably with a slight bias towards open source libraries (like react.js, core-js, etc.) rather than open source programs (like OpenOffice, MariaDB, etc.)).

Please note that you can find an explanation of the used characteristics below at [Used Characteristics](#used-characteristics)

__Table of Contents__
- [Awesome OSS Monetization](#awesome-oss-monetization)
  - [Monetization Approaches](#monetization-approaches)
    - [Unconditional Funding](#unconditional-funding)
    - [Paid Access](#paid-access)
    - [Paid Work](#paid-work)
    - [Paid Content](#paid-content)
    - [Paid Licences](#paid-licences)
    - [Paid Services](#paid-services)
    - [Paid for Use](#paid-for-use)
    - [Special Monetization Approaches](#special-monetization-approaches)
  - [Used Characteristics](#used-characteristics)
  - [Notes / Monetization Risks](#notes--monetization-risks)
  - [Links to other Monetization Lists](#links-to-other-monetization-lists)
- [Opportunities & Reasons for Monetization](#opportunities--reasons-for-monetization)
  - [Reasons](#reasons)
  - [Opportunities](#opportunities)
- [OSS Definition & Delimitation](#oss-definition--delimitation)
- [Other Motivations for OSS](#other-motivations-for-oss)

## Monetization Approaches

### Unconditional Funding
* [Private Donations](./approaches/private-donations.md)
* [Corporate Sponsoring](./approaches/corporate-sponsoring.md)
* [Funding Grants & Stipends](./approaches/grants-and-stipends.md)

### Paid Access
* [Paid Early Access / Sponsorware / Embargo Model](./approaches/early-access.md)
* [Paid Memberspace / Community](./approaches/memberspace.md)
* [Advertisements on Website(s)](./approaches/advertisements.md)

### Paid Work
* [Paid Support](./approaches/paid-support.md)
* [Paid Bugfixes / Bounties](./approaches/paid-bugfixes.md)
* [Paid Feature Development](./approaches/paid-features.md)
* [Paid Version Development / Crowdfunding](./approaches/paid-versions.md)
* [Paid Consultations](./approaches/paid-consultations.md)
* [Paid Training & Certifications](./approaches/paid-certifications.md)

### Paid Content
* [Paid Online Courses](./approaches/paid-courses.md)
* [Paid Merchandise or Books](./approaches/paid-merchandise.md)
* [Paid Extensions / Plugins / Tools](./approaches/paid-tools.md)
* [Paid Newsletter](./approaches/paid-newsletter.md)

### Paid Licences
* [Paid Commercial Use / Dual-Licensing](./approaches/dual-licensing.md)
* [Paid Premium Version / Open Core](./approaches/open-core.md)

### Paid Services
* [Paid Hosting / Open SaaS](./approaches/paid-hosting.md)

### Paid for Use
* [Paid Usage](./approaches/paid-usage.md)
* [Kickback from Hoster](./approaches/kickback.md)
* [Paid Unlocking](./approaches/paid-unlocking.md)
* [Sell Telemetry](./approaches/telemetry.md)
* [Blockchain-based distribution](./approaches/blockchain-distribution.md)

### Special Monetization Approaches
* [Employment](./approaches/employement.md)
* [Raise Venture Capital](./approaches/raise-venture-capital.md)
* [Sell Project](./approaches/acquisition.md)
* TBD: _Widget Frosting (selling hardware on-top of OSS)_

## Used Characteristics
In order to evaluate and explain the monetization approaches, several characteristics were used. 
* Effort to set-up: The amount of work required to start the monetization approach. [None; Low; Medium; High; N/A] or [None, Days, Weeks, Months, N/A]?
* Effort to maintain income: The amount of work needed to keep the monetization going. 
* Visibility: The ease with which a user of the OSS notices the monetization approach. 
* Necessity to pay: The need for the user of an OSS to accept and pay. 
* Scalability: The ease and number of users or companies that can be reached to pay. 
* One-time Income: The level of one single contribution. 
* Recurring Income: The level of monthly contribution that can be expected. 
* Entry Threshold for client: The amount of effort necessary to contribute money. 
* Clients needed for full income: The amount of payers necessary to get to 5k USD (pre-Tax) per month. 

* Effort for marketing: The amount of work necessary to make the monetization opportunity known to the public. 
* Countervalue: The value a contributor of money gets if he pays. 
* Perfect for software type: The types of OSS that would benefit the most from this onetization approach. 

* Additional Work: The amount of (continuous) work required in addition to working on the OSS. 
* Upfront Cost: The monetary cost to setup the monetization approach (e.g., for external services) - excluding cost for private bank accounts, tax advisors, etc. 
* Continuous Cost: The monetary cost to maintain the monetization approach over time (e.g., for hosting certificates)
* Recipient: The entity receiving the monetization result - and who might distribute it further (I: Individual, C: Collective/Company)
* Competitors: The kind of competitors for this monetization approach (M: Other maintainers, C: Contributors, O: Other Developers, Companies, or Content creators)

## Notes / Monetization Risks
* Need for Legal Entity: depends heavily on the country / jurisdiction you live in (or pay taxes in if you are a Digital Native). As an individual it would be good to be registered as a Freelancer, to tax the income - but in some countries the normal income tax declaration might be sufficient (Please ask a tax advisor in your country).

... Dangers, Problems
* Not having a License
* Not having a concensus in the maintainer or contributor group
* Overlooking Contributor's Copyright / missing CLA: May require a CLA (Contributor License Agreement) in order to accept code submissions from outside contributors while retaining the ability to relicense those submissions under the proprietary license
* Unfair distribution / unbalanced distribution
* Not paying taxes (as a project or individual)
> TBD

If funds are being raised for a __project__ (multiple maintainers or contributors - not a single individual), the following might also be required regardless of monetization approach:
* An extra bank account or fiscal host to collect the funding and distribute it from there
* A distribution or usage model for the money (i.e., who (maintainers, contributors, etc.) or what (bug bounties, conferences, etc.) gets how much of the money?). Distribution might be implemented, e.g., objectively by number of features, bugfixes, LOC, etc. or subjectively determined by the maintainer(s) or by voting.
* The project may need to be incorporated and pay itself taxes (some legal forms may be tax-exempt, such as a non-profit entity (USA) or a registered association (Germany)).

If funds are being raised for an __individual__ or distrituted from a fiscal host to an individual, the following might also be required regardless of monetization approach:
* The individual might need to pay taxes for the funding in their country

## Links to other Monetization Lists
[1] https://en.wikipedia.org/wiki/Business_models_for_open-source_software

[2] https://github.com/nayafia/lemonade-stand 

[3] https://www.oss.fund

# Opportunities & Reasons for Monetization
## Reasons
Trademark infringements:
(March 2016): Azer Koçulu unpublished over 250 modules (esp. left-pad) from npm due to trademark infringement over the name "kik".

Faulty updates
(April 2020) Updated is-promised library didn't adhere to the proper ES module standards causing wide-spread build errors. 

Package Ownership
(Aug. 2021) The ownership of the package bebop was auto-transferred due to a corrupt contact address of the former owner

Corporate Disputes
(Aug. 2021): Elasticsearch change its widely used JS library to not work with AWS Elasticsearch and OpenSearch anymore.

Security Problems
(Dec 2021): log4j enabled a feature from 2013 by default that allowed loading of malicious code.

Developer Burnout / Infocide
(Jan. 2022): Marak deletes his projects Colors.js and Faker.js after getting pushed / bullied by corporates.

* Independent / Digital Native Lifestyle
* Slowly build-up of a Startup
## Opportunities

> TBD

# OSS Definition & Delimitation
> TBD

# Other Motivations for OSS
* (Learning, ...)
> TBD
