# Authenticated Workspace

## Context

An operator workspace contains records that must be visible only to authorized users.

## Decision

Access is checked by the application service before protected information is returned. Interface visibility follows the same user context.

## Consequences

The interface remains responsive to access changes. A hidden button alone does not establish authorization. Authorization behavior needs verification independently of the visual layout.
