# 🎯 QA Job Interview — Complete English Dialogue

> A realistic Q&A dialogue between an interviewer and a QA Engineer, covering **testing fundamentals, automation, processes, and agile practices** (20+ questions and answers).

---

## 👥 The Participants

| Role | Description |
|------|-------------|
| 🧑‍💼 **Interviewer** | Senior Engineering Manager |
| 👩‍💻 **Candidate** | Experienced QA Engineer (16 years) |

---

## 💬 The Interview

---

### 🔹 Question 1 — Introduction

**🧑‍💼 Interviewer:**
> Thank you for coming! Let's get started. Could you briefly introduce yourself and tell us about your experience in QA?

**👩‍💻 Candidate:**
Sure! I've been working in software quality assurance for about **5 years**. I started as a manual tester and gradually transitioned into test automation. I've been part of agile teams, focusing on **web and API testing**, implementing test strategies, and improving QA processes through automation and closer collaboration with developers and product owners.

Interviewer: What’s the difference between verification and validation in software testing?
---

### 🔹 Question 2 — Verification vs. Validation

**🧑‍💼 Interviewer:**
> What's the difference between **verification** and **validation** in software testing?

**👩‍💻 Candidate:**
Great question! Here's how I think about it:

- ✅ **Verification** — *"Are we building the product right?"* — checks if the software meets the specified requirements and design (documents, specs, code reviews).
- ✅ **Validation** — *"Are we building the right product?"* — checks if the software actually satisfies **user needs and business goals** (real usage, acceptance testing).

In short: verification is about correctness, validation is about value.

---

### 🔹 Question 3 — Testing Levels

**🧑‍💼 Interviewer:**
> Can you explain the different **levels of testing**?

**👩‍💻 Candidate:**
Absolutely! The main levels are:

| 🏗️ Level | 📋 Focus |
|----------|---------|
| **Unit Testing** | Small pieces of code — functions or methods, usually written by developers |
| **Integration Testing** | How different modules or services work together |
| **System Testing** | The complete integrated system against all requirements |
| **Acceptance Testing** | User/business perspective — often done as UAT (User Acceptance Testing) |

---

### 🔹 Question 4 — Types of Testing

**🧑‍💼 Interviewer:**
> What types of testing do you usually perform?

**👩‍💻 Candidate:**
It depends on the project, but my typical toolkit includes:

- 🔍 **Functional testing**
- 🔁 **Regression testing**
- 💨 **Smoke & sanity testing**
- 🗺️ **Exploratory testing**
- 🌐 **API testing**
- ⚡ **Performance testing** *(usually with a specialized team)*
- 🤖 **Automated testing** for regression and critical paths

---

### 🔹 Question 5 — What to Automate?

**🧑‍💼 Interviewer:**
> How do you decide **what to automate** and what to keep as manual tests?

**👩‍💻 Candidate:**
I consider several factors:

- 🔄 **Frequency of execution** — High-frequency tests are strong candidates for automation.
- 🏗️ **Stability of functionality** — Stable features work well; unstable ones cause flaky tests.
- 💼 **Business criticality** — Critical paths and core workflows should always be automated.
- 🧩 **Complexity** — If automation is extremely complex and cheaper to test manually, I keep it manual.
- 📊 **ROI** — I evaluate maintenance cost versus time saved in regression cycles.

---

### 🔹 Question 6 — Automation Tools & Frameworks

**🧑‍💼 Interviewer:**
> Which **automation tools and frameworks** do you have experience with?

**👩‍💻 Candidate:**
Here's my stack:

| 🧰 Category | 🛠️ Tools |
|-------------|---------|
| **UI Testing** | Selenium WebDriver, Cypress, Playwright |
| **API Testing** | Postman, REST Assured, Cypress |
| **Unit Testing** | JUnit, TestNG, Jest |
| **CI/CD** | Jenkins, GitLab CI, GitHub Actions |

---

### 🔹 Question 7 — Framework Structure

**🧑‍💼 Interviewer:**
> How do you **structure** your automated test framework?

**👩‍💻 Candidate:**
I aim for a framework that is **modular, readable, and easy to maintain**:

- 📁 **Clear folder structure** — separating tests, page objects, utilities, test data, and configs
- 🧱 **Page Object Model (POM)** for UI tests to avoid code duplication
- 🔧 **Reusable helpers** for common actions like login, data setup, and API calls
- ⚙️ **Config files** for environment URLs, credentials (secured!), and browser settings
- ✅ Tests should be **readable, independent, and not tightly coupled** to each other

---

### 🔹 Question 8 — QA in Agile

**🧑‍💼 Interviewer:**
> Can you describe your **test process in an agile environment**?

**👩‍💻 Candidate:**
In agile, I'm involved from day one:

- 📋 **Refinement** — I join grooming sessions to clarify requirements and help define acceptance criteria and test scenarios.
- 📅 **Planning** — I estimate testing effort and identify risks early.
- 🚀 **During the sprint** — I write test cases, collaborate with developers, and start automation in parallel when possible.
- 🔄 **Continuous testing** — I run tests in CI, provide fast feedback, and retest issues quickly.
- 🔎 **Review & Retro** — I share feedback on what worked, what didn't, and how to improve quality.

---

### 🔹 Question 9 — Regression on Frequent Releases

**🧑‍💼 Interviewer:**
> How do you handle **regression testing** when there are frequent releases?

**👩‍💻 Candidate:**
I rely heavily on automation for regression. My approach:

- 🤖 Maintain an automated **regression suite** covering critical functionalities.
- 🎯 For areas not yet automated, use **risk-based testing** to prioritize manual regression.
- 💨 Run **smoke tests after every deployment** to verify main flows still work in production or staging.

---

### 🔹 Question 10 — Risk-Based Testing

**🧑‍💼 Interviewer:**
> What is **risk-based testing**?

**👩‍💻 Candidate:**
Risk-based testing means **prioritizing tests based on:**

1. 📉 **Probability of failure** — How likely is this area to break?
2. 💥 **Impact of failure** — What happens if it does break?

Modules that are business-critical or highly complex receive more testing effort and earlier attention. This is especially valuable when **time and resources are limited**.

---

### 🔹 Question 11 — Test Coverage

**🧑‍💼 Interviewer:**
> How do you ensure **good test coverage**?

**👩‍💻 Candidate:**
I combine multiple approaches:

