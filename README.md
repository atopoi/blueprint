# Blueprint

Minimalist, vendor-agnostic guidelines and tools to transform any project into a structured research workflow for both AI assistants and human collaborators.

## Getting Started

The core components of this blueprint:

- `LLM_START.md`: Entry-point guide for AI and code assistants.
- `blueprint/roadmap.md`: Document high-level project goals, strategies, constraints, and milestones.
- `blueprint/getting-started.md`: Setup instructions and usage examples.
- `blueprint/journal-guidelines.md`: Templates and rules for maintaining the research journal.
- `blueprint/documents/`: Folder for additional specification and documentation files.
- `examples/`: Sample journal entries and experiment logs.
  
Copy these files and folders into your project to bootstrap your R&D workflow.

## Usage

### Setup
1. Copy `LLM_START.md` and the `blueprint/` directory into your project repository.
2. Customize `blueprint/roadmap.md` with your project’s goals, methodologies, resources, and milestones.
3. (Optional) Add detailed specifications or design documents under `blueprint/documents/`.
4. Create or copy a research journal file (e.g., `research_journal.md`) and follow the templates in `blueprint/journal-guidelines.md`.
5. Refer to the `examples/` folder for sample journal entries and experiment logs.

### Running Sessions
At the start of each session, instruct your AI assistant to read and adhere to `LLM_START.md`. This ensures consistent context and methodology.


## Special Queries

This blueprint includes three advanced operations for AI assistants. See the **Special Queries** section in `LLM_START.md` for details:

- **Interactive Merge**: Diff two file versions, resolve conflicts interactively, and update the target file.
- **Expand Formulate**: Locate `FORMULATE:` labels and rephrase the following text to match document style.
- **Search Cite**: Locate `CITE:` labels, find authoritative sources, and insert properly formatted citations.

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Reporting issues and suggesting features
- Code reviews and pull requests
- Documentation improvements

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
