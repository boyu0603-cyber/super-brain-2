# Knowledge Governance

## Public vs Private Knowledge

Super Brain 2.0 uses a strict boundary between public-safe portfolio material and private working knowledge.

Public-safe knowledge may include:

- High-level system descriptions
- Synthetic examples
- Architecture diagrams
- Workflow explanations
- Governance principles
- Portfolio-safe screenshots or mockups

Private knowledge must not be included:

- Personal notes or journals
- Private conversations
- Client/customer information
- API keys, tokens, credentials, or `.env` files
- Internal business materials
- Financial records
- Trading account information
- Sensitive commercial project details
- Full local second brain contents

## Source Traceability

Knowledge entries should preserve where important information came from. A structured entry may include source type, date, context, related project, and review status.

Traceability helps prevent unverified information from becoming hidden assumptions.

## Decision Versioning

Important decisions should be versioned. A decision record should show:

- Original decision
- Date
- Rationale
- Alternatives considered
- Later updates
- Current status
- Review owner

This makes the system useful for learning, accountability, and future review.

## Sensitive Data Exclusion

Sensitive information is excluded from the public repository by default.

Before any material becomes public, it should be checked for:

- Names or identifiers that should remain private
- Client or customer references
- Financial or account data
- Credentials or system secrets
- Commercially sensitive strategy
- Private AI conversations

## Write-Back Discipline

Write-back is the process of updating the knowledge base after action.

Good write-back records:

- What was done
- What changed
- What was learned
- What decision was made
- What should be reused
- What should be reviewed later

Without write-back discipline, the system becomes a storage archive instead of decision infrastructure.

## Review Cadence

A regular review cadence keeps the system current.

Suggested review loops:

- Daily capture cleanup
- Weekly project review
- Monthly methodology review
- Quarterly public/private boundary review

## What Is Intentionally Excluded

This repository intentionally excludes private system contents, production credentials, commercial materials, sensitive financial or trading records, and raw private conversations.

The purpose of this repository is to communicate the design and governance logic safely.
