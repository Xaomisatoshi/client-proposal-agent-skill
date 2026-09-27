---
name: client-proposal-agent-skill
description: Create client-ready project proposals from discovery call notes, rough requirements, emails, or briefs. Use when the user needs a proposal, scope of work, deliverables, timeline, pricing structure, assumptions, missing-data notes, or a follow-up message for freelancers, consultants, coaches, creators, or small agencies.
---

# Client Proposal Agent Skill

## Purpose

Turn messy client input into a clear, professional, client-ready proposal.

This skill is designed for freelancers, consultants, coaches, creators, and small agencies who need to quickly transform discovery notes, chat messages, emails, or rough project ideas into structured project proposals.

The skill does not only write nice text. It helps the user clarify:

- client goal
- client problem
- desired outcome
- scope of work
- deliverables
- timeline
- assumptions
- missing information
- risks
- next steps
- follow-up message

## When to Use This Skill

Use this skill when the user asks for any of the following:

- create a client proposal
- write a project proposal
- turn discovery call notes into an offer
- structure a scope of work
- create a freelancer offer
- create a consulting proposal
- create a coaching package proposal
- prepare a client-ready sales document
- write a follow-up after a sales call
- organize client requirements
- create deliverables and next steps

## Core Rule

Always create a practical, client-ready proposal structure.

Do not invent facts, prices, guarantees, deadlines, legal claims, or client commitments.

If information is missing, mark it clearly.

Use:

```text
Missing data: ...
Assumption: ...
Not provided: ...
To confirm with client: ...
```

## Input Types

The user may provide:

- raw call notes
- short client messages
- emails
- bullet points
- vague project ideas
- website audit notes
- coaching inquiry notes
- service descriptions
- a rough offer idea
- only a target client and desired outcome

If the input is incomplete, proceed with a useful draft but mark assumptions clearly.

## Method

Follow this workflow:

1. Identify the client type.
2. Identify the client's current situation.
3. Identify the client's desired result.
4. Extract the main problem or pain point.
5. Translate the problem into project goals.
6. Define the proposed solution.
7. Create deliverables.
8. Define what is included and excluded.
9. Add timeline or phases if possible.
10. Add pricing structure only if enough data is provided.
11. Mark assumptions and missing information.
12. Add risks or open decisions.
13. Create client-ready next steps.
14. Write a short follow-up message.

## Required Output Structure

Unless the user asks for a different format, output the proposal in this structure:

```markdown
# Client Proposal

## 1. Proposal Summary

## 2. Client Situation

## 3. Goals and Desired Outcome

## 4. Proposed Solution

## 5. Scope of Work

## 6. Deliverables

## 7. Timeline / Project Phases

## 8. What Is Included

## 9. What Is Not Included

## 10. Pricing / Investment

## 11. Assumptions

## 12. Missing Information

## 13. Risks and Clarifications

## 14. Next Steps

## 15. Client Follow-up Message
```

## Pricing Rules

If the user gives exact pricing, include it.

If the user gives pricing ranges, present them clearly.

If no pricing is provided, do not invent a price.

Instead write:

```text
Pricing / Investment:
Not provided. Recommended next step: define either a fixed project fee, hourly rate, retainer, or three package options.
```

If helpful, suggest a pricing structure without numbers:

```text
Option 1: Basic package — core deliverables only
Option 2: Standard package — core deliverables plus revisions
Option 3: Premium package — full implementation support
```

## Tone

Use a tone that is:

- clear
- professional
- confident
- calm
- client-friendly
- not pushy
- easy to copy into an email, PDF, or proposal document

Avoid sounding too generic or overly dramatic.

## Quality Rules

Before finalizing, check:

- Is the proposal understandable to a non-technical client?
- Are all deliverables concrete?
- Are assumptions marked?
- Are missing details visible?
- Are there no invented prices?
- Are there no unrealistic guarantees?
- Is the next step clear?
- Does the follow-up message sound natural?

## Safety and Reliability Rules

Do not provide legal, tax, medical, or financial guarantees.

Do not promise outcomes such as:

- guaranteed revenue
- guaranteed rankings
- guaranteed conversion rates
- guaranteed legal result
- guaranteed business success

Use careful language:

```text
The goal is to...
This proposal is designed to...
Expected outcome, if the required inputs and cooperation are provided...
```

## Example Input

```text
Client owns a small coaching business. She wants better follow-up after sessions and a clearer client journey. Notes are messy. She wants an AI workflow that turns session notes into summaries, questions, homework, and follow-up emails. Budget unknown. Timeline maybe 2 weeks.
```

## Example Output Style

```markdown
# Client Proposal

## 1. Proposal Summary

This proposal outlines a practical AI-supported follow-up workflow for a coaching business. The goal is to turn raw session notes into structured summaries, reflection questions, homework suggestions, and professional client follow-up messages.

## 2. Client Situation

The client currently has coaching session notes but no consistent post-session workflow. This can make follow-up slower, less structured, and harder to repeat.

## 3. Goals and Desired Outcome

- Save time after coaching sessions
- Create consistent client follow-up
- Improve clarity for clients
- Build a reusable session documentation workflow

## 4. Proposed Solution

Create a reusable AI workflow that transforms raw coaching notes into a polished post-session package.

## 5. Scope of Work

Included:
- session note intake structure
- summary output format
- reflection question format
- homework/action-step format
- follow-up email template
- quality checklist

## 6. Deliverables

- Coaching follow-up prompt
- Example input and output
- Client email template
- Session summary structure
- Quality checklist

## 7. Timeline / Project Phases

Assumption: Timeline is approximately 2 weeks.

Phase 1: Clarify workflow requirements  
Phase 2: Build and test prompt structure  
Phase 3: Finalize templates and handover  

## 8. What Is Included

- One reusable workflow
- One example run
- One follow-up email structure
- Basic usage guidance

## 9. What Is Not Included

- Full CRM integration
- Automation setup
- Legal or therapeutic documentation review
- Custom software development

## 10. Pricing / Investment

Not provided. Recommended next step: define a fixed project fee or package-based pricing.

## 11. Assumptions

- The client wants a repeatable AI workflow, not custom software.
- Session notes will be provided by the coach.
- The workflow should be easy to reuse without technical setup.

## 12. Missing Information

- Exact budget
- Number of templates needed
- Preferred tone of voice
- Whether the workflow must support multiple coaching formats
- Whether automation is required

## 13. Risks and Clarifications

The workflow quality depends on the quality of session notes. Sensitive client information should be handled carefully and according to the coach's privacy obligations.

## 14. Next Steps

Confirm scope, preferred tone, example session notes, and budget range.

## 15. Client Follow-up Message

Hi [Client Name],

thank you for sharing your goals. Based on what you described, I suggest creating a reusable AI-supported follow-up workflow that turns your coaching session notes into structured summaries, reflection questions, homework suggestions, and client-ready follow-up emails.

The next step would be to confirm your preferred tone, one example of your session notes, and whether you want this as a simple prompt workflow or a more complete template system.

Best,  
[Your Name]
```

## Compact Mode

If the user asks for a shorter answer, provide:

```markdown
## Proposal Summary
## Scope
## Deliverables
## Missing Information
## Next Steps
## Follow-up Message
```

## Final Instruction

Always make the proposal usable immediately.

The result should be something the user can copy, edit, send, or turn into a PDF without needing to rebuild the structure from scratch.
