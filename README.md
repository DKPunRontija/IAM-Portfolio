# IAM Implementation Portfolio

<!--
HOW TO USE THIS TEMPLATE
------------------------
This is your portfolio scaffold. The structure is already built for you.
Your job is to fill in each section with your own work as you go through the course.

1. Replace every [PLACEHOLDER] with your own details.
2. As you finish each part of the build, complete that capability's section below.
3. Drop your screenshots into /screenshots and your config files into /artifacts,
   then update the links.
4. Delete these HTML comment instructions once you have filled a section.

Do not try to fill it all at once. Complete a capability's section right after you
build it in the course, while it is fresh. That is how you end up with a portfolio
that actually reflects what you built and understand.

This portfolio is organized by CAPABILITY, not by course module. A recruiter or
interviewer should land here and immediately see what you can DO: onboard identities,
provision to targets, run the mover, certify access, federate with real protocols.
That framing is what turns a portfolio into interviews. You do not need every section
filled to start applying, build it up as you go, and lead with the capabilities you
are most confident explaining.
-->

**Name:** [DEEPA KUMARI PUN RONTIJA]
**LinkedIn:** [www.linkedin.com/in/deepa-kumari-pun-rontija-23a30753]
**GitHub:** [github.com/dkpunrontija]
**Status:** In progress

---

## What This Portfolio Shows

I built a complete IAM environment from scratch using midPoint (IGA), a simulated HR source, OpenLDAP (target directory), and Auth0 (access management and federation). The environment runs locally and replicates how IAM works on a real enterprise engagement, from HR-triggered identity lifecycle through governance and certification, to customer identity and federation with live protocols.

This repository documents my configuration, architectural decisions, and analysis for each capability I built. It is intended as portfolio evidence for IAM implementation and engineering roles.

<!-- Once you are further along, rewrite this in your own words and name the specific roles you are targeting. -->

---

## Environment

| Component | Purpose |
| --- | --- |
| midPoint | IGA platform: identity lifecycle, provisioning, reconciliation, access governance |
| SimplifyHR | HR source of truth: simulates an enterprise HRIS (Workday / SAP SuccessFactors equivalent) |
| OpenLDAP | Target directory: named user accounts provisioned here (Active Directory equivalent) |
| Auth0 | Access management and CIAM: OIDC, OAuth, and SAML federation |

---

## How This Repository Is Organized

- Each capability below has its own section: the problem it solves, what I built, the key concept, evidence, and a resume bullet.
- `/screenshots` holds the visual evidence for each capability.
- `/artifacts` holds the actual configuration I built: resource XML, Groovy mappings, role definitions. Screenshots show it happened; artifacts show how. Artifacts are your strongest evidence for a technical interviewer.

---

## Capabilities Built

