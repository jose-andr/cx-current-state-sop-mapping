# Shared Data and Knowledge Dependencies

## Purpose

This file captures dependencies between customer data quality and service knowledge quality across the current-state functions:

- Customer Data and Systems Support
- Customer Focus Information Support

The purpose is to show how reliable customer service depends on both accurate customer records and accurate service information.

This file should support later synthesis, future operating model design and business case development.

## Current status

Status: Draft discovery placeholder.

Dependencies should be validated after both functions have completed current-state SOP walkthroughs.

## Dependency inventory

| Dependency ID | Dependency | Customer Data and Systems Support relevance | Customer Focus Information Support relevance | Service impact | Status |
|---|---|---|---|---|---|
| DK-001 | Staff need reliable customer records and reliable service guidance. | Ensures customer identity and record history are trustworthy. | Ensures staff know what advice, process or next step applies. | Staff confidence and first contact resolution depend on both. | To validate |
| DK-002 | CRM quality affects how staff use service knowledge. | Duplicate or incorrect records may confuse customer context. | Staff may need guidance on how to interpret or act in CRM. | Poor data can reduce usefulness of guidance. | To validate |
| DK-003 | Service knowledge may influence data entry quality. | Staff need clear guidance to enter, update or select customer information correctly. | Service information may describe what data is needed for a service task. | Weak guidance can create upstream data quality issues. | To validate |
| DK-004 | Data quality issues can reveal knowledge gaps. | Repeated corrections may show users do not understand correct data entry or record selection. | Knowledge content may need improvement to prevent repeat errors. | Feedback loops can reduce repeated defects. | To validate |
| DK-005 | Knowledge gaps can reveal data quality risks. | Staff uncertainty may lead to inconsistent record handling. | Unclear guidance may affect how customer information is collected or used. | Inconsistent handling can affect records and customer experience. | To validate |
| DK-006 | Source-of-truth rules are needed for both data and knowledge. | Customer records need authoritative sources and correction rules. | Service information needs authoritative owners and publishing rules. | Future channels need trusted information foundations. | To validate |
| DK-007 | Manual workarounds connect systems today. | Officers may manually inspect, reconcile or correct records. | Officers may manually check, update or align service information. | Hidden coordination effort supports service reliability. | To validate |
| DK-008 | Future automation depends on trustworthy inputs. | Automation needs reliable customer data and duplicate controls. | Automation needs accurate, structured, approved knowledge. | Poor inputs reduce safety, consistency and trust. | To validate |
| DK-009 | Review and lifecycle controls are needed. | Customer data quality requires monitoring and correction over time. | Service knowledge requires review, expiry and retirement over time. | Quality degrades without ownership and review. | To validate |
| DK-010 | Staff escalation pathways need clear classification. | Data quality issues require different owners from system or access issues. | Knowledge, content and CRM user support issues require different owners. | Clear routing reduces delay and misdirected work. | To validate |

## Dependency themes

## 1. Customer context plus service guidance

Customer-facing staff need two kinds of confidence:

- confidence that the customer record is correct
- confidence that the service guidance is correct

If either is weak, the service response may be delayed, inconsistent or escalated.

Future implication:

The future operating model should treat customer data and service knowledge as linked foundations of service reliability.

## 2. Data quality and knowledge quality can create each other’s problems

Poor guidance can lead to poor data entry.

Poor data quality can make service guidance harder to apply.

Examples to validate:

- unclear guidance leads staff to create duplicate records
- unclear service steps lead staff to enter incomplete information
- duplicate records make it harder to understand customer history
- incorrect data causes staff to question the right process
- repeated data corrections reveal missing staff guidance
- repeated staff questions reveal unclear system behaviour

Future implication:

Future governance should include feedback loops between data quality work and knowledge improvement work.

## 3. Human judgement is currently a dependency

Both functions rely on people interpreting context, recognising patterns and knowing who to ask.

This is not a weakness by itself.

It becomes a risk when judgement is undocumented, unshared or unsupported by clear rules.

Future implication:

Current-state mapping should distinguish:

- judgement that should remain human
- judgement that can be supported by rules
- checks that could be automated
- escalations that need clearer thresholds
- knowledge that should be documented for continuity

## 4. Trusted information is a prerequisite for omnichannel

Omnichannel does not only require more channels.

It requires reliable information that can be reused safely.

Future channels may depend on:

- clean customer records
- authoritative service knowledge
- clear source-of-truth rules
- approval and review states
- lifecycle and expiry rules
- structured content that can be reused
- escalation thresholds for ambiguous cases

Future implication:

The business case should show that data and knowledge maturity are prerequisites for effective omnichannel service.

## 5. Current work contains prevention signals

The current work does not only fix issues.

It reveals why issues are happening.

Examples to validate:

- duplicate records may reveal poor search behaviour, unclear user guidance or weak system controls
- content gaps may reveal unclear service ownership or unsupported staff tasks
- repeated CRM support requests may reveal training, content, system design or data quality issues
- urgent update issues may reveal weak lifecycle and approval pathways

Future implication:

Future CX capability should include mechanisms to convert operational signals into prevention work.

## Dependency mapping template

Use this template to expand each validated dependency.

## Dependency: [dependency name]

| Attribute | Details |
|---|---|
| Dependency ID |  |
| Description |  |
| Related functions |  |
| Related SOPs |  |
| Related systems |  |
| What depends on what |  |
| Evidence observed |  |
| Current workaround |  |
| Risk if dependency fails |  |
| Customer impact |  |
| Staff impact |  |
| Future-state requirement |  |
| Business case signal |  |
| Status | Open / validated / rejected / superseded |

## Dependency questions

Use these prompts during synthesis.

- Where does poor data quality make service information harder to use?
- Where does poor service information create data quality problems?
- Where do staff need both customer context and service guidance?
- Where do duplicate records affect first contact resolution?
- Where do content gaps cause staff to use CRM incorrectly?
- Where do CRM questions reveal unclear service knowledge?
- Where do manual corrections reveal upstream prevention opportunities?
- Where do manual content updates reveal source-of-truth problems?
- Where do both functions rely on the same person, tool or undocumented knowledge?
- Where would future automation fail without better data or knowledge governance?
- Where would a single source of truth reduce both data and content rework?

## Future operating model signals

| Signal | Why it matters |
|---|---|
| Data quality and knowledge quality reinforce each other. | Future governance should connect rather than isolate these foundations. |
| Staff confidence depends on both records and guidance. | Improvements should be assessed by their effect on staff decision-making and customer outcomes. |
| Repeated defects are learning signals. | Future model should capture patterns and convert them into prevention work. |
| Manual judgement is currently essential. | Future design should support judgement rather than pretend it can be fully automated. |
| Omnichannel depends on trusted inputs. | Customer data and service knowledge are prerequisites for channel consistency. |
| Source-of-truth rules are needed across both domains. | Future architecture should distinguish authoritative systems, reference tools and publishing locations. |

## Review notes

| Date | Update | Updated by |
|---|---|
| YYYY-MM-DD | Initial draft placeholder created. |  |
