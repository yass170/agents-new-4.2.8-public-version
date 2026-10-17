# Agents 4.2.8 — Structured AI-Assisted Project Work

A file-based framework for organizing AI-assisted software work through governance, workflows, domain skills, reusable templates and engineering artifacts.

The framework gives a project a consistent way to connect requirements, design decisions, implementation checks and delivery. It separates shared rules from task-specific guidance and provides a structure for understanding what is being done, which constraints apply and what has been verified.

## Users

| Role | Use |
|---|---|
| Project owner | Set the scope, review decisions and retain control of consequential actions. |
| Developer or AI coding assistant | Find relevant project guidance, organize work and check the result. |
| Framework maintainer | Evolve shared rules, skills, templates and validation tools. |

## Main features

- **Governance structure.** Separate permissions and shared constraints from project-specific activity.
- **Task workflows.** Organize substantial work into preparation, implementation, checking and delivery.
- **Domain skills.** Group reusable guidance by technical responsibility and load relevant guidance when needed.
- **Engineering artifacts.** Connect user outcomes, design choices and verification through issues and decisions.
- **Reusable templates.** Provide consistent starting structures for project and engineering documents.
- **Mechanical validation.** Check the coherence of structured project documents and framework conventions.

## Typical workflow

1. Identify the project context and the requested outcome.
2. Use the relevant guidance to frame the design and work scope.
3. Implement and check the scoped changes.
4. Review the result and handle delivery as a separate concern.

## Project structure

```text
agents-new-4.2.8-public-version/
├── docs/
│   └── design/
│       ├── decisions.md
│       ├── requirements.md
│       └── verification.md
├── new-4.2.8/
│   └── framework/
│       ├── examples/
│       │   └── engineering-artifacts/
│       │       ├── decisions/
│       │       ├── issues/
│       │       │   ├── epics/
│       │       │   ├── features/
│       │       │   ├── tasks/
│       │       │   └── README.md
│       │       └── README.md
│       ├── governance/
│       │   ├── governance.md
│       │   └── README.md
│       ├── references/
│       ├── scripts/
│       │   └── tests/
│       ├── skills/
│       │   ├── backend-csharp/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── backend-python/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── code-design-principles/
│       │   │   └── SKILL.md
│       │   ├── database/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── database-android/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── deployment/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── deployment-android/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── docker-postgres-pgadmin/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── frontend-android/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── frontend-csharp/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── frontend-python/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── frontend-react/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── git/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── git-forgejo/
│       │   │   └── SKILL.md
│       │   ├── nginx/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── project-tracker-sync/
│       │   │   ├── references/
│       │   │   ├── scripts/
│       │   │   ├── package.json
│       │   │   └── SKILL.md
│       │   ├── stack-fields-guide/
│       │   │   ├── references/
│       │   │   └── SKILL.md
│       │   ├── ux-writing-fr/
│       │   │   └── SKILL.md
│       │   └── …
│       ├── templates/
│       └── workflow/
│           ├── MAIN-WORKFLOW/
│           │   ├── SUB-WORKFLOW/
│           │   │   ├── deployment/
│           │   │   │   └── WORKFLOW.md
│           │   │   └── engineering-artifacts/
│           │   │       └── WORKFLOW.md
│           │   └── WORKFLOW.md
│           └── README.md
├── ARCHITECTURE.md
└── README.md
```

[Complete directory structure](docs/design/structure.md)

| Area | Responsibility |
|---|---|
| Governance | Shared boundaries and permissions for project activity. |
| Workflow | Coordination of preparation, implementation, review and delivery. |
| Skills | Domain-focused guidance for backend, frontend, data, deployment and related work. |
| Templates | Reusable structures for decisions, issues and project records. |
| Examples | Illustrations of engineering artifacts and their relationships. |
| Scripts | Validation and integration tooling around the file-based framework. |

## Technology

Markdown, structured JSON documents, Python validation scripts and JavaScript integration tooling.

## Engineering

- [Architecture](ARCHITECTURE.md)
- [Product requirements](docs/design/requirements.md)
- [Design decisions](docs/design/decisions.md)
- [Verification strategy](docs/design/verification.md)

## Engineering examples

- [Workspace epic](new-4.2.8/framework/examples/engineering-artifacts/issues/epics/operator-workspace.md)
- [Overview task](new-4.2.8/framework/examples/engineering-artifacts/issues/tasks/workspace-overview.md)
- [Access decision](new-4.2.8/framework/examples/engineering-artifacts/decisions/authenticated-workspace.md)

The framework organizes work; it does not replace engineering judgment, user decisions or evidence from the target environment.

---

Source code, operational configuration and project-specific data are withheld for confidentiality.