- 📝 Analyze **requirements and user stories** to derive test cases.
- 🔗 Maintain **traceability** between requirements and tests.
- 🗺️ Perform **exploratory testing** to catch issues beyond scripted tests.
- 🤝 Collaborate with developers to understand **complex flows and edge cases**.
- 📊 Use **code coverage tools** (for unit/integration tests) as an additional indicator.

---

### 🔹 Question 12 — Flaky Tests

**🧑‍💼 Interviewer:**
> How do you deal with **flaky automated tests**?

**👩‍💻 Candidate:**
First, I identify the root cause — is the flakiness related to **timing, environment, data, or external services?** Then I:

- ⏱️ Improve **synchronization** — use explicit waits instead of arbitrary `sleep()`.
- 🗄️ Stabilize **test data** and remove dependencies between tests.
- 🔌 **Mock or stub** unstable external dependencies when appropriate.
- 📸 Improve **error logging and screenshots** to analyze failures faster.
- 🚧 If a test stays flaky with low value, I **quarantine** it, then refactor or replace it.

---

### 🔹 Question 13 — API Testing

**🧑‍💼 Interviewer:**
> What's your experience with **API testing**?

**👩‍💻 Candidate:**
I've tested REST APIs using **Postman** for exploration and **REST Assured / Cypress** for automation. I validate:

- ✅ Response **status codes**
- 📦 Response **body and schema**
- 🔐 **Headers and authentication**
- ⚠️ **Error handling**
- 🔁 **Edge cases and negative scenarios**

I also integrate API tests into **CI/CD** to run on every build or merge to the main branch.

---

### 🔹 Question 14 — CI/CD Integration

**🧑‍💼 Interviewer:**
> How do you **integrate your tests into a CI/CD pipeline**?

**👩‍💻 Candidate:**
I work with DevOps or developers to:

- ⚙️ Add **test execution steps** to the pipeline *(unit → API → UI tests)*.
- 📊 Configure **test reports** (JUnit XML, HTML dashboards).
- 🚨 Set **quality gates** — fail the build if critical tests fail.
- ⚡ **Parallelize tests** to reduce execution time.

This ensures fast, **visible feedback** for the entire team.

---

### 🔹 Question 15 — Challenging Bug

**🧑‍💼 Interviewer:**
> Can you describe a **challenging bug** you found and how you handled it?

**👩‍💻 Candidate:**
In one project, I found an **intermittent bug in the checkout process** that only occurred under specific load conditions and for certain user roles.

I reproduced it by correlating:
- 📋 API logs
- 🖥️ Frontend console logs
- 🗄️ Database queries

I then created a clear, detailed **bug report** with steps, environment, data used, screenshots, and logs. This helped developers quickly identify a **race condition in the backend**. After the fix, I added automated tests and performance checks to prevent regression.

---

### 🔹 Question 16 — Writing a Good Bug Report

**🧑‍💼 Interviewer:**
> How do you write a **good bug report**?

**👩‍💻 Candidate:**
A great bug report should include:

| 📝 Field | 📋 Description |
|---------|---------------|
| **Title** | Clear summary of the problem |
| **Environment** | Version, environment, browser, device |
| **Steps to Reproduce** | Precise and repeatable steps |
| **Expected vs. Actual** | Clear description of the difference |
| **Attachments** | Screenshots, logs, or videos |
| **Severity & Priority** | Business impact classification |

This saves everyone time and avoids unnecessary back-and-forth. 💡

---

### 🔹 Question 17 — Collaboration

**🧑‍💼 Interviewer:**
> How do you **collaborate with developers and product owners**?

**👩‍💻 Candidate:**
I treat it as a **partnership**, not gatekeeping. My approach:

- 🤝 **With Developers** — Join discussions early, test early builds, provide fast feedback, and keep an open channel during development.
- 💼 **With Product Owners** — Discuss quality trade-offs, help prioritize issues based on user impact, and clarify acceptance criteria.

I also review requirements, surface edge cases, and share test scenarios to build **shared ownership of quality**.

---

### 🔹 Question 18 — Test Documentation

**🧑‍💼 Interviewer:**
> What's your approach to **test documentation**?

**👩‍💻 Candidate:**
I prefer **lightweight but useful** documentation:

- 📋 For regression — I maintain test cases or checklists for critical areas.
- 🗺️ For exploratory testing — I use charters and short session notes.
- 🔄 I keep docs up to date when features change.
- 📖 I document the **test strategy and coverage** for key projects so new team members onboard quickly.

---

### 🔹 Question 19 — Staying Up to Date

**🧑‍💼 Interviewer:**
> How do you **stay current** with QA and automation best practices?

**👩‍💻 Candidate:**
I stay sharp through:

- 📰 **Blogs and communities** — QA/Dev channels and newsletters
- 📚 **Official documentation** for new tools
- 🧪 **Side projects** to experiment with new frameworks
- 🔍 **Code reviews and retrospectives** with teammates
- 🎤 When I discover something useful, I **bring it to the team** (e.g., better assertion libraries or improved test data patterns)

---

### 🔹 Question 20 — QA's Role in Agile

**🧑‍💼 Interviewer:**
> What do you think is the **role of QA in an agile team**?

**👩‍💻 Candidate:**
QA's role goes far beyond finding bugs — it's about **helping the whole team deliver quality**:

- 🛡️ **Prevent defects** by participating in refinement and design discussions.
- 📊 **Make quality visible** through tests and metrics.
- ⚡ **Provide fast feedback** through automation and testing.
- 🤝 **Encourage shared ownership** — quality is everyone's responsibility, not just QA.

---

### 🔹 Question 21 — Improving QA Processes

**🧑‍💼 Interviewer:**
> Where do you see **opportunities to improve our QA process** if you join?

**👩‍💻 Candidate:**
Initially, I would:

1. 🔍 **Understand** the current test strategy, automation coverage, and release process.
2. 🚧 **Identify bottlenecks** — long regression cycles, high production bug rates.
3. 🤖 **Strengthen automated regression** around critical paths.
4. 🤝 **Improve QA collaboration** in refinement and planning sessions.
5. 🔧 **Reduce flaky tests** and make results more visible and reliable.

---

### 🔹 Closing — Candidate's Questions

**🧑‍💼 Interviewer:**
> Thank you! Do you have any **questions for us**?

**👩‍💻 Candidate:**
Absolutely! I'd love to understand:

- 🔄 How is **QA currently integrated** into your development process?
- 🛠️ What **tools do you use** for automation and CI/CD?
- 🎯 What are your **main quality challenges** right now?

---

## 📚 Vocabulary Highlights

