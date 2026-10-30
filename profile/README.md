# L'Alternative Fabrique

Much of the software a small European organisation depends on is hosted outside
Europe, priced per seat, and impossible to inspect.

We build our own applications on infrastructure hosted in the EU. The
repositories below are the technical foundations we maintain in the open.

## Open building blocks

| Repository | What it is |
| --- | --- |
| [sklp](https://github.com/lalternativefabrique/sklp) | Rootless development, CI and deployment supervisor for single-node and multi-node stacks (BSL 1.1) |
| [cortex](https://github.com/lalternativefabrique/cortex) | Go SDK for building and running agents with tools, memory and MCP (BSL 1.1) |
| [skt](https://github.com/lalternativefabrique/skt) | Toolchain manager for pinned runtimes and CLIs — no shims, no global state |
| [stack](https://github.com/lalternativefabrique/stack) | Scaffolder for a Go DDD backend and TanStack application, wired to the `sklp` workflow |
| [eventkit](https://github.com/lalternativefabrique/eventkit) | Go primitives for event-driven, event-sourced and CQRS applications |
| [searchkit](https://github.com/lalternativefabrique/searchkit) | Go libraries for finding, retrieving and admitting content |
| [editorkit](https://github.com/lalternativefabrique/editorkit) | Shared TipTap editor for React and React Native |
| [spore-sdk](https://github.com/lalternativefabrique/spore-sdk) | Node, Python, PHP, Ruby, Rust and Go SDKs for the [Spore](https://sporee.fr) transactional email API |
| [packages](https://github.com/lalternativefabrique/packages) | Shared Go and npm packages used across our applications |

## From foundations to products

[**Cortext**](https://cortext.lalter.fr/decouvrir) is the agent runtime behind
[**L'Alter**](https://lalter.fr). It declares agents, gives them tools and
credentials, and keeps their execution under the organisation's control.

Cortext already runs agents used by L'Alter, Synthiz, Partage and Skalpai.
The applications are where these open foundations meet real users, real data
and production constraints.

## What is not here

The applications themselves are private for now. What is published above is
what we are willing to document, support and maintain in the open.

[Discover L'Alternative](https://lalter.org) ·
[Explore the applications](https://lalter.org/outils)
