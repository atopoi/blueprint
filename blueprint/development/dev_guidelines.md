# Development Guidelines

This document provides guidelines for developers, LLMs, and code assistants on how to maintain and update the development-specific components of the project.

## Purpose of Development Documentation

The development documentation serves as:
- A record of technical decisions, implementations, and changes
- A structured system for task management and code organization
- A framework for maintaining software quality and consistency
- A source for technical documentation and knowledge transfer

## Development Module Components

### Development Journal
The primary tool for tracking software development activities. Located at `dev_journal.md` in the project root.

### Development Documents
Supplementary documentation for development aspects:
- Architecture diagrams
- API specifications
- Code style guides
- Technical requirements

### Development Templates
Standardized formats for common development activities:
- Feature implementation
- Bug fixes
- Code refactoring
- Performance optimization

## Development Journal Structure

The development journal follows a specific format with these development-focused sections:

### 1. 🏗️ ARCHITECTURE
Contains system design, component relationships, and technical decisions.

### 2. 🚀 FEATURES
Detailed documentation of feature implementation, requirements, and status.

### 3. 🐛 BUGS & FIXES
Information about identified issues, root causes, and resolution approaches.

### 4. ⚙️ REFACTORING
Documentation of code improvements, technical debt reduction, and optimization.

### 5. 🧪 TESTING
Test plans, coverage information, and testing methodologies.

### 6. 📋 DEVELOPMENT TASKS
Current and upcoming development work items and their status.

## Feature Implementation Documentation

Each feature implementation should be documented with:
```markdown
### 🚀 Feature: [Name] (YYYY-MM-DD)
Status: [planning/in-progress/review/complete]
Requirements:
  - [Functional requirement 1]
  - [Functional requirement 2]
Technical Approach:
  - Framework/libraries: [tools used]
  - Architecture decisions: [key design choices]
Implementation:
  1. [Step 1]
  2. [Step 2]
Files Changed:
  - [file/path]: [brief description of changes]
Testing:
  - [Test case 1]
  - [Test case 2]
Deployment Notes:
  [Special considerations for deployment]
Author: [name]
```

## Development-Research Integration

Development activities often require research insights or generate research questions. To facilitate this connection:

1. Link development tasks to research findings using a consistent format:
   ```
   Research Basis: [brief description] #research-exp-123
   ```

2. When implementation challenges suggest research needs, document with:
   ```
   Research Question from Implementation: [question] #research-q-456
   ```

3. Use cross-references between development journal and research journal:
   ```
   See development feature F007 for implementation details
   ```

## Current Focus Section

The CURRENT FOCUS section of the development journal is essential for task management:

```markdown
## 🔍 CURRENT FOCUS

### Active Priority: [Development activity description]
Associated with: [feature IDs, tickets, or architecture components]
Started: YYYY-MM-DD
Status: [planning/implementation/testing/review]
Blocking: [any blocked tasks or dependencies]

Development Goals:
- [Specific development goal 1]
- [Specific development goal 2]

Development Mini-Roadmap:
1. [ ] [Development step 1]
2. [ ] [Development step 2]
3. [ ] [Development step 3]

Next milestone: [When/what will determine next development steps]
```

Guidelines for maintaining the CURRENT FOCUS section:
1. Keep it updated with current development priorities
2. Link explicitly to related features and components
3. Include clear technical goals and acceptance criteria
4. Maintain a detailed mini-roadmap of implementation steps
5. Update status as development progresses
6. Document the next development milestone

## Documentation Pathway

Development documentation should support creating technical documentation:

1. Tag content with documentation potential using:
   ```
   Documentation Value: [brief description of what should be documented]
   ```

2. Use a structured approach for technical documentation:
   ```
   ### 📝 DOC-NN: [Component/Feature Name] (Status: draft/published)
   Target: [API docs/user manual/developer guide]
   Based on: [feature1, feature2, ...]
   Key sections:
   - Usage: [brief description]
   - Configuration: [brief description]
   - Examples: [brief description]
   ```

## Development Standards

Development activities should maintain:
1. **Code Quality**: Follow established code standards and practices
2. **Testing**: Ensure appropriate test coverage
3. **Documentation**: Document code, APIs, and user interfaces
4. **Maintainability**: Consider future maintenance needs
5. **Security**: Follow security best practices