| 🔤 Term | 💡 Meaning |
|---------|-----------|
| **Flaky test** | A test that passes sometimes and fails other times without code changes |
| **Smoke test** | A quick set of tests to verify basic functionality after a deployment |
| **UAT** | User Acceptance Testing — validates the system from the end user's perspective |
| **POM** | Page Object Model — a design pattern to organize UI test code |
| **ROI** | Return on Investment — benefit vs. cost of a testing effort |
| **Race condition** | A bug where behavior depends on the timing of uncontrollable events |
| **Quarantine** | Temporarily isolating flaky/unstable tests from the main test suite |

---

> 💡 **Study Tip:** Practice this dialogue out loud! Record yourself answering each question and compare with the suggested answers. Focus on **clear, confident delivery** and **technical vocabulary**.---

### 🔹 Question 2 — Verification vs. Validation

**🧑‍💼 Interviewer:**
> What's the difference between **verification** and **validation** in software testing?

**👩‍💻 Candidate:**
Great question! Here's how I think about it:

- ✅ **Verification** — *"Are we building the product right?"* — checks if the software meets the specified requirements and design (documents, specs, code reviews).
- ✅ **Validation** — *"Are we building the right product?"* — checks if the software actually satisfies **user needs and business goals** (real usage, acceptance testing).

In short: verification is about correctness, validation is about value.

---

### 🔹 Question 3 — Testing Levels

**🧑‍💼 Interviewer:**
> Can you explain the different **levels of testing**?

**👩‍💻 Candidate:**
Absolutely! The main levels are:

| 🏗️ Level | 📋 Focus |
|----------|---------|
| **Unit Testing** | Small pieces of code — functions or methods, usually written by developers |
| **Integration Testing** | How different modules or services work together |
| **System Testing** | The complete integrated system against all requirements |
| **Acceptance Testing** | User/business perspective — often done as UAT (User Acceptance Testing) |

---

### 🔹 Question 4 — Types of Testing

**🧑‍💼 Interviewer:**
> What types of testing do you usually perform?

**👩‍💻 Candidate:**
It depends on the project, but my typical toolkit includes:

- 🔍 **Functional testing**
- 🔁 **Regression testing**
- 💨 **Smoke & sanity testing**
- 🗺️ **Exploratory testing**
- 🌐 **API testing**
- ⚡ **Performance testing** *(usually with a specialized team)*
- 🤖 **Automated testing** for regression and critical paths

---

### 🔹 Question 5 — What to Automate?

**🧑‍💼 Interviewer:**
> How do you decide **what to automate** and what to keep as manual tests?

**👩‍💻 Candidate:**
I consider several factors:

- 🔄 **Frequency of execution** — High-frequency tests are strong candidates for automation.
- 🏗️ **Stability of functionality** — Stable features work well; unstable ones cause flaky tests.
- 💼 **Business criticality** — Critical paths and core workflows should always be automated.
- 🧩 **Complexity** — If automation is extremely complex and cheaper to test manually, I keep it manual.
- 📊 **ROI** — I evaluate maintenance cost versus time saved in regression cycles.

---

### 🔹 Question 6 — Automation Tools & Frameworks

**🧑‍💼 Interviewer:**
> Which **automation tools and frameworks** do you have experience with?

**👩‍💻 Candidate:**
Here's my stack:

| 🧰 Category | 🛠️ Tools |
|-------------|---------|
| **UI Testing** | Selenium WebDriver, Cypress, Playwright |
| **API Testing** | Postman, REST Assured, Cypress |
| **Unit Testing** | JUnit, TestNG, Jest |
| **CI/CD** | Jenkins, GitLab CI, GitHub Actions |

---

### 🔹 Question 7 — Framework Structure

**🧑‍💼 Interviewer:**
> How do you **structure** your automated test framework?

**👩‍💻 Candidate:**
I aim for a framework that is **modular, readable, and easy to maintain**:

- 📁 **Clear folder structure** — separating tests, page objects, utilities, test data, and configs
- 🧱 **Page Object Model (POM)** for UI tests to avoid code duplication
- 🔧 **Reusable helpers** for common actions like login, data setup, and API calls
- ⚙️ **Config files** for environment URLs, credentials (secured!), and browser settings
- ✅ Tests should be **readable, independent, and not tightly coupled** to each other

---

### 🔹 Question 8 — QA in Agile

**🧑‍💼 Interviewer:**
> Can you describe your **test process in an agile environment**?

**👩‍💻 Candidate:**
In agile, I'm involved from day one:

- 📋 **Refinement** — I join grooming sessions to clarify requirements and help define acceptance criteria and test scenarios.
- 📅 **Planning** — I estimate testing effort and identify risks early.
- 🚀 **During the sprint** — I write test cases, collaborate with developers, and start automation in parallel when possible.
- 🔄 **Continuous testing** — I run tests in CI, provide fast feedback, and retest issues quickly.
- 🔎 **Review & Retro** — I share feedback on what worked, what didn't, and how to improve quality.

---

### 🔹 Question 9 — Regression on Frequent Releases

**🧑‍💼 Interviewer:**
> How do you handle **regression testing** when there are frequent releases?

**👩‍💻 Candidate:**
I rely heavily on automation for regression. My approach:

- 🤖 Maintain an automated **regression suite** covering critical functionalities.
- 🎯 For areas not yet automated, use **risk-based testing** to prioritize manual regression.
- 💨 Run **smoke tests after every deployment** to verify main flows still work in production or staging.

---

### 🔹 Question 10 — Risk-Based Testing

**🧑‍💼 Interviewer:**
> What is **risk-based testing**?

**👩‍💻 Candidate:**
Risk-based testing means **prioritizing tests based on:**

1. 📉 **Probability of failure** — How likely is this area to break?
2. 💥 **Impact of failure** — What happens if it does break?

Modules that are business-critical or highly complex receive more testing effort and earlier attention. This is especially valuable when **time and resources are limited**.

---

### 🔹 Question 11 — Test Coverage

**🧑‍💼 Interviewer:**
> How do you ensure **good test coverage**?

**👩‍💻 Candidate:**
I combine multiple approaches:

- 📝 Analyze **requirements and user stories** to derive test cases.
- 🔗 Maintain **traceability** between requirements and tests.
- 🗺️ Perform **exploratory testing** to catch issues beyond scripted tests.
- 🤝 Collaborate with developers to understand **complex flows and edge cases**.
- 📊 Use **code coverage tools** (for unit/integration tests) as an additional indicator.

---

