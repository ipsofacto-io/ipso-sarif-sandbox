---
edr: 1
id: 01KA0000000000000000000004
slug: no-eval-waived
title: "Code must not call eval, waived"
status: accepted
owner: team:core
scope:
  - org: ipsofacto-io
valid_from: 2026-01-01
valid_to: null
review_by: 2027-06-01
supersedes: []
criticality: blocking
checks:
  - engine: semgrep
    ref: rules/no-eval.yaml
    mode: block
waivers:
  - reason: sandbox waiver reason
    approver: Sandbox Approver
    valid_from: 2026-01-01
    valid_to: 2027-06-01
sources:
  - type: pr
    url: https://github.com/ipsofacto-io/ipso/pull/1
tags: [fixture]
---

# Code must not call eval, waived

## Context

Test fixture.

## Decision

Test fixture for the SARIF proof.

## Alternatives considered

None.

## Consequences

None.

## Verification

The SARIF proof.
