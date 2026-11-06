# Authority Trace

Independent review of execution integrity, business authority, infrastructure, and runtime authorisation.

Automated systems increasingly take actions with money, data, and access. Authority Trace checks that those actions do exactly what they are authorised to do.

## Who this is for

- **Teams building AI agents or automation** that move money, change records, or grant access, and need proof that each action was approved and ran as approved.
- **Payments and refund platforms** that want to confirm an approved refund is executed once, by the right service, within the approved limit.
- **SaaS companies with multi-tenant products** that need to confirm one customer's administrators cannot act on another customer's data or roles.
- **Companies with internal approval workflows** (finance, procurement, access requests) that want to check the approval rules are enforced in the software, not just in the policy document.
- **Startups preparing for a security or compliance review** that need an independent check of authority and execution before a customer or auditor asks.
- **Open-source maintainers** who want an outside review of their authorisation model before a release.

If you are not sure whether your system fits, describe it when you get in touch and we will tell you whether we can help.

## What we review

- **Execution integrity.** Each action traces to a valid approval, runs once, and cannot be changed after it is recorded. We look for gaps between what was approved and what ran, including retries, races, and replays.
- **Business authority.** Who or what may approve, initiate, and change an action, and whether those rules hold in code. This includes role changes, delegation, and tenant boundaries.
- **Infrastructure.** Service identities, shared credentials, network paths, and the configuration that decides who can do what.
- **Runtime authorisation.** Whether permissions are checked at the point of action, not only at login, and whether the checks agree with each other.

## How we work

1. **Scope.** We agree in writing what is in scope, which repositories or environments, and what is out of scope.
2. **Permission.** We test only systems you own or have written authorisation to test. We do not test production systems unless the scope says so.
3. **Review.** We read the code and configuration, and where it is agreed, run the system in a test environment to confirm each finding.
4. **Report.** For each finding: the location, what happens, the evidence needed to reproduce it, the impact, and a suggested fix.
5. **Follow-up.** We check fixes and re-run the reproduction where you ask us to.

## What you receive

- A written report, with findings ranked by severity and confidence.
- Reproduction steps for every finding we have confirmed. Findings we could not confirm are marked as such.
- A short summary for non-technical readers.
- A call to walk through the findings.

## What we do not do

- Test without written permission.
- Publish findings about any organisation without its agreement.
- Claim a finding we have not confirmed.

## Disclosure

Findings go to the system owner first, through a private channel the owner names. We follow the owner's disclosure policy where it has one. Where it does not, we give the owner a fixed window to respond and fix before any public discussion, and we agree the wording of any public statement with the owner first.

## Contact

Pavan Dev Singh Charak
charak1987@gmail.com
https://www.linkedin.com/in/pavancharak/

Tell us what you want reviewed and the systems involved. We will reply with a proposed scope and an estimate.