### 🔹 Question 12 — Flaky Tests

**🧑‍💼 Interviewer:**
> How do you deal with **flaky automated tests**?

**👩‍💻 Candidate:**
First, I identify the root cause — is the flakiness related to **timing, environment, data, or external services?** Then I:

- ⏱️ Improve **synchronization** — use explicit waits instead of arbitrary `sleep()`.
- 🗄️ Stabilize **test data** and remove dependencies between tests.
- 🔌 **Mock or stub** unstable external dependencies when appropriate.
- 📸 Improve **error logging and screenshots** to analyze failures faster.
- 🚧 If a test stays flaky with low value, I **quarantine** it, then refactor or replace it.

---

### 🔹 Question 13 — API Testing

**🧑‍💼 Interviewer:**
> What's your experience with **API testing**?

**👩‍💻 Candidate:**
I've tested REST APIs using **Postman** for exploration and **REST Assured / Cypress** for automation. I validate:

- ✅ Response **status codes**
- 📦 Response **body and schema**
- 🔐 **Headers and authentication**
- ⚠️ **Error handling**
- 🔁 **Edge cases and negative scenarios**

I also integrate API tests into **CI/CD** to run on every build or merge to the main branch.

---

### 🔹 Question 14 — CI/CD Integration

**🧑‍💼 Interviewer:**
> How do you **integrate your tests into a CI/CD pipeline**?

**👩‍💻 Candidate:**
I work with DevOps or developers to:

- ⚙️ Add **test execution steps** to the pipeline *(unit → API → UI tests)*.
- 📊 Configure **test reports** (JUnit XML, HTML dashboards).
- 🚨 Set **quality gates** — fail the build if critical tests fail.
- ⚡ **Parallelize tests** to reduce execution time.

This ensures fast, **visible feedback** for the entire team.

---

### 🔹 Question 15 — Challenging Bug

**🧑‍💼 Interviewer:**
> Can you describe a **challenging bug** you found and how you handled it?

**👩‍💻 Candidate:**
In one project, I found an **intermittent bug in the checkout process** that only occurred under specific load conditions and for certain user roles.

I reproduced it by correlating:
- 📋 API logs
- 🖥️ Frontend console logs
- 🗄️ Database queries

I then created a clear, detailed **bug report** with steps, environment, data used, screenshots, and logs. This helped developers quickly identify a **race condition in the backend**. After the fix, I added automated tests and performance checks to prevent regression.

---

### 🔹 Question 16 — Writing a Good Bug Report

**🧑‍💼 Interviewer:**
> How do you write a **good bug report**?

**👩‍💻 Candidate:**
A great bug report should include:

| 📝 Field | 📋 Description |
|---------|---------------|
| **Title** | Clear summary of the problem |
| **Environment** | Version, environment, browser, device |
| **Steps to Reproduce** | Precise and repeatable steps |
| **Expected vs. Actual** | Clear description of the difference |
| **Attachments** | Screenshots, logs, or videos |
| **Severity & Priority** | Business impact classification |

This saves everyone time and avoids unnecessary back-and-forth. 💡

---

### 🔹 Question 17 — Collaboration

**🧑‍💼 Interviewer:**
> How do you **collaborate with developers and product owners**?

**👩‍💻 Candidate:**
I treat it as a **partnership**, not gatekeeping. My approach:

- 🤝 **With Developers** — Join discussions early, test early builds, provide fast feedback, and keep an open channel during development.
- 💼 **With Product Owners** — Discuss quality trade-offs, help prioritize issues based on user impact, and clarify acceptance criteria.

I also review requirements, surface edge cases, and share test scenarios to build **shared ownership of quality**.

---

### 🔹 Question 18 — Test Documentation

**🧑‍💼 Interviewer:**
> What's your approach to **test documentation**?

**👩‍💻 Candidate:**
I prefer **lightweight but useful** documentation:

- 📋 For regression — I maintain test cases or checklists for critical areas.
- 🗺️ For exploratory testing — I use charters and short session notes.
- 🔄 I keep docs up to date when features change.
- 📖 I document the **test strategy and coverage** for key projects so new team members onboard quickly.

---

### 🔹 Question 19 — Staying Up to Date

**🧑‍💼 Interviewer:**
> How do you **stay current** with QA and automation best practices?

**👩‍💻 Candidate:**
I stay sharp through:

- 📰 **Blogs and communities** — QA/Dev channels and newsletters
- 📚 **Official documentation** for new tools
- 🧪 **Side projects** to experiment with new frameworks
- 🔍 **Code reviews and retrospectives** with teammates
- 🎤 When I discover something useful, I **bring it to the team** (e.g., better assertion libraries or improved test data patterns)

---

### 🔹 Question 20 — QA's Role in Agile

**🧑‍💼 Interviewer:**
> What do you think is the **role of QA in an agile team**?

**👩‍💻 Candidate:**
QA's role goes far beyond finding bugs — it's about **helping the whole team deliver quality**:

- 🛡️ **Prevent defects** by participating in refinement and design discussions.
- 📊 **Make quality visible** through tests and metrics.
- ⚡ **Provide fast feedback** through automation and testing.
- 🤝 **Encourage shared ownership** — quality is everyone's responsibility, not just QA.

---

### 🔹 Question 21 — Improving QA Processes

**🧑‍💼 Interviewer:**
> Where do you see **opportunities to improve our QA process** if you join?

**👩‍💻 Candidate:**
Initially, I would:

1. 🔍 **Understand** the current test strategy, automation coverage, and release process.
2. 🚧 **Identify bottlenecks** — long regression cycles, high production bug rates.
3. 🤖 **Strengthen automated regression** around critical paths.
4. 🤝 **Improve QA collaboration** in refinement and planning sessions.
5. 🔧 **Reduce flaky tests** and make results more visible and reliable.

---

### 🔹 Closing — Candidate's Questions

**🧑‍💼 Interviewer:**
> Thank you! Do you have any **questions for us**?

**👩‍💻 Candidate:**
Absolutely! I'd love to understand:

- 🔄 How is **QA currently integrated** into your development process?
- 🛠️ What **tools do you use** for automation and CI/CD?
- 🎯 What are your **main quality challenges** right now?

---

## 📚 Vocabulary Highlights

