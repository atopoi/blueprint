# Blueprint

Minimalist, vendor-agnostic, drop-in instruction files to transform any project into a structured workflow for both AI assistants and human collaborators.

## Getting Started

### Setup
1. Copy `LLM_START.md` and the `blueprint/` directory into your project repository.
2. Choose the appropriate module for your project:
   - For scientific research: Use `blueprint/research/research_journal.md`
   - For software development: Use `blueprint/development/dev_journal.md`
   - For combined projects: Use both journals with `blueprint/module_integration.md`
3. Customize `blueprint/roadmap.md` with your project's goals, methodologies, resources, and milestones.
4. Instruct the LLM or coding agent to read and follow `LLM_START.md`.

That's it! The coding assistant becomes a structured project collaborator!

### Optional
- You can add detailed specifications or design documents at any time under `blueprint/documents/`. Just ask the agent to read them.
- There are additional journal templates in `examples/`, but it's best to ask the agent if you want to tweak the journal.

### Running Sessions
At the start of each session, instruct your AI assistant to read and adhere to `LLM_START.md`. This ensures consistent context and methodology.

## How it works

The file `LLM_START.md` provides global instructions to the AI assistant. It's human-readable, be sure to review it!

Blueprint uses a modular approach with specialized components:

1. **Research Module**: Scientific investigation, experiments, and academic outputs
   - `research_journal.md`: Tracks experiments, hypotheses, and research findings
   - `research_guidelines.md`: Standards for research documentation

2. **Development Module**: Software implementation and technical tasks
   - `dev_journal.md`: Tracks features, bugs, and code changes
   - `dev_guidelines.md`: Standards for development documentation

3. **Core Components**: Project foundation and integration
   - `roadmap.md`: High-level project goals, strategies, and milestones
   - `module_integration.md`: Guidelines for connecting research and development

### Future Plans
A management module is planned for future releases, which will focus on:
- Project planning and coordination
- Resource allocation
- Timeline tracking
- Team collaboration
- Risk management

## Special Queries

As an additional practical feature, you can define a list of common useful queries for the AI assistant. See the **Special Queries** section in `LLM_START.md` for details. For example:

- **Interactive Merge**: Diff two file versions, resolve conflicts interactively, and update the target file.
- **Expand Formulate**: Locate `FORMULATE:` labels and rephrase the following text to match document style.
- **Search Cite**: Locate `CITE:` labels, find authoritative sources, and insert properly formatted citations.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.