# Research Journal Guidelines

This document provides guidelines for researchers, LLMs, and code assistants on how to maintain and update the research journal.

## Purpose of the Research Journal

The research journal serves as:
- A chronological record of research activities and decisions
- A centralized repository for experiments, hypotheses, and insights
- A structured system for knowledge management and retrieval
- A collaboration tool for multiple researchers and AI assistants
- A primary source for blog posts, articles, and publications

## Journal Structure

The journal follows a specific format with the following sections:

### 1. 🧭 PLAN
Contains overall project goals and milestones. Use checkboxes to track completion status:
- `[x]` Completed milestone
- `[ ]` Pending milestone
- `[!]` High priority milestone
- `[~]` Low priority milestone

### 2. 🧪 EXPERIMENTS
Each experiment has a standardized format:
```markdown
### 📌 expNNN – Title (YYYY-MM-DD)
Model: model_name
Dataset: dataset_name
Config: {key1: value1, key2: value2, ...}
Author: name

Result:
- Finding 1
- Finding 2
- ...
```
Where:
- `expNNN` is a unique experiment ID (e.g., exp001, exp002)
- Title is a descriptive name
- Date is in ISO format
- Model, Dataset, Config fields document the setup
- Result lists key findings (bullet points)

### 3. 🧠 INSIGHTS & DECISIONS
Documents key insights and design decisions as bullet points. Focus on:
- Important conclusions from experiments
- Design choices and their rationale
- Trade-offs considered and decisions made

### 4. 🧰 MODELS & DATASETS
Lists all models and datasets used in the project:
```markdown
- Model: name - brief description (parameter count)
- Dataset: name - brief description (source)
```

### 5. 📅 DAILY LOGS
Chronological record of research activities:
```markdown
### YYYY-MM-DD
- Activity 1
- Activity 2
- ...
Author: name
```

### 6. ✅ TO DO / NEXT
Lists upcoming tasks with priority markers:
- `[ ]` Standard task
- `[!]` High priority task
- `[~]` Low priority task

### 7. 🔬 HYPOTHESES & THINKING BLOCKS
Documents research hypotheses and thought processes:
```markdown
- H1: Hypothesis statement
- H2: Hypothesis statement
- ...
```

### 8. 🧠 ZETTELKASTEN INDEX
Contains atomic knowledge units that can be linked:
```markdown
[[YYYYMMDDUUU]]: Title
Linked to: [[reference]]
Author: name
```
Where `YYYYMMDDUUU` is a unique ID (date + sequential number).

### 9. 📖 REFERENCES
Academic citations in BibTeX format:
```markdown
- Name: @type{key, title={}, author={}, ...}
Author: name
```

### 10. 📎 LLM SESSION LOGS
Documents interactions with AI assistants:
```markdown
### 🤖 Q&A YYYYMMDDHHMM
**Q:** Question asked
**A:** Answer received
Author: LLM_name
```

### 11. 📝 PUBLICATION DRAFTS
Tracks content being prepared for publication:
```markdown
### 📝 PUB-NN: [Title] (Status: draft/review/submitted)
Target: [blog/article/paper/documentation]
Based on: [exp001, exp002, ...]
Key sections:
- Introduction: [Main idea]
- Methods: [Brief summary]
- Results: [Key findings]
- Discussion: [Main insights]

Author: name
Last updated: YYYY-MM-DD
```

## Activity-Specific Journal Entries

Each research activity requires a dedicated journal entry with goals and mini-roadmap. These structured entries ensure comprehensive documentation for later publication:

### Code Implementation/Fix
```markdown
### YYYY-MM-DD: Code Implementation - [Feature/Fix Name]
Goals:
- Implement/fix [specific functionality]
- Ensure compatibility with [related components]
- Add tests for validation

Mini-Roadmap:
1. [ ] Analyze current implementation
2. [ ] Design solution approach
3. [ ] Implement changes
4. [ ] Test and validate
5. [ ] Document changes

Publication value: [How this activity contributes to future publications]
Author: name
```

### Literature Search
```markdown
### YYYY-MM-DD: Literature Review - [Topic]
Goals:
- Identify key papers on [topic]
- Summarize existing approaches
- Extract relevant methods/findings for our work

Mini-Roadmap:
1. [ ] Search databases with keywords: [list]
2. [ ] Screen initial results
3. [ ] Read and annotate selected papers
4. [ ] Synthesize findings
5. [ ] Update references section

Key papers for citation:
- [author1]: [brief note on relevance]
- [author2]: [brief note on relevance]

Author: name
```

### Experiment Running
```markdown
### YYYY-MM-DD: Experiment - [expNNN] [Title]
Goals:
- Test hypothesis [H#]
- Compare performance of [variables]
- Determine optimal configuration for [task]

Mini-Roadmap:
1. [ ] Setup experimental environment
2. [ ] Configure parameters
3. [ ] Launch experiment runs
4. [ ] Monitor progress
5. [ ] Collect results

Config: {key1: value1, key2: value2, ...}
Publication angle: [How this experiment will feature in publications]
Author: name
```