| 🔤 Term | 💡 Meaning |
|---------|-----------|
| **Flaky test** | A test that passes sometimes and fails other times without code changes |
| **Smoke test** | A quick set of tests to verify basic functionality after a deployment |
| **UAT** | User Acceptance Testing — validates the system from the end user's perspective |
| **POM** | Page Object Model — a design pattern to organize UI test code |
| **ROI** | Return on Investment — benefit vs. cost of a testing effort |
| **Race condition** | A bug where behavior depends on the timing of uncontrollable events |
| **Quarantine** | Temporarily isolating flaky/unstable tests from the main test suite |

---

> 💡 **Study Tip:** Practice this dialogue out loud! Record yourself answering each question and compare with the suggested answers. Focus on **clear, confident delivery** and **technical vocabulary**.---

### 🔹 Question 2 — Verification vs. Validation

**🧑‍💼 Interviewer:**
> What's the difference between **verification** and **validation** in software testing?

**👩‍💻 Candidate:**
Great question! Here's how I think about it:

- ✅ **Verification** — *"Are we building the product right?"* — checks if the software meets the specified requirements and design (documents, specs, code reviews).
- ✅ **Validation** — *"Are we building the right product?"* — checks if the software actually satisfies **user needs and business goals** (real usage, acceptance testing).

In short: verification is about correctness, validation is about value.

---

### 🔹 Question 3 — Testing Levels

**🧑‍💼 Interviewer:**
> Can you explain the different **levels of testing**?

**👩‍💻 Candidate:**
Absolutely! The main levels are:

| 🏗️ Level | 📋 Focus |
|----------|---------|
| **Unit Testing** | Small pieces of code — functions or methods, usually written by developers |
| **Integration Testing** | How different modules or services work together |
| **System Testing** | The complete integrated system against all requirements |
| **Acceptance Testing** | User/business perspective — often done as UAT (User Acceptance Testing) |

---

### 🔹 Question 4 — Types of Testing

**🧑‍💼 Interviewer:**
> What types of testing do you usually perform?

**👩‍💻 Candidate:**
It depends on the project, but my typical toolkit includes:

- 🔍 **Functional testing**
- 🔁 **Regression testing**
- 💨 **Smoke & sanity testing**
- 🗺️ **Exploratory testing**
- 🌐 **API testing**
- ⚡ **Performance testing** *(usually with a specialized team)*
- 🤖 **Automated testing** for regression and critical paths

---

### 🔹 Question 5 — What to Automate?

**🧑‍💼 Interviewer:**
> How do you decide **what to automate** and what to keep as manual tests?

**👩‍💻 Candidate:**
I consider several factors:

- 🔄 **Frequency of execution** — High-frequency tests are strong candidates for automation.
- 🏗️ **Stability of functionality** — Stable features work well; unstable ones cause flaky tests.
- 💼 **Business criticality** — Critical paths and core workflows should always be automated.
- 🧩 **Complexity** — If automation is extremely complex and cheaper to test manually, I keep it manual.
- 📊 **ROI** — I evaluate maintenance cost versus time saved in regression cycles.

---

### 🔹 Question 6 — Automation Tools & Frameworks

**🧑‍💼 Interviewer:**
> Which **automation tools and frameworks** do you have experience with?

**👩‍💻 Candidate:**
Here's my stack:

| 🧰 Category | 🛠️ Tools |
|-------------|---------|
| **UI Testing** | Selenium WebDriver, Cypress, Playwright |
| **API Testing** | Postman, REST Assured, Cypress |
| **Unit Testing** | JUnit, TestNG, Jest |
| **CI/CD** | Jenkins, GitLab CI, GitHub Actions |

---

### 🔹 Question 7 — Framework Structure

**🧑‍💼 Interviewer:**
> How do you **structure** your automated test framework?

**👩‍💻 Candidate:**
I aim for a framework that is **modular, readable, and easy to maintain**:

- 📁 **Clear folder structure** — separating tests, page objects, utilities, test data, and configs
- 🧱 **Page Object Model (POM)** for UI tests to avoid code duplication
- 🔧 **Reusable helpers** for common actions like login, data setup, and API calls
- ⚙️ **Config files** for environment URLs, credentials (secured!), and browser settings
- ✅ Tests should be **readable, independent, and not tightly coupled** to each other

---

### 🔹 Question 8 — QA in Agile

**🧑‍💼 Interviewer:**
> Can you describe your **test process in an agile environment**?

**👩‍💻 Candidate:**
In agile, I'm involved from day one:

- 📋 **Refinement** — I join grooming sessions to clarify requirements and help define acceptance criteria and test scenarios.
- 📅 **Planning** — I estimate testing effort and identify risks early.
- 🚀 **During the sprint** — I write test cases, collaborate with developers, and start automation in parallel when possible.
- 🔄 **Continuous testing** — I run tests in CI, provide fast feedback, and retest issues quickly.
- 🔎 **Review & Retro** — I share feedback on what worked, what didn't, and how to improve quality.

---

### 🔹 Question 9 — Regression on Frequent Releases

**🧑‍💼 Interviewer:**
> How do you handle **regression testing** when there are frequent releases?

**👩‍💻 Candidate:**
I rely heavily on automation for regression. My approach:

- 🤖 Maintain an automated **regression suite** covering critical functionalities.
- 🎯 For areas not yet automated, use **risk-based testing** to prioritize manual regression.
- 💨 Run **smoke tests after every deployment** to verify main flows still work in production or staging.

---

### 🔹 Question 10 — Risk-Based Testing

**🧑‍💼 Interviewer:**
> What is **risk-based testing**?

**👩‍💻 Candidate:**
Risk-based testing means **prioritizing tests based on:**

1. 📉 **Probability of failure** — How likely is this area to break?
2. 💥 **Impact of failure** — What happens if it does break?

Modules that are business-critical or highly complex receive more testing effort and earlier attention. This is especially valuable when **time and resources are limited**.

---

### 🔹 Question 11 — Test Coverage

**🧑‍💼 Interviewer:**
> How do you ensure **good test coverage**?

**👩‍💻 Candidate:**
I combine multiple approaches:

- 📝 Analyze **requirements and user stories** to derive test cases.
- 🔗 Maintain **traceability** between requirements and tests.
- 🗺️ Perform **exploratory testing** to catch issues beyond scripted tests.
- 🤝 Collaborate with developers to understand **complex flows and edge cases**.
- 📊 Use **code coverage tools** (for unit/integration tests) as an additional indicator.

---

### 🔹 Question 12 — Flaky Tests

**🧑‍💼 Interviewer:**
> How do you deal with **flaky automated tests**?

**👩‍💻 Candidate:**
First, I identify the root cause — is the flakiness related to **timing, environment, data, or external services?** Then I:

