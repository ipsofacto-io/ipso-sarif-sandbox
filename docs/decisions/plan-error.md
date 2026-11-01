---
edr: 1
id: 01KA0000000000000000000005
slug: broken-check
title: "This check cannot evaluate"
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
  - engine: opa
    target: terraform-plan
    ref: rules/broken.rego
waivers: []
sources:
  - type: pr
    url: https://github.com/ipsofacto-io/ipso/pull/1
tags: [fixture]
---

# This check cannot evaluate

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
