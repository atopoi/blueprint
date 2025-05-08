# Blueprint

Minimalist, vendor-agnostic, drop-in instruction files to transform any project into a structured research workflow for both AI assistants and human collaborators.


## Getting Started

### Setup
1. Copy `LLM_START.md`, `research_journal.md`, and the `blueprint/` directory into your project repository.
2. Customize `blueprint/roadmap.md` with your project’s goals, methodologies, resources, and milestones. It can be minimal at first and refined interactively later.
3. Instruct the LLM or coding agent to read and follow `LLM_START.md`.

That's it! The coding assistant becomes a research assistant!

### Optional
- You can add detailed specifications or design documents at any time under `blueprint/documents/`. Just ask the agent to read them.
- There are additional journal templates in `examples/`, but it’s best to ask the agent if you want to tweak the journal.

### Running Sessions
At the start of each session, instruct your AI assistant to read and adhere to `LLM_START.md`. This ensures consistent context and methodology.


## How it works

The file `LLM_START.md` provides global instructions to the AI assistant. It’s human-readable, be sure to review it!

The agent uses the `research_journal` to manage all activities. It should automatically update the journal in a systematic, structured manner during project execution. This journal is also human-readable and modeled according to established research practices. The agent uses the methods defined in `blueprint/journal-guidelines.md` to use and edit the journal.

The other key file is `blueprint/roadmap.md`, which documents high-level project goals, strategies, constraints, and milestones. First written by the user, it will be updated and formatted by the agent. A good practice is to ask the agent to analyze the roadmap during project setup and interactively elaborate on it. Also, the roadmap can be updated and refined at any time for experimental and exploratory R&D. In fact, many AI assistants excel at this. The user can also edit the roadmap manually, then ask the agent to read it again.


## Special Queries

As an additional practical feature, you can define a list of common useful queries for the AI assistant. See the **Special Queries** section in `LLM_START.md` for details. For example:

- **Interactive Merge**: Diff two file versions, resolve conflicts interactively, and update the target file.
- **Expand Formulate**: Locate `FORMULATE:` labels and rephrase the following text to match document style.
- **Search Cite**: Locate `CITE:` labels, find authoritative sources, and insert properly formatted citations.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