- ⏱️ Improve **synchronization** — use explicit waits instead of arbitrary `sleep()`.
- 🗄️ Stabilize **test data** and remove dependencies between tests.
- 🔌 **Mock or stub** unstable external dependencies when appropriate.
- 📸 Improve **error logging and screenshots** to analyze failures faster.
- 🚧 If a test stays flaky with low value, I **quarantine** it, then refactor or replace it.

---

### 🔹 Question 13 — API Testing

**🧑‍💼 Interviewer:**
> What's your experience with **API testing**?

**👩‍💻 Candidate:**
I've tested REST APIs using **Postman** for exploration and **REST Assured / Cypress** for automation. I validate:

- ✅ Response **status codes**
- 📦 Response **body and schema**
- 🔐 **Headers and authentication**
- ⚠️ **Error handling**
- 🔁 **Edge cases and negative scenarios**

I also integrate API tests into **CI/CD** to run on every build or merge to the main branch.

---

### 🔹 Question 14 — CI/CD Integration

**🧑‍💼 Interviewer:**
> How do you **integrate your tests into a CI/CD pipeline**?

**👩‍💻 Candidate:**
I work with DevOps or developers to:

- ⚙️ Add **test execution steps** to the pipeline *(unit → API → UI tests)*.
- 📊 Configure **test reports** (JUnit XML, HTML dashboards).
- 🚨 Set **quality gates** — fail the build if critical tests fail.
- ⚡ **Parallelize tests** to reduce execution time.

This ensures fast, **visible feedback** for the entire team.

---

### 🔹 Question 15 — Challenging Bug

**🧑‍💼 Interviewer:**
> Can you describe a **challenging bug** you found and how you handled it?

**👩‍💻 Candidate:**
In one project, I found an **intermittent bug in the checkout process** that only occurred under specific load conditions and for certain user roles.

I reproduced it by correlating:
- 📋 API logs
- 🖥️ Frontend console logs
- 🗄️ Database queries

I then created a clear, detailed **bug report** with steps, environment, data used, screenshots, and logs. This helped developers quickly identify a **race condition in the backend**. After the fix, I added automated tests and performance checks to prevent regression.

---

### 🔹 Question 16 — Writing a Good Bug Report

**🧑‍💼 Interviewer:**
> How do you write a **good bug report**?

**👩‍💻 Candidate:**
A great bug report should include:

| 📝 Field | 📋 Description |
|---------|---------------|
| **Title** | Clear summary of the problem |
| **Environment** | Version, environment, browser, device |
| **Steps to Reproduce** | Precise and repeatable steps |
| **Expected vs. Actual** | Clear description of the difference |
| **Attachments** | Screenshots, logs, or videos |
| **Severity & Priority** | Business impact classification |

This saves everyone time and avoids unnecessary back-and-forth. 💡

---

### 🔹 Question 17 — Collaboration

**🧑‍💼 Interviewer:**
> How do you **collaborate with developers and product owners**?

**👩‍💻 Candidate:**
I treat it as a **partnership**, not gatekeeping. My approach:

- 🤝 **With Developers** — Join discussions early, test early builds, provide fast feedback, and keep an open channel during development.
- 💼 **With Product Owners** — Discuss quality trade-offs, help prioritize issues based on user impact, and clarify acceptance criteria.

I also review requirements, surface edge cases, and share test scenarios to build **shared ownership of quality**.

---

### 🔹 Question 18 — Test Documentation

**🧑‍💼 Interviewer:**
> What's your approach to **test documentation**?

**👩‍💻 Candidate:**
I prefer **lightweight but useful** documentation:

- 📋 For regression — I maintain test cases or checklists for critical areas.
- 🗺️ For exploratory testing — I use charters and short session notes.
- 🔄 I keep docs up to date when features change.
- 📖 I document the **test strategy and coverage** for key projects so new team members onboard quickly.

---

### 🔹 Question 19 — Staying Up to Date

**🧑‍💼 Interviewer:**
> How do you **stay current** with QA and automation best practices?

**👩‍💻 Candidate:**
I stay sharp through:

- 📰 **Blogs and communities** — QA/Dev channels and newsletters
- 📚 **Official documentation** for new tools
- 🧪 **Side projects** to experiment with new frameworks
- 🔍 **Code reviews and retrospectives** with teammates
- 🎤 When I discover something useful, I **bring it to the team** (e.g., better assertion libraries or improved test data patterns)

---

### 🔹 Question 20 — QA's Role in Agile

**🧑‍💼 Interviewer:**
> What do you think is the **role of QA in an agile team**?

**👩‍💻 Candidate:**
QA's role goes far beyond finding bugs — it's about **helping the whole team deliver quality**:

- 🛡️ **Prevent defects** by participating in refinement and design discussions.
- 📊 **Make quality visible** through tests and metrics.
- ⚡ **Provide fast feedback** through automation and testing.
- 🤝 **Encourage shared ownership** — quality is everyone's responsibility, not just QA.

---

### 🔹 Question 21 — Improving QA Processes

**🧑‍💼 Interviewer:**
> Where do you see **opportunities to improve our QA process** if you join?

**👩‍💻 Candidate:**
Initially, I would:

1. 🔍 **Understand** the current test strategy, automation coverage, and release process.
2. 🚧 **Identify bottlenecks** — long regression cycles, high production bug rates.
3. 🤖 **Strengthen automated regression** around critical paths.
4. 🤝 **Improve QA collaboration** in refinement and planning sessions.
5. 🔧 **Reduce flaky tests** and make results more visible and reliable.

---

### 🔹 Closing — Candidate's Questions

**🧑‍💼 Interviewer:**
> Thank you! Do you have any **questions for us**?

**👩‍💻 Candidate:**
Absolutely! I'd love to understand:

- 🔄 How is **QA currently integrated** into your development process?
- 🛠️ What **tools do you use** for automation and CI/CD?
- 🎯 What are your **main quality challenges** right now?

---

## 📚 Vocabulary Highlights

| 🔤 Term | 💡 Meaning |
|---------|-----------|
| **Flaky test** | A test that passes sometimes and fails other times without code changes |
| **Smoke test** | A quick set of tests to verify basic functionality after a deployment |
| **UAT** | User Acceptance Testing — validates the system from the end user's perspective |
| **POM** | Page Object Model — a design pattern to organize UI test code |
| **ROI** | Return on Investment — benefit vs. cost of a testing effort |
| **Race condition** | A bug where behavior depends on the timing of uncontrollable events |
| **Quarantine** | Temporarily isolating flaky/unstable tests from the main test suite |

