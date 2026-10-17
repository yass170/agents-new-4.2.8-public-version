# Verification Strategy

## Critical behaviors

- Shared conventions remain consistent across templates and examples.
- A selected domain skill corresponds to the task’s technical responsibility.
- A design decision can be related to a user outcome and a verification objective.
- Delivery checks remain distinct from implementation checks.

## Test layers

| Layer | Focus |
|---|---|
| Unit | Domain rules, validation and state changes without live external dependencies. |
| Integration | Consistency across application services and their storage or external-service adapters. |
| User journey | A complete path from a user action to its visible outcome, including failure states. |

## Environment checks

The framework organizes work; it does not replace engineering judgment, user decisions or evidence from the target environment.
