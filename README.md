Axiom — Independent AI Research
Project status: Active research prototype | Researcher: Chase Simmons, Mississippi, USA | Updated: October 14, 2026
What I'm working on
I'm developing Axiom, a locally operated AI research prototype to investigate whether persistent memory, verified experiences, and transparent decision histories can improve the reliability and accountability of AI decisions.
Why this matters
A system that makes decisions over time needs more than a conversation history. It should be possible to ask what it remembered, what evidence it relied on, what action it chose, what happened afterward, and whether outside influence affected the decision. Axiom is a practical testbed for studying those questions under constrained, reproducible conditions.
Work completed so far
The private working repository includes implemented components and software tests for:
- Persistent structured memory: storing and retrieving structured facts with atomic saves.
- Action and outcome tracking: linking an executed action to an observed outcome, including after task restarts.
- Decision provenance: recording evidence and outside influences used in decisions.
- Controlled evaluation preparation: synthetic learning/evaluation fixtures, a runner, and a bounded scheduler, with tests of software behavior.
- Safeguards and recovery: explicit action boundaries and durable records to support auditing and interruption recovery.
These are software-development milestones, not proof of autonomous learning, AGI, consciousness, or general independent judgment. The experimental learning results are not yet established. The full local repository and private memory data are not published here.
Proposed next experiment
Question: Do verified records of prior experiences and decision provenance improve subsequent decisions after an interruption or restart?
The plan is to compare fixed local-model conditions on synthetic tasks with different memory/provenance inputs, check that scoring matches the intended behavior, and document successes, failures, and resource costs. We will publish a sanitized benchmark, protocol, and results when they have been validated and reviewed for privacy.
Current limitation and funding request
Axiom has been developed primarily on an 8 GB, CPU-only Linux laptop. Limited memory and compute restrict controlled local-model experiments. I'm requesting $2,500 for an appropriately configured local AI workstation. The equipment would support reproducible experiments while allowing research data and project development to remain under local control.
The equipment request is for the next measurement stage, not a claim that advanced AI capabilities have already been achieved.
Evidence and transparency
This public page documents work in progress without publishing sensitive project records. The development repository contains source code, tests, and revision history. A reviewer-safe demonstration and a freshly captured test result can be provided or added here after review. Earlier local activity reported 401 passing software tests and one expected failure, but that figure should not be interpreted as a current, independently verified benchmark or as evidence of learning.
Research principle: Keep long-term scientific goals ambitious; make near-term claims only when supported by reproducible evidence.
