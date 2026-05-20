# Leo Stehlik

I build tools and products around the awkward parts of working with AI agents: vague briefs, fake "done" claims, stale memory, repeated behaviour failures, and the strange tendency of coding agents to produce shiny nonsense unless you box them in properly.

The flagship product direction is [WrenLore](https://github.com/wrenlore/wrenlore): a knowledge and memory layer for teams that want AI to work against source-backed company context rather than a pile of chat history and hope.

Around that, I keep a set of small operating tools for AI agent workflows: clearer briefs, evidence-backed completion, evals for repeated failures, source-backed memory, and frontend guardrails.

## Agent Operating Tools

| Repo | Use it when |
| --- | --- |
| [Proof Loop](https://github.com/LeoStehlik/proof-loop) | a coding task needs evidence before anyone calls it done |
| [Sovereign Brain](https://github.com/LeoStehlik/decoupled-agent-memory) | long-running agents need source-backed memory and freshness review |
| [WrenLore](https://github.com/wrenlore/wrenlore) | teams need the product-grade version of source-backed knowledge and agent memory |
| [Loopsmith](https://github.com/LeoStehlik/loopsmith) | the same agent failure keeps recurring and should become an eval |
| [Brief Master](https://github.com/LeoStehlik/brief-master) | the task is still fuzzy and needs to become a precise agent brief |
| [no-slop-ui](https://github.com/LeoStehlik/no-slop-ui) | frontend agents need guardrails against generic AI UI sludge |

The rough workflow is simple: write a better brief, freeze the acceptance criteria, verify the work with evidence, turn repeated failures into evals, and keep the durable decisions attached to sources.

Most of this came from running agents on real work and getting tired of confident final messages that were only half true.

