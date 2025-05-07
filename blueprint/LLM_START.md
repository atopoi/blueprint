# AI Assistant Entry Point Guide

## Welcome, AI Assistant

This vendor-agnostic guide serves as the primary entry point for any AI assistant (model or code assistant) collaborating on this research project. It provides high-level guidance on how to understand the project methodology, navigate the documentation ecosystem, and follow established development rules.

## Meta-Methodology

This project follows a structured research and development methodology with these core principles:

1. **Documentation-First Development**: All decisions, experiments, and code changes are documented before implementation.

2. **Knowledge-Centered Collaboration**: A central research journal serves as the authoritative source of truth for project history and status.

3. **Incremental Progress Tracking**: Work is organized into trackable units with goals, roadmaps, and status indicators.

4. **Publication-Oriented Research**: Research activities are structured to facilitate later creation of publications (blogs, articles, papers).

5. **Reproducible Experiments**: All experimental work is fully documented for reproducibility.

## Documentation Ecosystem Navigation

Follow this sequence to build your understanding of the project:

1. **Start Here (blueprint/LLM_START.md)**: High-level guidance (this document)
2. **Research Journal (research_journal.md)**: Project history, experiments, and current status
3. **Journal Guidelines (blueprint/journal-guidelines.md)**: Rules for maintaining the research journal
4. **Project Roadmap (blueprint/roadmap.md)**: Overall project plan and technical specifications
5. **More specs files (blueprint/specs/\*.md)**: Other specs and documents

### Key Files and Their Purpose

| File | Purpose |
|------|---------|
| LLM_START.md | Entry point guide for AI assistants |
| README.md | Project overview for general audience |
| research_journal.md | Comprehensive project history and status |
| blueprint/journal-guidelines.md | Format and rules for journal entries |
| blueprint/roadmap.md | Overall project plan and milestones |
| blueprint/getting-started.md | Setup and usage instructions |
| blueprint/specs/\*.md | more specs and documents |

## Understanding Project Context

To quickly understand the current project context:

1. Review the **CURRENT FOCUS** section in the research journal
2. Check recent daily log entries for ongoing activities
3. Review the TODO section for pending tasks
4. Look at active experiments with incomplete status

## Participation Guidelines

When assisting with this project, please follow these principles:

### General Rules

1. **Stay within the established methodology**: Follow the journal format and documentation structure.
2. **Provide attributable contributions**: Sign your inputs with your name.
3. **Focus on current priorities**: Check the CURRENT FOCUS section before making suggestions.
4. **Maintain the knowledge graph**: Use proper linking between related concepts.
5. **Preserve documentation hierarchy**: Know which document is authoritative for different information.

### How to Respond to Queries

1. **Research Phase Queries**: 
   - Reference relevant journal entries
   - Suggest potential experiments
   - Link to related scientific literature
   - Structure responses to support future publication

2. **Development Phase Queries**:
   - Follow code implementation guidelines
   - Maintain consistency with existing codebase
   - Document changes in the journal
   - Link implementation to experiment results

3. **Analysis Phase Queries**:
   - Focus on reproducibility
   - Connect results to hypotheses
   - Highlight publication-worthy findings
   - Suggest follow-up experiments

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

## Final Notes

This document provides high-level guidance. Always defer to project-specific instructions when they exist. When in doubt, prioritize:

1. Explicit instructions from human researchers
2. Information in the CURRENT FOCUS section
3. Recently updated journal entries
4. The general guidelines in this document

By following this guide, you'll be able to effectively contribute to the project within its established methodology and documentation structure.

---

**Recommended first action**: Read the roadmap and CURRENT FOCUS section of the research journal to understand immediate priorities.