### Results Collection/Analysis
```markdown
### YYYY-MM-DD: Results Analysis - [expNNN]
Goals:
- Analyze data from experiment [expNNN]
- Compare against baseline/hypothesis
- Identify key patterns and insights

Mini-Roadmap:
1. [ ] Compile raw results
2. [ ] Compute metrics
3. [ ] Create visualizations
4. [ ] Compare against hypotheses
5. [ ] Summarize findings

Key Metrics:
- Metric 1: [value]
- Metric 2: [value]

Publication-worthy findings:
- Finding 1: [brief description]
- Finding 2: [brief description]

Author: name
```

### Debugging Session
```markdown
### YYYY-MM-DD: Debugging - [Issue Description]
Goals:
- Identify root cause of [issue]
- Develop fix with minimal side effects
- Add safeguards against regression

Mini-Roadmap:
1. [ ] Reproduce the issue
2. [ ] Isolate affected components
3. [ ] Trace execution path
4. [ ] Implement fix
5. [ ] Verify resolution

Lessons for documentation:
- [Note any insights worth documenting]

Author: name
```

### Design Planning
```markdown
### YYYY-MM-DD: Design Planning - [Component/Feature]
Goals:
- Architect solution for [requirement]
- Ensure scalability and maintainability
- Define interfaces and data structures

Mini-Roadmap:
1. [ ] Analyze requirements
2. [ ] Evaluate alternative approaches
3. [ ] Draft architecture/design
4. [ ] Review for edge cases
5. [ ] Finalize specifications

Design diagrams: [links or descriptions]
Publication relevance: [architectural insights worth sharing]
Author: name
```

## Guidelines for Updating the Journal

### For Human Researchers

1. **Consistency**: Maintain consistent formatting across all entries.
2. **Chronology**: Date all entries and maintain chronological order within sections.
3. **Attribution**: Include your name in the "Author" field for your entries.
4. **Linking**: Use the Zettelkasten IDs to link related concepts (e.g., `[[20250506101]]`).
5. **Milestones**: Update milestone status as progress is made.
6. **Experiments**: Assign unique IDs (expNNN) to each new experiment.
7. **Daily Logs**: Add entries each research day, even if brief.
8. **Activity Entries**: Create dedicated entries for each research activity with goals and mini-roadmap.
9. **Progress Tracking**: Update the status of mini-roadmap items as they are completed.
10. **Publication Focus**: Tag content with publication potential as you create it.

### For LLMs and Code Assistants

1. **Format Preservation**: Maintain the existing format and structure when adding entries.
2. **Author Attribution**: Always include "Author: [LLM name]" at the end of your entries.
3. **Session Logs**: When answering research questions, format as an LLM session log.
4. **Timestamps**: Use the format YYYYMMDDHHMM for session logs (e.g., 202505061400).
5. **New Entries**: When suggesting new journal entries:
   - Use the correct section headings and formatting
   - Follow the pattern of existing entries
   - Include all required fields
   - Do not modify existing entries unless requested
6. **Activity Support**: When assisting with a research activity, refer to and update the corresponding activity entry.
7. **Publication Support**: Highlight findings and insights that are particularly noteworthy for publication.

## Best Practices

1. **Regular Updates**: Update the journal at least daily during active research.
2. **Granular Experiments**: Create a new experiment entry for each distinct test.
3. **Link Liberally**: Use the Zettelkasten linking system to connect related concepts.
4. **Track TODOs**: Keep the TODO section updated as tasks are completed and new ones arise.
5. **Milestone Status**: Update milestone status promptly to reflect current progress.
6. **Save Insights**: Document insights and decisions as they occur, before they're forgotten.
7. **Precise References**: Include complete bibliographic information for all references.
8. **Config Details**: Document all relevant configuration parameters for experiments.
9. **Activity Closure**: When an activity is completed, update its entry with a summary of outcomes and findings.
10. **Cross-Reference**: Link related activities and experiments to build a connected research narrative.
11. **Publication Tagging**: Mark content with high publication value as you create it.
12. **Narrative Development**: Periodically review entries to identify emerging narratives for publication.

## Using Journal Content

### For Publication and Documentation

The journal is designed to serve as a primary source for creating:
- Research blog posts
- Technical articles
- Conference/journal papers
- Documentation
- Progress reports

When writing content for publication:
1. Use experiment entries as the foundation for methods sections
2. Extract insights and decisions for discussion sections
3. Convert hypotheses into research questions
4. Use daily logs to create narrative flow
5. Leverage references for literature review sections
6. Transform result analyses into figures and tables
7. Collect "publication-worthy findings" notes into highlights

#### From Journal to Publication Process:
```
1. Identify target publication format (blog, article, paper)
2. Create a PUB entry in the Publication Drafts section
3. List relevant journal entries to draw from
4. Extract and organize content from these entries
5. Draft the publication following the target format
6. Review and refine using the journal as a reference
7. Submit/publish and update the PUB entry status
```

### For Analysis and Management

The structured format of the journal allows for:
- Generating reports and summaries
- Extracting experiment results for comparison
- Creating bibliographies from references
- Tracking progress over time
- Building a knowledge graph from Zettelkasten entries

## Automated Processing

The journal's structured format allows for automated processing:
- HTML/PDF generation for sharing and presentation
- Data extraction for analysis and visualization
- Progress tracking and milestone reporting
- Bibliography generation
- Draft publication extraction

---

By following these guidelines, all contributors to the research journal will maintain its structure, organization, and utility, creating a valuable resource for the project and a foundation for high-quality publications.