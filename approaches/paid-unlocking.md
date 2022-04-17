> WARN: this is still work in progress!

# Monetization via Paid Unlocking
AKA: Paid performance, Pay for speed, Pay for features, Crippleware, Feature-limited

Contributions made by a user to un-throttle or unlock higher performance or special features. Payment could be collected via an registration key, external API or use of a crypto wallet and could become recurring.

Requires:
* Setup of a payment mechanism (e.g. via hosted API or crypto wallet)
* Integration of a throttling or locking mechanism into the OSS
* Integration of a token validation service into the OSS  

Variants & Options:
* API based: User pays by calling a paid API
* Crypto based: User pays by transfering a crypto token to the maintainers wallet
* ICO: Initial Coin/Token Offering with (discounted) sale (e.g., upfront payment for infrastructure development)
* Daily Checks: Check to unlock is done once per day
* Boot Checks: Check to unlock is done once per start
* Node Checks: Check to unlock is done once per day and node
 
## Platforms
* [RapidAPI](https://rapidapi.com/) (Unlocking by hitting the paid API)
* [Web Monetization API](https://webmonetization.org/) (Unlocking by paying with connected crypto wallet)

## Evaluation

| Characteristics                   | Value  | Note |
| --------------------------------- |:------ |:---- |
| Effort to set-up                  | Medium | Integration and setup of several small subsystems
| Effort to maintain income         | Low    | Probably only updating subsystem
| Visibility                        | Low    | Low performance / functionality might be OK for user
| Necessity to pay                  | Low    | Might be OK for user but can be made uncomfortable
| Scalability                       | Medium | Scales with the number of users (who need the performance)
| One-time Income                   | High   | ICO might bring a bigger initial income
| Recurring Income                  | Medium | Depends on the value created and number of running instances
| Income Stability / Predictability | Medium | If users accept paying it should become stable; Crypto might be very volatile
| Entry Threshold for client        | Medium | Paying for API access might be easy but paying in crypto might be more complex
| Clients needed for full income    | 500+   | Price can be set by maintainers

| Effort for marketing              | Low    | Will make waves but no "sale" is necessary
| Countervalue                      | Perf.  | User pays for performance or unlocked features
| Perfect for software type         | Special| Best for stand-alone systems on one server (e.g., databases, blogs, LMS, etc.)

| Additional Work                   | Low    | Extra work to initially develop unlocking system
| Upfront Cost                      | None   | 
| Continuous Cost                   | Low    | Platform used for unlocking might cost a little (or a share of the income)
| Recipient                         | C      | 
| Competitors                       | None   | 

> NOTE: Due to the nature of open-source a user can fork and remove the unlock check. But he had to do it every time and the maintainers could forbid it in a special License.