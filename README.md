[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=58A6FF&center=false&vCenter=true&width=600&lines=Staff+Software+Engineer+%40+RBC+AI+Advice+Centre;Toronto)](https://git.io/typing-svg)

I build the agents that listen in on live call-centre conversations, work
out what the customer actually needs, and carry it through to resolution.
Some of that's a model, some of it's just a state machine, whichever one
is right for the step.

Picking the model is its own job. Sometimes a frontier model (GPT, Claude,
Gemini) is the fast path. Other times it has to run on-prem, cost, latency, or data
residency, and then it's on us end to end: fine-tune it (SFT, QLoRA when
the GPU won't fit the full thing, DPO to align it after), deploy it, keep
the GPUs fed. Same fleet runs embedding models and classifier heads next
to the LLMs, Nemotron's one of them, for agentic orchestration. The
unglamorous part is most of the job: fault tolerance, keeping the model
honest, not falling over at scale.

Outside of that: homelab networking, chaos engineering, breaking things
on purpose before they break on their own.

**Currently building**
- MCP server for TP-Link Omada SDN controllers
- self-hosted Nemotron Lightning 30B agent on OpenShift KServe

[LinkedIn](https://www.linkedin.com/in/samiul-haque) · [site](https://www.samiulhaque.com/)
