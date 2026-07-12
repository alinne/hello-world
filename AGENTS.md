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

- Context/applicability: use `scripts/get-agent-context.ps1`; `manifests/agent-contracts.json` selects exact capability contracts and sections.
- Documentation/code: follow `docs/contracts/agent-oriented-documentation-and-commenting-contract-v1.md`; explain invariants, never target comment density, and decompose oversized sources or record a reviewed disposition.
- Tasks/freshness: use `scripts/run.ps1` with `doctor|build|test|verify|docs`; keep `manifests/agent-documents.json` current.
- Success is correct routing, authority, code/test discovery, and verification—not prose volume.
