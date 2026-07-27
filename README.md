# GeoCopilot

GeoCopilot is an autonomous computational workspace for geospatial analysis. It brings an intelligent agent into the JupyterLab notebook—the place where researchers work with data, code, maps, figures, and intermediate results—so that these materials can remain part of one continuous analytical process.

Rather than acting as a separate chat interface, GeoCopilot works with the state of an active workspace. It can advance an analysis, inspect what actually happened during computation, and use the resulting evidence to decide what to do next. Researchers remain responsible for research questions, methodological choices, and scientific interpretation.

## Research vision

Geospatial analysis commonly moves back and forth between data preparation, method selection, programming, model execution, result inspection, and explanation. GeoCopilot is designed to turn this fragmented work into a collaborative workflow: the researcher states an objective or gives feedback; the agent carries out appropriate operations in a real computational environment; and the resulting code, maps, tables, and explanations are returned to the notebook for review.

## How it works

GeoCopilot follows a continuing reasoning–execution–observation cycle:

1. **Understand** the research objective and the data, code, and results already present in the notebook.
2. **Execute** appropriate analytical actions and access available geospatial resources.
3. **Observe** program output, maps, tables, warnings, and errors.
4. **Refine** the next step until the researcher has a result that can be inspected and discussed.

This loop supports multi-step geospatial work while keeping the analytical record visible and reviewable.

## Human–AI collaboration

GeoCopilot is intended to reduce the burden of procedural execution and repair, not to replace researchers. The researcher defines the problem, evaluates methodological soundness, reviews results, and determines the next direction. The agent helps translate these decisions into an executable workflow and preserves a traceable notebook record.

## Evaluation

In the accompanying study, GeoCopilot was evaluated on 90 geospatial analysis tasks. It achieved a **98.9% task-completion rate**, required an average of **1.38 human–agent interaction rounds** per task, and performed about **25 internal operations and tool calls** for each researcher request.

> Zhou, M., Ma, P., Xie, W., Sheng, T., Wen, Y., Yue, S., Lv, G., & Chen, M. (2026). *GeoCopilot: Accelerating Geospatial Analysis Tasks with Autonomous Computational Workspace*.

## License

MIT

## Dataset

The GeoCopilot evaluation dataset is available on Zenodo: https://zenodo.org/records/21450280
