# Hello World Agent Router

Status: active mandatory repository router

Mandatory-context budget: 40 lines

- This is an intentionally empty seed repository; it is not shared engine or platform authority.
- Before adding implementation, define its product-local role, add a README, and reconcile reusable behavior with `linnaeus/linnaeus-engine`.
- Do not copy app-local contracts or runtime implementations into this seed.
- Build and test are explicitly not applicable until an implementation scaffold is accepted.
- Use `pwsh ../../scripts/run.ps1 -Repo apps/hello-world -Task doctor|build|test|verify|docs` for standardized task status.
- Follow the Workbench documentation/commenting contract when the repository gains code.


## Workspace Agent Standard

- Before broad exploration, generate bounded context from the Workbench root with `pwsh -NoProfile -File scripts/get-agent-context.ps1 -Repo <repo> [-Capability <handle>]`.
- Workbench `manifests/agent-contracts.json` and `manifests/agent-capabilities.json` determine applicable authority; read only the contracts selected by that packet.
- Follow Workbench `docs/contracts/agent-oriented-documentation-and-commenting-contract-v1.md`: document semantic boundaries and invariants, never target comment density or narrate syntax.
- Use `pwsh -NoProfile -File scripts/run.ps1 -Repo <repo> -Task doctor|build|test|verify|docs`; `not_applicable` requires the registered concrete reason.
- Keep navigation-critical documents current in `manifests/agent-documents.json`. Oversized or mixed-responsibility source units require decomposition or an explicit reviewed disposition.
- Measure success through routing, authority, implementation/test discovery, task availability, and verification completion—not prose volume.
