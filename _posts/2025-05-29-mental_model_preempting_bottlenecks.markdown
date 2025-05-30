---
layout: post
title: "Mental Model: Pre-empting Bottlenecks in High-Talent AI-Leveraged Organizations"
categories: mental_models
tags: mental_models, ai, organizations, management, productivity
---

Last Updated: May 29, 2025

_Disclaimer - I reserve the right to change my mind every time I encounter a new idea. I'm getting this out of my head for my own sake and will improve these posts as I have the time. Engage at your own risk._

<br/>

---

<br/>

## Summary

AI tools are accelerating software development at an unprecedented pace. This emerging paradigm will continue to gain speed, rewarding agile organizations that anticipate and adapt to new bottlenecks as coding becomes faster and cheaper.

This post attempts to identify how organizations should re-tool and re-staff to best capture the increasing force-multiplier of AI tooling.

The bulk of this discussion will related to changes in software development, with non-software tooling and its ramifications discussed at the end.

<br/>

---

<br/>

## Main Content

### Context

This is being written in May of 2025. Claude 4 recently came out, and the time-horizon for when AI tools can fully replace junior and mid-level developers is measured in months, not years. The capabilities that will replace senior developers seem slightly farther in the horizon. The guidelines here are for the second half of 2025 and the start of 2026 and should be re-evaluated frequently as the field changes.

### How Engineering Organizations Should Change

#### The World We're Trending Towards

- The cost of writing code is trending towards zero
- The cost of writing tests is trending towards zero
- The cost of onboarding to a codebase is trending towards zero
  - AI tools can immediately provide context about any question you have

#### Addenda

- The cost of writing code is trending towards zero
  - **IF** senior developers are able to provide context to tools in O(1) or O(log n) time per command
- The cost of writing tests is trending towards zero
  - **IF** code is sufficiently atomic to be testable
- The cost of onboarding to a codebase is trending towards zero
  - **IF** code is sufficiently organized that reasoning about any given chunk of it is easy

#### The implications of this world

- There is increasing leverage in atomic, easy-to-test, and easy-to-read code
  - Atomic code is easy for developers unfamiliar with a codebase to quickly reason about, increasing the organizational scale at which individual developers can operate
- **Untested, hard-to-understand code isn't worth writing more of**
  - So this code almost entirely loses the early leverage provided by new tooling
  - This becomes less true as tooling gets good enough to effectively refactor codebases, but there will still be a multi-month advantage to organizations that are quick to refactor
- Having a static ruleset to convey architectural norms is (in the near term) critical for capturing force-multiplying effects of AI tooling
- There is increasing leverage in having an organization where developers contribute across multiple codebases
  - Developers will need less and less expertise to quickly contribute across multiple codebases and parts of the stack
  - Domain experts will continue to be valuable for vetting architectural decisions, but heavily-siloed organizations will be bottlenecked by those silos
  - Rhe value-add of a mid-level developer who only writes code in one repo will continue to decrease

### How Design, Product, User Testing, and Management Should Change

#### The World We're Trending Towards

- The time from creating a design to having the new feature ready for users to test is decreasing and will continue to decrease
- Robust design systems will further increase how quickly new features can be coded
- Creating great design will be slower than shipping great code
- Testing features with users will be slower than shipping great code
- Constantly re-aligning organizations to complex and shifting product goals will be harder and slower than shipping great code

#### Addenda

- The above is hardly true now, but will become more and more so over the next 18 months
- The above also assumes that an organization is adapting to capture the value of new software development tools as described in the previous section

#### The implications of this world

- The absolute value of great designers will increase in the next 18 months
- The absolute value of great product managers will increase in the next 18 months
- The absolute value of great UX Researchers will increase in the next 18 months
- The absolute value of flexible Management (and organizations) will increase in the next 18 months
- The marginal value of developers in organizations constrained in the above areas will decrease in the next 18 months

<br/>

---

<br/>

## Areas for further exploration

- Impact of remote work on bottleneck formation
- Role of AI in organizational bottleneck prediction
- Cultural factors in bottleneck prevention
- Scaling strategies for high-growth organizations
- Integration of human and AI decision-making

<br/>

---

<br/>

## Updates

[Add a `###` section each time I encounter information that causes me to update my mental model. Explain what changed and reference the source]

<br/>

---

<br/>

## Sources

- Daily interfacing with AI tooling
- Personal experience in AI-enhanced organizations
- Management literature on organizational design
- Keeping up with AI tooling developments
