---
layout: default
title: Supporting Our AI Overlords (SAO)
---

<style>
  .organizer-img {
    border-radius: 50%;
    object-fit: cover;
  }
  .page-header .btn {
    display: none;
  }
</style>

## Overview

**A workshop on agent-first data systems, agents for data science and analytics, and the future of data systems (part of [CAIS 2026](https://www.caisconf.org/), The ACM Conference on AI and Agentic Systems, May 26, 2026, San Jose, California)**

Today's data systems were designed for a small number of careful human operators. But a growing share of analytics, data engineering, and ML workflows is increasingly being delegated to AI agents. This workshop will bring together researchers and practitioners to study how data systems should evolve for agents, and how agents themselves can help shape better systems.

The workshop is born out of recent work in data management (e.g. [Supporting Our AI Overlords](https://arxiv.org/pdf/2509.00997) and [Trustworthy AI in the Agentic Lakehouse](https://arxiv.org/abs/2511.16402)), but generalizes to other directions at the intersection of data and agents. Our goal is to explore the full design space where **data systems and AI agents meet**, and we are open to creative interpretations of the theme (including demos, lessons from the trenches, preliminary results, controversial positions, and failure stories).

- [Organizers](#organizers)
- [Invited Speakers](#invited-speakers)
- [Call for Papers](#call-for-papers)
- [Awards](#awards)
- [Important Dates](#important-dates)
- [Panel](#panel)
- [Program](#program-tentative)
- [Contact](#contact)

The workshop is sponsored by <a href="https://www.mozilla.ai/" target="_blank">Mozilla AI</a> and <a href="https://www.bauplanlabs.com/" target="_blank">Bauplan Labs</a>.

<p>
  <a href="https://www.mozilla.ai/" target="_blank"><img src="images/mozillaai-logo-black.png" alt="Mozilla AI" height="40"></a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://www.bauplanlabs.com/" target="_blank"><img src="images/bauplan-logo-color-on-white.png" alt="Bauplan Labs" height="60"></a>
</p>

## Organizers

<table>
  <tr>
    <td align="center" width="33%">
      <img src="images/elaine-ang.jpg" alt="Elaine Ang" width="160" height="160" class="organizer-img"><br><br>
      <strong>Elaine Ang</strong><br>
      <em>Columbia University</em>
    </td>
    <td align="center" width="33%">
      <img src="images/shu-liu.jpg" alt="Shu Liu" width="160" height="160" class="organizer-img"><br><br>
      <strong>Shu Liu</strong><br>
      <em>UC Berkeley</em>
    </td>
    <td align="center" width="33%">
      <img src="images/aditya-parameswaran.jpg" alt="Aditya Parameswaran" width="160" height="160" class="organizer-img"><br><br>
      <strong>Aditya Parameswaran</strong><br>
      <em>UC Berkeley</em>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <img src="images/john-dickerson.jpg" alt="John Dickerson" width="160" height="160" class="organizer-img"><br><br>
      <strong>John Dickerson</strong><br>
      <em>Mozilla AI</em>
    </td>
    <td align="center" width="33%">
      <img src="images/jonathan-frankle.jpg" alt="Jonathan Frankle" width="160" height="160" class="organizer-img"><br><br>
      <strong>Jonathan Frankle</strong><br>
      <em>Databricks</em>
    </td>
    <td align="center" width="33%">
      <img src="images/jacopo-tagliabue.jpg" alt="Jacopo Tagliabue" width="160" height="160" class="organizer-img"><br><br>
      <strong>Jacopo Tagliabue</strong><br>
      <em>Bauplan Labs</em>
    </td>
  </tr>
</table>

---

## Invited Speakers

<table>
  <tr>
    <td align="center" width="33%">
      <img src="images/andy-pavlo.JPG" alt="Andy Pavlo" width="160" height="160" class="organizer-img"><br><br>
      <strong>Andy Pavlo</strong> (left)<br>
      <em>Carnegie Mellon University</em>
    </td>
    <td align="center" width="33%">
      <img src="images/Aaron_Katz.jpeg" alt="Aaron Katz" width="160" height="160" class="organizer-img"><br><br>
      <strong>Aaron Katz</strong><br>
      <em>ClickHouse, Inc.</em>
    </td>
    <td align="center" width="33%">
      <img src="images/speaker-placeholder.svg" alt="Invited Speaker 3" width="160" height="160" class="organizer-img"><br><br>
      <strong>Speaker TBD</strong><br>
      <em>Affiliation TBD</em>
    </td>
  </tr>
</table>

### Speaker bios

**Andy Pavlo** — Andy Pavlo is an Associate Professor with Indefinite Tenure of Databaseology in the Computer Science Department at Carnegie Mellon University. His (unnatural) infatuation with database systems has inadvertently caused him to incur several distinctions, such as IEEE TCDE Ramez Elmasri Outstanding Database Education Award (2026), VLDB Early Career Award (2021), NSF CAREER (2019), Sloan Fellowship (2018), and the ACM SIGMOD Jim Gray Best Dissertation Award (2014). He also was the CEO & co-founder of the OtterTune database tuning start-up (2020-2024), but it died an untimely death. He is currently the CEO and co-founder of "SO-YOU-DONT-HAVE-TO INCORPORATED'); DROP TABLE companies; --" (2025-). Andy earned his Ph.D. in 2013 at Brown University under Stan Zdonik and Mike Stonebraker. He knows some pile about databases.

**Aaron Katz** — Aaron Katz is currently Co-Founder and CEO of ClickHouse, Inc., the company behind ClickHouse, the industry-leading online analytical processing database management system. With more than 20 years of experience building and leading global teams, Aaron brings a unique perspective with a focus on international business, scale, and distribution. Most recently, Aaron led the GTM efforts at Elastic (NYSE: ESTC) between 2014 and 2020 where he helped grow the company from ~$5M in revenue when he joined to >$500M in revenue as a Section 16 officer when he left. Prior to Elastic, Aaron spent 12 years (2002 - 2014) at salesforce.com (NYSE: CRM) where he held a variety of international sales leadership roles and helped grow the company from a private, ~200 employee startup to a >$200B market leader. Aaron holds a Bachelor's of Science degree in Managerial Economics from the University of California, Davis and lives in the San Francisco Bay Area with his wife and two children.

**Speaker TBD** — Bio TBD.

---

## Call for Papers

We invite submissions on the emerging intersection of **AI agents** and **data systems**. Drawing from the workshop [manifesto](papers/CAIS_2026_workshop_online.pdf), we are mainly interested in contributions along these research directions:

1. **Productionizing agentic workloads.** Capturing the nuances of agentic reasoning and engineering techniques across the entire data lifecycle.
2. **Optimizing agent semantics.** Exploring the transition from deterministic SQL execution to agent-driven pipelines.
3. **Data systems for agents.** Rethinking core system guarantees from the ground up to support non-human workloads.
4. **Agents for system design.** Exploring the "self-driving" potential of the stack, where agents autonomously design, tune, and maintain the very infrastructure they inhabit.

Examples of topics include, but are not limited to:

- Agent-first OLAP architectures for safe, reproducible, and cost-efficient analytics
- Agentic analytics workflows, including human-in-the-loop patterns and production failure modes
- Evaluation methodologies, benchmarks, and workload traces for data agents
- LLM-assisted optimization and tuning for data systems
- War stories and postmortems from production deployments
- Agentic workflows for data engineering and data science
- Operational reliability for agent-driven automation, including observability, guardrails, governance, and cost controls
- Work-in-progress and early-stage results that showcase novel ideas or promising directions, even if not yet fully evaluated

Generally speaking, we will be open to creative interpretations of the workshop themes as long as contributions sit at the intersection of data and agents.

**[Submit your paper here](https://sao-cais26workshop.hotcrp.com/)**

### Submission formats

We solicit:

- **Short research and position papers**: up to 4 pages plus references
- **Late-breaking results / extended abstracts**: up to 2 pages plus references

*Format*: The ACM sigconf double-column format ([templates here, including Overleaf](https://www.acm.org/publications/proceedings-template)) should be used for all submissions.

Submissions will be reviewed in a **single-blind** process by members of the committee. We welcome overlapping submissions with other venues: SAO is non-archival, but accepted papers will be featured on the website. Extended abstracts are particularly encouraged for work-in-progress ideas and early-stage explorations. Production war stories and postmortems need not be technically novel as long as they provide interesting insights and lessons relevant to the workshop theme. Accepted contributions will be presented at the workshop, and accepted materials will also be archived on the workshop website. For more background, recent relevant literature, and inspiring use cases, see our [workshop proposal](papers/CAIS_2026_workshop_online.pdf).

### Program Committee

- **Aldrin Montana** — Bauplan Labs
- **Alperen Keleş** — University of Maryland
- **Bonnie Xu** — OpenAI
- **Davide Eynard** — Mozilla AI
- **Eugene Wu** — Columbia University
- **Federico Bianchi** — Together AI
- **Gaetano Rossiello** — IBM
- **Jeremiah Milbauer** — CMU
- **Joseph Axisa** — Google
- **Nandana Mihindukulasooriya** — IBM
- **Nicole Rose Schneider** — University of Maryland
- **Sesh Nalla** — Datadog
- **Stephanie Wang** — MongoDB
- **Tao Ye** — Lyft
- **Till Döhmen** — MotherDuck

---

## Awards

We are pleased to offer awards for outstanding contributions:

- **Best Paper Award** — with a monetary prize, recognizing the strongest accepted contribution to the workshop.
- **Best Student-Led Paper Award** — with a monetary prize, for the best paper with a student as the primary author.

Awards will be presented at the end of the day during a social gathering with drinks and informal discussion. Stay tuned!

---

## Important Dates

| Milestone | Date |
|---|---|
| Submission deadline | Tue, May 5, 2026 |
| Accept / reject notification | Fri, May 8, 2026 |
| Camera-ready | Tue, May 12, 2026 |
| Workshop | Tue, May 26, 2026 |

---

## Panel

The workshop will conclude with a panel discussion bringing together different perspectives on agentic data systems, from infrastructure and optimization to safety and deployment. The panel will be moderated by [Ciro Greco](https://www.linkedin.com/in/cirogreco/). More panelists will be added soon.

<table>
  <tr>
    <td align="center" width="50%">
      <img src="images/Ashish_Kumar.jpg" alt="Ashish Kumar" width="160" height="160" class="organizer-img"><br><br>
      <strong>Ashish Kumar</strong><br>
      <em>MongoDB</em>
    </td>
    <td align="center" width="50%">
      <img src="images/Anant_Jhingran.png" alt="Anant Jhingran" width="160" height="160" class="organizer-img"><br><br>
      <strong>Anant Jhingran</strong><br>
      <em>IBM Software</em>
    </td>
  </tr>
</table>

### Panelist bios

**Ashish Kumar** — Ashish Kumar is a Technical Fellow at MongoDB, where he focuses on architectural improvements across the company's product offerings. He joined MongoDB through the acquisition of Grainite, where he was Co-Founder and CEO. At Grainite, he led the development of a first-of-its-kind transactional database unifying native stream storage and parallel processing. Previously, Ashish spent 11 years as a Senior Engineering Director at Google, most recently leading the teams responsible for BigTable, Spanner, Datastore, and Firestore. During his tenure at Google, he also managed teams across Hardware, Display Ads, and Developer Tools. Earlier in his career, Ashish held executive roles at Sun Microsystems and infrastructure startups. He holds a Bachelor's in Business from SRCC, Delhi University.

**Anant Jhingran** — Anant Jhingran is CTO for IBM Software, a role he took on when StepZen — the GraphQL API company he co-founded and led as CEO — was acquired by IBM in February 2023. Before StepZen, he helped take Apigee public and through its acquisition by Google. Earlier at IBM, he was an IBM Fellow and CTO of the Information Management Division, shipping products that generated billions in revenue across IBM and Apigee. He holds a PhD in database systems from UC Berkeley and is a Distinguished Alumnus of IIT Delhi, with over a dozen patents and 20+ technical papers to his name.

---

## Program (Tentative)

**May 26, 2026 — In person in San Jose, California. The schedule below is subject to change.**

| Time | Activity | Details |
|---|---|---|
| 1:00 – 1:10 PM | Welcome | Introductory remarks |
| 1:10 – 1:50 PM | Keynote 1 | Industry keynote — Aaron Katz |
| 1:50 – 2:30 PM | Keynote 2 | Academic keynote — Andy Pavlo |
| 2:30 – 2:50 PM | Contributions | Lightning talks |
| 2:50 – 3:00 PM | Break | Coffee break |
| 3:00 – 3:25 PM | Contributions | Lightning talks |
| 3:25 – 4:05 PM | Keynote 3 | Invited keynote — TBD |
| 4:05 – 4:55 PM | Panel | Moderated by [Ciro Greco](https://www.linkedin.com/in/cirogreco/) |
| 4:55 – 5:00 PM | Closing | Closing remarks |
| After hours | Pizza, drinks, and awards | Informal discussion and awards |

---

## Contact

For questions, please contact:

**Jacopo Tagliabue**  
jacopo.tagliabue@bauplanlabs.com

**Elaine Ang**  
ra3448@columbia.edu