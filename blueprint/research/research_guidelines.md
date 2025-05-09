# Research Guidelines

This document provides guidelines for researchers, LLMs, and code assistants on how to maintain and update the research-specific components of the project.

## Purpose of Research Documentation

The research documentation serves as:
- A record of scientific hypotheses, experiments, and findings
- A structured system for knowledge management in research contexts
- A framework for reproducible scientific inquiry
- A source for academic publications and research reports

## Research Module Components

### Research Journal
The primary tool for tracking scientific research activities. Located at `research_journal.md` in the project root.

### Research Documents
Supplementary documentation for research aspects:
- Literature reviews
- Experiment protocols
- Analysis methodologies
- Data collection procedures

### Research Templates
Standardized formats for common research activities:
- Experiment documentation
- Literature review
- Data analysis
- Hypothesis formulation

## Research Journal Structure

The research journal follows a specific format with these research-focused sections:

### 1. 🧭 RESEARCH PLAN
Contains research questions, hypotheses, and investigation approaches.

### 2. 🧪 EXPERIMENTS
Detailed documentation of experimental setup, execution, and results.

### 3. 📊 DATA & ANALYSIS
Information about datasets, analysis methodologies, and findings.

### 4. 🔬 HYPOTHESES & THEORIES
Formal statements of research hypotheses and theoretical frameworks.

### 5. 📚 LITERATURE REVIEW
Summaries and analyses of relevant academic literature.

### 6. 📝 PUBLICATION DRAFTS
Content being prepared for academic or research publication.

## Research Experiment Documentation

Each experiment should be documented with:
```markdown
### 📌 expNNN – Title (YYYY-MM-DD)
Hypothesis: Reference to relevant hypothesis
Setup: {key parameters and conditions}
Variables:
  - Independent: [variables manipulated]
  - Dependent: [variables measured]
  - Controlled: [variables held constant]
Method:
  1. [Step 1]
  2. [Step 2]
Results:
  - Finding 1
  - Finding 2
Analysis:
  [Brief analysis of findings]
Conclusions:
  [What was learned]
Next Steps:
  [Recommended follow-up]
Author: [name]
```

## Research-Development Integration

Research activities often inform development priorities and requirements. To facilitate this connection:

1. Link research findings to development tasks using a consistent format:
   ```
   Development Implications: [brief description] #dev-task-123
   ```

2. When development needs trigger research questions, document with:
   ```
   Research Question from Development: [question] #research-q-456
   ```

3. Use cross-references between research journal and development journal:
   ```
   See research experiment exp007 for methodology details
   ```

## Current Focus Section

The CURRENT FOCUS section of the research journal is critical for ongoing research management:

```markdown
## 🔍 CURRENT FOCUS

### Active Priority: [Research activity description]
Associated with: [experiment IDs, hypotheses, or plan items]
Started: YYYY-MM-DD
Status: [planning/in-progress/nearing-completion]
Blocking: [any blocked tasks or dependencies]

Research Goals:
- [Specific research goal 1]
- [Specific research goal 2]

Research Mini-Roadmap:
1. [ ] [Research step 1]
2. [ ] [Research step 2]
3. [ ] [Research step 3]

Next decision point: [When/what will determine next research steps]
```

Guidelines for maintaining the CURRENT FOCUS section:
1. Keep it updated with the most pressing research priorities
2. Link explicitly to related experiments and hypotheses
3. Include clear research goals and expected outcomes
4. Maintain a detailed mini-roadmap of steps
5. Update status as research progresses
6. Document the next decision point for research direction

## Publication Pathway

Research documentation should support creating publications:

1. Tag content with publication potential using:
   ```
   Publication Value: [brief description of contribution]
   ```

2. Use the PUBLICATION DRAFTS section to organize content for papers:
   ```
   ### 📝 PUB-NN: [Academic Title] (Status: draft/submitted)
   Target: [journal/conference]
   Based on: [exp001, exp002, ...]
   Abstract: [brief summary]
   ```

## Research Standards

Research activities should maintain:
1. **Reproducibility**: Document methods thoroughly
2. **Transparency**: Disclose limitations and assumptions
3. **Rigor**: Use appropriate methodologies
4. **Attribution**: Cite sources properly
5. **Ethics**: Consider ethical implications of research