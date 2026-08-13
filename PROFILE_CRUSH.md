# SuperInstance

Written from the wheelhouse of F/V EILEEN, Southeast Alaska.
One program: conservation laws for agents, deterministic bytecode, and memory treated as an ecology.
The shell gets built before the crab — on purpose. Parked mechanisms carry their own wake conditions.

## Landscape

### Conservation
What you cannot destroy, you must account for. `γ + η = C` is the budget every agent reconciles against, every step.
- [conservation-enforcer](https://github.com/SuperInstance/conservation-enforcer) — FLUX bytecode layers enforce the budget on LLM output.
- [conservation-enforcer-rs](https://github.com/SuperInstance/conservation-enforcer-rs) — the same law, in Rust, because it has to live on the boat.
- [exocortex-rs](https://github.com/SuperInstance/exocortex-rs) — agent substrate that knows the law is there.

### Determinism
The only agent you can trust is one running on a machine a human can read. FLUX is that machine — bytecode, three cross-verified VMs, no hidden state.
- [flux-core](https://github.com/SuperInstance/flux-core) — zero-dependency register VM (`fluxvm` on crates.io).
- [flux-runtime](https://github.com/SuperInstance/flux-runtime) — assembler, compiler, VM in one.
- [flux-policy-tester](https://github.com/SuperInstance/flux-policy-tester) — fuzz the edges, enforce the bounds.

### Memory as ecology
Memory isn't a database; it's a tide flat. Things settle, things erode, things get handed off and found later by someone who wasn't looking.
- [exocortex](https://github.com/SuperInstance/exocortex) — persistent substrate; S3-compatible, tiered, runs on an ESP32.
- [hermes-memory-mcp](https://github.com/SuperInstance/hermes-memory-mcp) — memory as a surface agents share.
- [baton-protocol](https://github.com/SuperInstance/baton-protocol) — a one-file handoff: state, next, meta.
- [lineage-tracker](https://github.com/SuperInstance/lineage-tracker) — provenance as bloodline records.

### Rooms & working animals
PLATO is the room. The whistle is how you address the animal in it. We keep working animals, not tools — so they have a vet, a breed registry, and a shepherd.
- [plato-core](https://github.com/SuperInstance/plato-core) · [plato-core-rs](https://github.com/SuperInstance/plato-core-rs) — the room runtime, two languages.
- [whistle](https://github.com/SuperInstance/whistle) — intent DSL; replaces system-prompt sprawl with compiled commands.
- [a2ui](https://github.com/SuperInstance/a2ui) — the adaptive interface layer.
- [shepherds-console](https://github.com/SuperInstance/shepherds-console) · [vetcheck](https://github.com/SuperInstance/vetcheck) · [breed-registry](https://github.com/SuperInstance/breed-registry) — operate, diagnose, select.
- [swarm-anchor](https://github.com/SuperInstance/swarm-anchor) — the roster is whatever files exist.

### The boat
F/V EILEEN, Southeast Alaska. The sea does not care about your abstractions, which is exactly why it's useful.
- [boat-agent](https://github.com/SuperInstance/boat-agent) — Commander Data for the wheelhouse.
- [tzpro-agent](https://github.com/SuperInstance/tzpro-agent) — first sensor node; watches the sounder, learns the grounds.
- [perception-cascade](https://github.com/SuperInstance/perception-cascade) — racehorse / scribe / analyst loops on a frame stream.
- [provenance-log](https://github.com/SuperInstance/provenance-log) — append-only, hash-chained; the boat's black box, as a crate.
- [trawl](https://github.com/SuperInstance/trawl) — fishing on working-animal architecture.

## Planted shells

Honest disclosure, because the honesty is the personality: we build the shell first and wait for the crab. These exist, parse, and run their own self-checks — but they sleep until a condition is met. Each carries its wake word.

- [othismos](https://github.com/SuperInstance/othismos) — the force a bounded system exerts against its bounds. *Wakes when* a system needs to feel its own wall.
- [VaaS](https://github.com/SuperInstance/VaaS) — vessel-as-a-robot resonance substrate, seven pillars. *Wakes when* the boat speaks to itself as one animal.
- [SmartCRDT](https://github.com/SuperInstance/SmartCRDT) — self-improving AI on CRDTs. *Wakes when* two agents honestly edit the same thought.
- [spectro](https://github.com/SuperInstance/spectro) — multi-model cognitive spectrograph. *Wakes when* one model isn't enough spectrum.
- [tminus-os](https://github.com/SuperInstance/tminus-os) — swarm coordination OS. *Wakes when* the fleet needs a single `.swarm/`, not a meeting.

If a shell wakes and there's no crab, we say so and put it back. That's the whole discipline.

## Writings

We write the essay first. The tool is what's left after we've finished arguing with the essay.
- [AI-Writings](https://github.com/SuperInstance/AI-Writings) — essays and philosophy from the exocortex.
- [SuperInstance-papers](https://github.com/SuperInstance/SuperInstance-papers) — the longer arguments.

## If you're reading this

We're a commercial fishing operation that got curious about where memory lives, and a research program that runs on salt water. If you're building something honest — a budget you actually reconcile, a handoff you'd sign your name to, a shell you'd admit is empty — the water's cold but the berth is open.

*Draft: Crush*
