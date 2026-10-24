# Multi-Agent Computer Platform Engineering Services Section

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

**A composition map for agent-inhabited computer platforms.** The 561
Group uses this engineering section to organize persistent operating
environments that coordinate multiple agents. It records platform
responsibilities and version-pinned component ownership.

**This public repository is not a downloadable, runnable multi-agent
platform.** Its current implementations are chiefly Git submodules to
private repositories. A public GitHub visitor can inspect the source
and design material tracked *here*, but not those private components.

## What a visitor can inspect

- [Platform requirements](content/requirements) and
  [text material](content/text) recorded directly in this repository.
- [Agentic enterprise platform specialization](services/agentic-enterprise-computer-platform-engineering-services-section/README.md),
  which identifies the enterprise hosting branch.
- The separately owned [Muse website source](https://github.com/red-cup-engineering/muse-site),
  currently public. A website repository is not the agent platform itself.
- The upstream [multi-agent computer-system engineering section](https://github.com/red-cup-engineering/multi-agent-computer-system-engineering-services-section),
  which handles agent-composition concerns rather than their hosting environment.

The root `package.json` is an organizational manifest without a CLI or
application export. No installation command is advertised at this root.

## Composed component inventory

These are the eight Git submodules declared at this repository's HEAD.
**Private** means its implementation cannot be inspected by an ordinary
outside GitHub visitor, even though this parent repository is public.

| Tracked path | Role in the composition | Source visibility |
| --- | --- | --- |
| `apps/agentic-orchestration-platform` | Agent orchestration platform | Private |
| `apps/feltos` | FeltOS: agent-inhabited world/kernel lineage | Private |
| `services/agentic-enterprise-computer-platform-engineering-services-section/apps/metroplat` | MetroPlat enterprise environment | Private |
| `services/agentic-enterprise-computer-platform-engineering-services-section/apps/metroplat-holofoam` | MetroPlat Holofoam component | Private |
| `services/agentic-enterprise-computer-platform-engineering-services-section/apps/metroplat-operations-console` | MetroPlat operations interface | Private |
| `services/agentic-enterprise-computer-platform-engineering-services-section/apps/muse-assist` | Muse Assist component | Private |
| `services/lakotaean-computer-application-engineering-services-section/apps/lakotaean-organization-application` | Lakotaean application component | Private |
| `services/agentic-enterprise-computer-platform-engineering-services-section/sites/muse.561.group` | [Muse site source](https://github.com/red-cup-engineering/muse-site) | Public |

The private-status labels reflect the current GitHub source visibility,
not a confidentiality permission or a substitute for the child repository's
own documentation. Submodule pointers prove which source versions a
composition names, **not** that those implementations are deployed,
available as public APIs, standards-certified, or usable without other
infrastructure.

## Scope and status

This section concerns the **platform** that hosts and operates multiple
agent systems. The faculty-level behavior of agents belongs to the
[Agent Organization Engine](https://github.com/red-cup-engineering/agent-organization-engine);
single-agent harnesses, source kernels, and operational deployment belong
to their separate owners.

If you have authorized access to a child repository, use *its* exact
package exports, tests, runbooks, and deployment conditions. For outside
visitors, the public requirements and source register here are the
available starting point. Public documentation must not be mistaken for
a public hosted service.
