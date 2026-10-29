# 03-harness

The platform itself: everything a CPG company is apart from the brand. One
folder per layer, bottom up.

- `erp/`: ERP platform selection and the standard CPG configuration, by process domain.
- `knowledge-graph/`: end-to-end CPG process knowledge the agents draw on.
- `agents/`: the AI operator layer: orchestrator, agent specs per function, guardrails.
- `channels/`: GTM channel integrations, one folder per channel.
- `warehousing/`: consignment model, warehouse operations, service billing.
- `entities/`: one geography equals one legal entity: siloing and financial visibility.

Rule of thumb: nothing brand-specific belongs here. If it does, the harness is
not yet general purpose.
