---
title: Tool
permalink: /tool/
---

OnlineProver is deployed at the [http://onlineprover.com/](http://onlineprover.com/).

## About
**OnlineProver** is an interactive proof assistant, tailored for the educational setting. The main features are a user-friendly interface for editing and checking proofs, and a DSL for specifying deduction systems and exercises about them. The user interface provides feedback directly in the derivation, based on error messages
provided by a proof checking web-service. A basic philosophy of the tool is that it should aid the student, while still maintaining that the students construct the proofs as if it was on paper.

## Documentation

We have developed an initial version of the OnlineProver system for simple Gentzen style derivations. In this pre-alpha version, an exercise is a list of
incomplete derivations, that the student must complete in an empty context. 
We implemented exercises for natural deduction in propositional logic in the style found in *The Logic Manual* by Volker Halbach.

The following notation is used for entering special symbols:

| **Logic** | **OnlineProver** |
|--------|--------------|
| ⊤ | top |
| ⊥ | bot |
| ¬ | not |
| ∧ | /\ |
| ∨ | \/ |
| ⇒ | => |

- For the application of the relevant rule, it is necessary to enter its name.
- To close a branch, it is necessary to enclose a formula in square brackets (e.g. [a /\ b]).

The following set of rules is implemented:

<img src="/images/nd_rules.png"/>
 <br>

## Experiments

### First experiment
The tool was tested in the course Logic for Informaticians at TUKE in April 2024. 
We gathered feedback on the tool through a questionnaire to evaluate its effectiveness, assessing its impact on teaching and learning approaches, along with technical aspects. The evaluation showed that the students were satisfied with using OnlineProver as part of the teaching and gave a first conformation of the learning approach behind. This gives us clear directions for future developments.

Results of the first experiments were processed into an extended abstract, and submitted to a conference, that currently (April 2024) is under review.