---

> 💡 **Study Tip:** Practice this dialogue out loud! Record yourself answering each question and compare with the suggested answers. Focus on **clear, confident delivery** and **technical vocabulary**.---

### 🔹 Question 2 — Verification vs. Validation

**🧑‍💼 Interviewer:**
> What's the difference between **verification** and **validation** in software testing?

**👩‍💻 Candidate:**
Great question! Here's how I think about it:

- ✅ **Verification** — *"Are we building the product right?"* — checks if the software meets the specified requirements and design (documents, specs, code reviews).
- ✅ **Validation** — *"Are we building the right product?"* — checks if the software actually satisfies **user needs and business goals** (real usage, acceptance testing).

In short: verification is about correctness, validation is about value.

---

### 🔹 Question 3 — Testing Levels

**🧑‍💼 Interviewer:**
> Can you explain the different **levels of testing**?

**👩‍💻 Candidate:**
Absolutely! The main levels are:

| 🏗️ Level | 📋 Focus |
|----------|---------|
| **Unit Testing** | Small pieces of code — functions or methods, usually written by developers |
| **Integration Testing** | How different modules or services work together |
| **System Testing** | The complete integrated system against all requirements |
| **Acceptance Testing** | User/business perspective — often done as UAT (User Acceptance Testing) |

---

### 🔹 Question 4 — Types of Testing

**🧑‍💼 Interviewer:**
> What types of testing do you usually perform?

**👩‍💻 Candidate:**
It depends on the project, but my typical toolkit includes:

- 🔍 **Functional testing**
- 🔁 **Regression testing**
- 💨 **Smoke & sanity testing**
- 🗺️ **Exploratory testing**
- 🌐 **API testing**
- ⚡ **Performance testing** *(usually with a specialized team)*
- 🤖 **Automated testing** for regression and critical paths

---

### 🔹 Question 5 — What to Automate?

**🧑‍💼 Interviewer:**
> How do you decide **what to automate** and what to keep as manual tests?

**👩‍💻 Candidate:**
I consider several factors:

- 🔄 **Frequency of execution** — High-frequency tests are strong candidates for automation.
- 🏗️ **Stability of functionality** — Stable features work well; unstable ones cause flaky tests.
- 💼 **Business criticality** — Critical paths and core workflows should always be automated.
- 🧩 **Complexity** — If automation is extremely complex and cheaper to test manually, I keep it manual.
- 📊 **ROI** — I evaluate maintenance cost versus time saved in regression cycles.

---

### 🔹 Question 6 — Automation Tools & Frameworks

**🧑‍💼 Interviewer:**
> Which **automation tools and frameworks** do you have experience with?

**👩‍💻 Candidate:**
Here's my stack:

| 🧰 Category | 🛠️ Tools |
|-------------|---------|
| **UI Testing** | Selenium WebDriver, Cypress, Playwright |
| **API Testing** | Postman, REST Assured, Cypress |
| **Unit Testing** | JUnit, TestNG, Jest |
| **CI/CD** | Jenkins, GitLab CI, GitHub Actions |

---

### 🔹 Question 7 — Framework Structure

**🧑‍💼 Interviewer:**
> How do you **structure** your automated test framework?

**👩‍💻 Candidate:**
I aim for a framework that is **modular, readable, and easy to maintain**:

- 📁 **Clear folder structure** — separating tests, page objects, utilities, test data, and configs
- 🧱 **Page Object Model (POM)** for UI tests to avoid code duplication
- 🔧 **Reusable helpers** for common actions like login, data setup, and API calls
- ⚙️ **Config files** for environment URLs, credentials (secured!), and browser settings
- ✅ Tests should be **readable, independent, and not tightly coupled** to each other

---

### 🔹 Question 8 — QA in Agile

**🧑‍💼 Interviewer:**
> Can you describe your **test process in an agile environment**?

**👩‍💻 Candidate:**
In agile, I'm involved from day one:

- 📋 **Refinement** — I join grooming sessions to clarify requirements and help define acceptance criteria and test scenarios.
- 📅 **Planning** — I estimate testing effort and identify risks early.
- 🚀 **During the sprint** — I write test cases, collaborate with developers, and start automation in parallel when possible.
- 🔄 **Continuous testing** — I run tests in CI, provide fast feedback, and retest issues quickly.
- 🔎 **Review & Retro** — I share feedback on what worked, what didn't, and how to improve quality.

---

### 🔹 Question 9 — Regression on Frequent Releases

**🧑‍💼 Interviewer:**
> How do you handle **regression testing** when there are frequent releases?

**👩‍💻 Candidate:**
I rely heavily on automation for regression. My approach:

- 🤖 Maintain an automated **regression suite** covering critical functionalities.
- 🎯 For areas not yet automated, use **risk-based testing** to prioritize manual regression.
- 💨 Run **smoke tests after every deployment** to verify main flows still work in production or staging.

---

### 🔹 Question 10 — Risk-Based Testing

**🧑‍💼 Interviewer:**
> What is **risk-based testing**?

**👩‍💻 Candidate:**
Risk-based testing means **prioritizing tests based on:**

1. 📉 **Probability of failure** — How likely is this area to break?
2. 💥 **Impact of failure** — What happens if it does break?

Modules that are business-critical or highly complex receive more testing effort and earlier attention. This is especially valuable when **time and resources are limited**.

---

### 🔹 Question 11 — Test Coverage

**🧑‍💼 Interviewer:**
> How do you ensure **good test coverage**?

**👩‍💻 Candidate:**
I combine multiple approaches:

- 📝 Analyze **requirements and user stories** to derive test cases.
- 🔗 Maintain **traceability** between requirements and tests.
- 🗺️ Perform **exploratory testing** to catch issues beyond scripted tests.
- 🤝 Collaborate with developers to understand **complex flows and edge cases**.
- 📊 Use **code coverage tools** (for unit/integration tests) as an additional indicator.

---

### 🔹 Question 12 — Flaky Tests

**🧑‍💼 Interviewer:**
> How do you deal with **flaky automated tests**?

**👩‍💻 Candidate:**
First, I identify the root cause — is the flakiness related to **timing, environment, data, or external services?** Then I:

- ⏱️ Improve **synchronization** — use explicit waits instead of arbitrary `sleep()`.
- 🗄️ Stabilize **test data** and remove dependencies between tests.
- 🔌 **Mock or stub** unstable external dependencies when appropriate.
- 📸 Improve **error logging and screenshots** to analyze failures faster.
- 🚧 If a test stays flaky with low value, I **quarantine** it, then refactor or replace it.

