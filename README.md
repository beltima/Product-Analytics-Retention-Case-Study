# Case Study: Data Analyst

**Guidelines:** Open doc - 2 days

Your deliverable should include:
* A business-oriented presentation (PPT, PDF, Dashboard or even better a Notion page) to support your case.
* A technical draft (SQL queries, Python Notebook or Excel Sheets) to show your calculations, explorations and reasoning while working on this case.

With this business case, we will evaluate your capacity to extract the most impactful insights from a dataset in a limited amount of time, so don't hesitate to prioritize your analyses and synthesize your restitution.

---

## Product Analysis

We observe lower retention rates since a month or two. What key patterns or behaviors can you extract to identify churn risk?

#### Datasets
* `d0_behaviour_br.csv`
* `retention_br.csv`

#### Description

**d0_behaviour**
* What the user did on its first day (=D0)
* Columns:
    * `keychain_udid`: device unique ID
    * `country`: country ISO code
    * `os`: platform used
    * `locale`: language
    * `timezone`: timezone of the user
    * `device_model`: phone
    * `age`: self explanatory
    * `session_length`: length of the sessions (in seconds)
    * `had_meaningful`: had a meaningful reaction from another user
    * `install_at`: timestamp of the install

**retention**
* Retention data of the users
* Columns:
    * `keychain_udid`: device unique ID
    * `d0`, `d3`, `d7`, `d14`, `d30`: boolean that indicated if the user was present after 3, 7, 14, 30 days

---

## Product Feature Suggestion

* Suggest and describe a new product feature that would help improve user retention.
* What events and what properties would you implement to track its usage?
* How would you test whether this new feature is successful? What KPIs would you look at?

---

## AB Test Analysis

We launched an AB test on new users to tackle the retention issue, here are the results.

* Do you think we should release the test cohort to all our users? Why?

#### Datasets
* `ab_test_br.csv`

#### Description
* `keychain_udid`: device unique ID
* `event_date`: date of the events
* `ab_test_cohort`: cohort of the user (test if the user has the new feature)
* `ads_revenue`: revenues from advertising
* `sessions`: number of sessions made
* `meaningful_reactions`: number of meaningful reactions the user had

---
Once finished, you can send back your case to the Talent Acquisition member you are in contact with.

Good luck!