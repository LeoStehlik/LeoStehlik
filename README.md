# Leo Stehlik

I build tools and products around the awkward parts of working with AI agents: vague briefs, fake "done" claims, stale memory, repeated behaviour failures, and the strange tendency of coding agents to produce shiny nonsense unless you box them in properly.

The flagship product direction is [WrenLore](https://github.com/wrenlore/wrenlore): a knowledge and memory layer for teams that want AI to work against source-backed company context rather than a pile of chat history and hope.

Around that, I keep a set of small operating tools for AI agent workflows: clearer briefs, evidence-backed completion, explicit correction learning, evals for repeated failures, source-backed memory, and frontend guardrails.

## Agent Operating Tools

| Repo | Use it when |
| --- | --- |
| [Proof Loop](https://github.com/LeoStehlik/proof-loop) | a coding task needs evidence before anyone calls it done |
| [Sovereign Brain](https://github.com/LeoStehlik/decoupled-agent-memory) | long-running agents need source-backed memory and freshness review |
| [WrenLore](https://github.com/wrenlore/wrenlore) | teams need the product-grade version of source-backed knowledge and agent memory |
| [Better Every Run](https://github.com/LeoStehlik/better-every-run) | explicit corrections should become reviewed lessons, not silent memory sludge |
| [Loopsmith](https://github.com/LeoStehlik/loopsmith) | the same agent failure keeps recurring and should become an eval |
| [Brief Master](https://github.com/LeoStehlik/brief-master) | the task is still fuzzy and needs to become a precise agent brief |
| [no-slop-ui](https://github.com/LeoStehlik/no-slop-ui) | frontend agents need guardrails against generic AI UI sludge |
| [Outlook CLI](https://github.com/LeoStehlik/outlook-cli) | Outlook Classic needs local mailbox automation without Graph or Azure access |
| [x-search-oauth](https://github.com/LeoStehlik/x-search-oauth) | agents need real X/Twitter search through the user's own OAuth path |
| [WordPress Receipts](https://github.com/LeoStehlik/wordpress-receipts) | WordPress publishing should come back with API proof and public URL receipts |
| [Agent Freeboard](https://github.com/LeoStehlik/agent-freeboard) | agent work needs a local dashboard for JSON, MQTT, and live status data |
| [human-writing](https://github.com/LeoStehlik/human-writing) | agent-written copy needs to stop sounding like generic LinkedIn sludge |
| [visual-dna](https://github.com/LeoStehlik/visual-dna) | AI-assisted UI needs reusable design identity instead of one-off vibes |
| [visual-architecture](https://github.com/LeoStehlik/visual-architecture) | agent systems and memory workflows need clean deterministic architecture diagrams |

The workflow is simple: write a better brief, freeze the acceptance criteria, verify the work with evidence, capture deliberate corrections, turn repeated failures into evals, and keep durable decisions attached to sources.

Most of this came from running agents on real work and getting tired of confident final messages that were only half true.
