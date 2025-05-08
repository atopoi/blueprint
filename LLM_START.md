# LLM Entry Point Guide

## Welcome, AI Assistant

This document serves as the primary entry point for AI assistants (LLMs and code assistants) collaborating on this research project. It provides high-level guidance on how to understand the project methodology, navigate the documentation ecosystem, and follow established development rules.

## Meta-Methodology

This project follows a structured research and development methodology with these core principles:

1. **Documentation-First Development**: All decisions, experiments, and code changes are documented before implementation.

2. **Knowledge-Centered Collaboration**: A roadmap file defines the high-level goals and plan, while a central research journal serves as the authoritative source of truth for project execution, history, and status.

3. **Incremental Progress Tracking**: Work is organized into trackable units with goals, roadmaps, and status indicators.

4. **Publication-Oriented Research**: Research activities and journals are structured to facilitate later creation of publications (blogs, articles, papers).

5. **Reproducible Experiments**: All experimental work is fully documented for reproducibility.

6. **Transparency & Attribution**: When leveraging external content or insights, always cite the original source and author to maintain transparency, credit, and traceability.

## Documentation Ecosystem Navigation

Follow this sequence to build your understanding of the project:

1. **Start Here (LLM_START.md)**: High-level guidance (this document)
2. **Research Journal (research_journal.md)**: Project history, experiments, and current status
3. **Journal Guidelines (blueprint/journal-guidelines.md)**: Rules for maintaining the research journal
4. **Project Roadmap (blueprint/roadmap.md)**: Overall project plan and technical specifications
5. **More spec documents (blueprint/documents/\*.md)**: Additional specifications and documentation

### Key Files and Their Purpose

| File | Purpose |
|------|---------|
| LLM_START.md | Entry point guide for AI assistants |
| README.md | Project overview for general audience |
| research_journal.md | Comprehensive project history and status |
| blueprint/journal-guidelines.md | Format and rules for journal entries |
| blueprint/roadmap.md | Overall project plan and milestones |
| blueprint/documents/\*.md | Additional specifications and documentation |

## Understanding Project Context

To quickly understand the current project context:

1. Use the roadmap (`blueprint/roadmap.md`) as a reference; it outlines:
   - High-level goals and context
   - Strategies and methodologies
   - Constraints and resources
   - Milestones
2. When updating the roadmap, ensure changes are proposed by human authors or explicitly validated by them.
3. Review the **CURRENT FOCUS** section in the research journal (`research_journal.md`).
4. Check recent daily log entries for ongoing activities.
5. Review the TODO/NEXT section for pending tasks.
6. Look at active experiments with incomplete status.

## Participation Guidelines

When assisting with this project, please follow these principles:

### General Rules

1. **Stay within the established methodology**: Follow the journal format and documentation structure.
2. **Provide attributable contributions**: For content sourced externally (e.g., papers, blogs, code snippets), explicitly cite the original source and author.
3. **Focus on current priorities**: Check the CURRENT FOCUS section before making suggestions.
4. **Maintain the knowledge graph**: Use proper linking between related concepts.
5. **Preserve documentation hierarchy**: Know which document is authoritative for different information.

### How to Respond to Queries

1. **Research Phase Queries**:
   - State explicitly the questions, context, and hypotheses
   - Explain the methodology, constraints, and assumptions
   - Reference relevant journal entries for background and previous results
   - Suggest potential experiments and outline expected outcomes
   - Before launching an experiment: assign a unique name, describe its purpose, scope, and constraints
   - When experiments fail, document and explain the failure modes
   - Link to related scientific literature for context and methods
   - Structure responses to support future publication

2. **Development Phase Queries**:
   - Follow code implementation guidelines and style conventions
   - Maintain consistency with the existing codebase and architecture
   - Document changes in the journal before implementation
   - Link implementation details to experiment results or requirements
   - Prefer simple, clear solutions; discuss alternatives as needed
   - Ensure reproducibility of code and experimental environments

3. **Analysis Phase Queries**:
   - Propose a concise summary of key results with context
   - Provide links to full results or embed them in tables and figures
   - Notify project leads or stakeholders of critical outcomes
   - Connect analysis back to hypotheses and project objectives
   - Highlight publication-worthy findings and insights
   - Suggest follow-up experiments or next steps

4. **Publication Phase Queries**:
   - Extract content from journal entries
   - Structure information for target publication format
   - Maintain academic rigor and citation standards
   - Preserve links back to source experiments

## Journal-Specific Guidance

The research journal is the central knowledge repository for this project. When working with it:

1. **Respect the sections**: The journal has specific sections for different types of information.
2. **CURRENT FOCUS section**: Pay special attention to the current focus section which indicates active priorities.
3. **Follow the format**: Use the established format for different entry types.
4. **Cross-reference entries**: Use the ID system to link related information.
5. **Preserve chronology**: Do not alter the historical record of past entries.

The detailed formatting rules are in `blueprint/guides/journal-guidelines.md`.

## Creating and Updating Journal Entries

When asked to create or update a journal entry:

1. Follow the activity-specific templates in the guidelines
2. Include all required fields (author, date, goals, etc.)
3. Structure content for later publication use
4. Add appropriate cross-references to related entries
5. Update status fields when activities progress

For new entries in the CURRENT FOCUS section, use this format:

```markdown
## 🔍 CURRENT FOCUS

### Active Priority: [Brief description]
Associated with: [experiment/task IDs]
Started: YYYY-MM-DD
Status: [planning/in-progress/nearing-completion]
Blocking: [any blocked tasks]

Goals:
- Goal 1
- Goal 2

Mini-Roadmap:
1. [ ] Step 1
2. [ ] Step 2
...

Next decision point: [When/what will determine next steps]
```

## Code Implementation Rules

When implementing or suggesting code changes:

1. Document the changes in the journal first
2. Follow the project's code style and conventions
3. Ensure compatibility with the existing architecture
4. Write tests for new functionality
5. Update relevant documentation
6. Link the implementation to experiments or requirements

## Asking for Clarification

If the project documentation is unclear or contradictory:

1. Identify the specific area of confusion
2. Reference the relevant documentation sections
3. Suggest potential interpretations
4. Ask for clarification before proceeding

## Project Setup
In the first interactions:
1. Check your understanding of the roadmap with the user. Ask for clarifications and fill in missing parts interactively if needed.
2. Setup the journal according to the roadmap and specs, with the user's approval.

## Final Notes

This document provides high-level guidance. Always defer to project-specific instructions when they exist. When in doubt, prioritize:

1. Explicit instructions from human researchers
2. Information in the CURRENT FOCUS section
3. Recently updated journal entries
4. The general guidelines in this document

By following this guide, you'll be able to effectively contribute to the project within its established methodology and documentation structure.

---

## Special Queries

These custom operations extend the assistant’s capabilities:

- **Interactive Merge**: Given two file versions, generate and present a diff, then interactively resolve conflicts one by one with the user. Once approved, update the first file with the merged content.
- **Expand Formulate**: Locate all labels marked `FORMULATE:` in the document. For each, rephrase the subsequent text and keywords to match the style and tone of this guide, retaining original intent and structure.
- **Search Cite**: Locate labels marked `CITE:` in the document. For each, search for precise, authoritative sources (e.g., academic papers, official documentation), and insert properly formatted citations (author, title, year, URL or DOI).

**Recommended first action**: Read the roadmap and CURRENT FOCUS section of the research journal to understand immediate priorities.
