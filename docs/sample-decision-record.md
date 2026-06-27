# Synthetic Decision Record

Synthetic Example — For Portfolio Demonstration Only. This does not describe a real private decision or project record.

## Decision ID

DR-SYN-001

## Date

2026-06-28

## Project Area

Public-safe portfolio documentation

## Decision Question

How should a public portfolio repository demonstrate the Super Brain 2.0 workflow without exposing private notes or project records?

## Context

The portfolio repository needs to show how the knowledge system works in practice. The existing documentation explains the architecture and governance model, but admissions reviewers may benefit from seeing a concrete artifact format.

The example must remain fictional and must not include private second-brain contents, personal records, sensitive project details, financial information, trading-related materials, client information, API keys, tokens, or private prompts.

## Options Considered

| Option | Description | Tradeoff |
| --- | --- | --- |
| Architecture only | Keep the repository focused on diagrams and explanatory documents. | Safe, but too abstract for review. |
| Redacted real record | Use a real private decision with sensitive parts removed. | More realistic, but creates privacy and context risks. |
| Synthetic record | Create a fictional decision record using the same structure expected in the system. | Public-safe while still showing workflow behavior. |

## Selected Decision

Create a synthetic decision record that demonstrates the decision structure, review logic, and write-back discipline without describing a real private decision.

## Rationale

The synthetic record gives reviewers a concrete view of how Super Brain 2.0 captures decision context, compares options, records rationale, and defines follow-up actions. It supports credibility without exposing private data.

## Risks

- The example may still feel simplified compared with real project work.
- Reviewers may misread the synthetic example as a production record if the disclaimer is not clear.
- Too many examples could make the repository feel inflated rather than focused.

## Follow-up Actions

- Add a clear synthetic-example disclaimer at the top of the document.
- Link the decision record from the repository structure in `README.md`.
- Keep the example focused on public-safe portfolio documentation.
- Avoid any real project names, private notes, or operational details.

## Review Date

2026-07-15

## Write-back Notes

The decision format should be reused as a future template for public-safe examples. If a cockpit interface is later created, this record can become sample data for a demo view.
