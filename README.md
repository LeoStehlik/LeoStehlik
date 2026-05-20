# Leo Stehlik

Building WrenLore and the operating tools around it.

I work on the unglamorous parts of AI agents: clearer briefs, proof-backed completion, source-backed memory, eval loops, and guardrails that stop generated work from looking more finished than it is.

## Current Focus

[WrenLore](https://github.com/wrenlore/wrenlore) is the flagship product: a source-backed knowledge and memory layer for teams that want AI working from real company context, not chat history and hope.

## Agent Operating Tools

| Repo | What it is for |
| --- | --- |
| [Proof Loop](https://github.com/LeoStehlik/proof-loop) | Evidence before `done` for AI coding tasks |
| [Sovereign Brain](https://github.com/LeoStehlik/decoupled-agent-memory) | Source-backed memory with freshness review |
| [WrenLore](https://github.com/wrenlore/wrenlore) | Product-grade company knowledge and agent memory |
| [Loopsmith](https://github.com/LeoStehlik/loopsmith) | Turning repeated agent failures into evals |
| [Brief Master](https://github.com/LeoStehlik/brief-master) | Turning fuzzy requests into precise agent briefs |
| [no-slop-ui](https://github.com/LeoStehlik/no-slop-ui) | Frontend guardrails against generic AI UI output |

The workflow is simple: write a better brief, freeze the acceptance criteria, verify the work with evidence, turn repeated failures into evals, and keep durable decisions attached to sources.

Most of this came from running agents on real work and getting tired of confident final messages that were only half true.
