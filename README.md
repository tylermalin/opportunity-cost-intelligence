# Opportunity Cost Intelligence

AI should not silently consume human time.

Most AI tools are designed to answer the question in front of them. They help us draft the email, debug the app, compare the insurance plan, dispute the bill, write the contract, book the trip, fix the washing machine, or research the medical code.

That is useful.

But it misses the more important question:

**Should a person be spending their time on this at all?**

## The Problem

AI is not only replacing labor.

It is also transferring labor.

Travel agents disappeared. Now the traveler compares flights, hotels, refund policies, luggage rules, seat maps, and rental car add-ons.

Bank tellers disappeared. Now the customer manages the app, the login, the fraud alert, the password reset, the transfer limit, and the support bot.

Customer support disappeared. Now the user troubleshoots the system, searches the forum, restarts the device, uploads screenshots, and argues with the chatbot.

Accountants, lawyers, doctors, repair technicians, claims specialists, assistants, editors, and analysts are not disappearing all at once. But more of their preliminary work is being pushed onto ordinary people.

AI accelerates this shift.

It gives people more capability, but it also gives them more responsibility.

The result is a strange paradox:

**AI can make us more powerful while making us more overloaded.**

## Opportunity Cost Neglect

People notice the invoice they avoided.

They do not always notice the evening they lost.

A $500 accountant fee feels visible. Four fragmented hours of tax research, document sorting, prompt iteration, filing uncertainty, and post-submission anxiety often do not.

This is opportunity cost neglect: the tendency to undervalue what we give up when the cost is paid in time, attention, and cognitive effort instead of money.

AI makes this worse because the cost arrives in small increments:

- 10 minutes clarifying the prompt
- 20 minutes checking the answer
- 35 minutes comparing options
- 15 minutes correcting the output
- 45 minutes deciding whether to trust it
- another 30 minutes starting over

No single step feels expensive.

The total burden can be enormous.

## What This Project Is

Opportunity Cost Intelligence, or OCI, is an open skill layer for AI tools.

It teaches AI assistants, coding agents, chat interfaces, and workflow systems to notice hidden labor before it becomes invisible.

OCI is not a productivity framework.

It is not a hustle system.

It is not a time-tracking cult.

It is a lightweight behavioral protocol for helping humans decide:

- continue
- stop
- simplify
- delegate
- automate
- learn
- ignore
- ask a professional
- ship the imperfect version

The goal is not to maximize output.

The goal is to protect human attention and agency.

## Core Principle

Every AI interaction should be able to answer five questions:

1. **What is this likely to cost in time?**
2. **What is the user giving up by doing it personally?**
3. **Is the task strategic, educational, emotional, administrative, or repetitive?**
4. **Is the user learning something valuable, or absorbing someone else’s unpaid back-office work?**
5. **At what point should the system recommend stopping, delegating, or seeking a professional?**

## What Is Included

This repository starts with portable Skill Files that can be copied into existing tools:

```text
/skill-files
  chatgpt-custom-instructions.md
  claude-project.md
  cursor-rules.md
  agent-policy.yaml

/tools
  time-value-calculator.md

/templates
  oci-task-log.csv

/examples
  example-interventions.md
```

The files are intentionally simple. The point is forkability.

Use them in:

- ChatGPT custom instructions
- Claude Projects
- Cursor rules
- Windsurf rules
- agentic coding systems
- personal operating systems
- internal AI assistants
- workflow automations

## The OCI Loop

Use this loop inside any AI workflow:

```text
1. Clarify the task
2. Estimate time cost
3. Estimate value at stake
4. Identify hidden labor
5. Check risk and expertise boundaries
6. Recommend continue, stop, delegate, automate, or seek a professional
7. Log the decision
```

## Example Intervention

Instead of:

> Here is a 12-step guide to dispute this insurance bill.

OCI-aware AI should say:

> This may be worth doing yourself if the disputed amount is meaningful and the issue is procedural. Before continuing, estimate your time ceiling. If this takes more than 90 minutes or involves medical necessity, legal rights, or coverage interpretation, consider escalating to a billing advocate or qualified professional.

Instead of:

> Here are 20 more logo variations.

OCI-aware AI should say:

> You have already explored several adequate directions. The marginal business value of more iteration appears low. Consider choosing one, testing it with users, and moving on.

Instead of:

> Here are 10 travel booking options.

OCI-aware AI should say:

> This search has crossed into over-optimization. If the expected savings are less than your time value, choose the best acceptable option and stop.

## Personal Time Value

OCI does not require a perfect hourly rate.

Start with a rough value:

```text
Personal Time Value = annual income target / 1,500 focused hours
```

Or use a simple default:

```text
$25/hr = constrained budget
$50/hr = professional baseline
$100/hr = founder/operator baseline
$250/hr = executive/strategic time
```

This is not about ego.

It is about making invisible trade-offs visible.

## Risk Boundary

OCI should never encourage users to rely on AI as a replacement for qualified professionals in high-risk contexts.

Examples:

- medical diagnosis
- legal advice
- tax filing with complex facts
- electrical work
- structural repairs
- financial suitability decisions
- immigration issues
- insurance coverage disputes
- safety-critical code
- regulated business operations

In these cases, OCI should help the user prepare for a professional conversation, not pretend to be the professional.

## Initial Hypothesis

People do not need another productivity app.

They need AI systems that can say:

> This is not worth your time.

> You are absorbing hidden labor.

> You are over-optimizing.

> This should be delegated.

> This is worth learning because it compounds.

> Stop here. Ship it.

## How to Use This Repo

1. Copy a Skill File into your preferred AI tool.
2. Use it during normal work.
3. Log three decisions where OCI changed your behavior.
4. Open an issue with what worked, what failed, and what you want integrated next.
5. Fork the repo and adapt the skill to your own agents or workflows.

## Call for Contributors

This is an early open experiment.

Useful contributions include:

- better heuristics
- agent integrations
- Cursor/Windsurf rules
- browser extension prototypes
- time-value calculators
- local-first tracking tools
- research on opportunity cost neglect
- examples from law, medicine, finance, design, coding, home repair, and operations
- critique of where this framework overreaches

## Design Constraint

OCI itself should not become another burden.

If the system takes more time than it saves, it is failing.

## Short Version

AI should not just help us do more.

AI should help us decide what is worth doing.
