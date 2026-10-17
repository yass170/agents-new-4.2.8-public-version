# Design Decisions

## 1. Keep guidance in inspectable files

**Benefit.** Developers can review and version the framework beside their projects.

**Trade-off.** Consistency between documents requires validation and maintenance.

## 2. Separate general rules from domain guidance

**Benefit.** A task can use the relevant technical material without loading every instruction.

**Trade-off.** Domain boundaries and discovery need to stay understandable.

## 3. Separate implementation from delivery

**Benefit.** A tested change can be reviewed before it affects a running environment.

**Trade-off.** Delivery needs its own scope and verification rather than inheriting success from implementation.