---

### 🔹 Question 13 — API Testing

**🧑‍💼 Interviewer:**
> What's your experience with **API testing**?

**👩‍💻 Candidate:**
I've tested REST APIs using **Postman** for exploration and **REST Assured / Cypress** for automation. I validate:

- ✅ Response **status codes**
- 📦 Response **body and schema**
- 🔐 **Headers and authentication**
- ⚠️ **Error handling**
- 🔁 **Edge cases and negative scenarios**

I also integrate API tests into **CI/CD** to run on every build or merge to the main branch.

---

### 🔹 Question 14 — CI/CD Integration

**🧑‍💼 Interviewer:**
> How do you **integrate your tests into a CI/CD pipeline**?

**👩‍💻 Candidate:**
I work with DevOps or developers to:

- ⚙️ Add **test execution steps** to the pipeline *(unit → API → UI tests)*.
- 📊 Configure **test reports** (JUnit XML, HTML dashboards).
- 🚨 Set **quality gates** — fail the build if critical tests fail.
- ⚡ **Parallelize tests** to reduce execution time.

This ensures fast, **visible feedback** for the entire team.

---

### 🔹 Question 15 — Challenging Bug

**🧑‍💼 Interviewer:**
> Can you describe a **challenging bug** you found and how you handled it?

**👩‍💻 Candidate:**
In one project, I found an **intermittent bug in the checkout process** that only occurred under specific load conditions and for certain user roles.

I reproduced it by correlating:
- 📋 API logs
- 🖥️ Frontend console logs
- 🗄️ Database queries

I then created a clear, detailed **bug report** with steps, environment, data used, screenshots, and logs. This helped developers quickly identify a **race condition in the backend**. After the fix, I added automated tests and performance checks to prevent regression.

---

### 🔹 Question 16 — Writing a Good Bug Report

**🧑‍💼 Interviewer:**
> How do you write a **good bug report**?

**👩‍💻 Candidate:**
A great bug report should include:

| 📝 Field | 📋 Description |
|---------|---------------|
| **Title** | Clear summary of the problem |
| **Environment** | Version, environment, browser, device |
| **Steps to Reproduce** | Precise and repeatable steps |
| **Expected vs. Actual** | Clear description of the difference |
| **Attachments** | Screenshots, logs, or videos |
| **Severity & Priority** | Business impact classification |

This saves everyone time and avoids unnecessary back-and-forth. 💡

---

### 🔹 Question 17 — Collaboration

**🧑‍💼 Interviewer:**
> How do you **collaborate with developers and product owners**?

**👩‍💻 Candidate:**
I treat it as a **partnership**, not gatekeeping. My approach:

- 🤝 **With Developers** — Join discussions early, test early builds, provide fast feedback, and keep an open channel during development.
- 💼 **With Product Owners** — Discuss quality trade-offs, help prioritize issues based on user impact, and clarify acceptance criteria.

I also review requirements, surface edge cases, and share test scenarios to build **shared ownership of quality**.

---

### 🔹 Question 18 — Test Documentation

**🧑‍💼 Interviewer:**
> What's your approach to **test documentation**?

**👩‍💻 Candidate:**
I prefer **lightweight but useful** documentation:

- 📋 For regression — I maintain test cases or checklists for critical areas.
- 🗺️ For exploratory testing — I use charters and short session notes.
- 🔄 I keep docs up to date when features change.
- 📖 I document the **test strategy and coverage** for key projects so new team members onboard quickly.

---

### 🔹 Question 19 — Staying Up to Date

**🧑‍💼 Interviewer:**
> How do you **stay current** with QA and automation best practices?

**👩‍💻 Candidate:**
I stay sharp through:

- 📰 **Blogs and communities** — QA/Dev channels and newsletters
- 📚 **Official documentation** for new tools
- 🧪 **Side projects** to experiment with new frameworks
- 🔍 **Code reviews and retrospectives** with teammates
- 🎤 When I discover something useful, I **bring it to the team** (e.g., better assertion libraries or improved test data patterns)

---

### 🔹 Question 20 — QA's Role in Agile

**🧑‍💼 Interviewer:**
> What do you think is the **role of QA in an agile team**?

**👩‍💻 Candidate:**
QA's role goes far beyond finding bugs — it's about **helping the whole team deliver quality**:

- 🛡️ **Prevent defects** by participating in refinement and design discussions.
- 📊 **Make quality visible** through tests and metrics.
- ⚡ **Provide fast feedback** through automation and testing.
- 🤝 **Encourage shared ownership** — quality is everyone's responsibility, not just QA.

---

### 🔹 Question 21 — Improving QA Processes

**🧑‍💼 Interviewer:**
> Where do you see **opportunities to improve our QA process** if you join?

**👩‍💻 Candidate:**
Initially, I would:

1. 🔍 **Understand** the current test strategy, automation coverage, and release process.
2. 🚧 **Identify bottlenecks** — long regression cycles, high production bug rates.
3. 🤖 **Strengthen automated regression** around critical paths.
4. 🤝 **Improve QA collaboration** in refinement and planning sessions.
5. 🔧 **Reduce flaky tests** and make results more visible and reliable.

---

### 🔹 Closing — Candidate's Questions

**🧑‍💼 Interviewer:**
> Thank you! Do you have any **questions for us**?

**👩‍💻 Candidate:**
Absolutely! I'd love to understand:

- 🔄 How is **QA currently integrated** into your development process?
- 🛠️ What **tools do you use** for automation and CI/CD?
- 🎯 What are your **main quality challenges** right now?

---

## 📚 Vocabulary Highlights

| 🔤 Term | 💡 Meaning |
|---------|-----------|
| **Flaky test** | A test that passes sometimes and fails other times without code changes |
| **Smoke test** | A quick set of tests to verify basic functionality after a deployment |
| **UAT** | User Acceptance Testing — validates the system from the end user's perspective |
| **POM** | Page Object Model — a design pattern to organize UI test code |
| **ROI** | Return on Investment — benefit vs. cost of a testing effort |
| **Race condition** | A bug where behavior depends on the timing of uncontrollable events |
| **Quarantine** | Temporarily isolating flaky/unstable tests from the main test suite |

---

> 💡 **Study Tip:** Practice this dialogue out loud! Record yourself answering each question and compare with the suggested answers. Focus on **clear, confident delivery** and **technical vocabulary**.
