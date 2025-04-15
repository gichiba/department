# LLM Workflow for Protocol Fiction

This document outlines the cyclical workflow process for LLM collaboration in developing "The Department of Dark Forestry" protocol fiction.

## Core Workflow Cycle

### 1. Re-read All Files
- **Purpose**: Establish complete context and ensure canonical consistency
- **Process**: 
  - Read all files in fragments/, protocol/, world/, and drafts/ directories
  - Pay special attention to recently modified files
  - Build comprehensive mental model of the current state of the world
  - Verify style consistency across all documents with the style guide

### 2. Analyze Fragments
- **Purpose**: Extract meaning and patterns from raw story elements
- **Process**:
  - Identify key terminology, mechanisms, and rules
  - Look for implicit world-building elements not yet formalized
  - Connect new fragments to existing canonical framework
  - Flag any style inconsistencies in the fragments

### 3. Find Patterns
- **Purpose**: Identify emergent rules or canonical elements
- **Process**:
  - Compare fragments for consistent themes or mechanisms
  - Identify contradictions or logical extensions of existing rules
  - Determine if patterns suggest new rules or canon

### 4. Update Protocol and World
- **If new rules needed**:
  - Create new files in the protocol/ directory for specific rule systems
  - Refine existing protocol documents for clarity and consistency
  - Consider creating specialized protocol documents for particular mechanisms

- **If new canon detected**:
  - Create new files in the world/ directory for specific canonical elements
  - Develop specialized documents for particular aspects of the world
  - Maintain separation between different canonical domains

- **If style inconsistencies detected**:
  - Apply existing style guidelines to resolve inconsistencies
  - If no guideline exists for the inconsistency:
    1. Propose an amendment to the style guide
    2. Document the issue with specific examples
    3. Provide a clear resolution approach

### 5. Generate Draft
- **Purpose**: Create narrative text following protocol constraints
- **Process**:
  - Apply rules from protocol/ directory
  - Maintain consistency with world/ canonical framework
  - Create draft narratives in drafts/ directory
  - Focus on systems and protocols over character development

### 6. Extract Fragments
- **Purpose**: Decompose drafts into new canonical elements
- **Process**:
  - Identify strong standalone concepts from drafts
  - Extract as new fragment files in fragments/ directory
  - Prepare extracted fragments for verification

### 7. Style Consistency Check
- **Purpose**: Ensure all documents adhere to style guidelines
- **Process**:
  - Verify formatting against style_guide.md standards
  - Check for consistent terminology, capitalization, and structure
  - Document any inconsistencies found
  - Propose style guide amendments if needed

### 8. Loop Back to Re-read
- Return to step 1, maintaining a continuous improvement cycle

## Context Refresh Triggers

The workflow should restart from step 1 (Re-read All Files) whenever:

1. **New Conversation**: Starting a fresh LLM session requires rebuilding context
2. **Files Changed**: Any file modifications should trigger a full re-read
3. **Style Guide Updated**: Changes to style_guide.md should trigger a review of relevant documents

## Implementation Guidelines

### Creating New Fragments
```
- Place raw story elements in fragments/ directory
- Use descriptive filenames (e.g., temporal_funding.md)
- Keep fragments focused on specific concepts or scenes
```

### Developing Protocol Rules
```
- Create new protocol files based on clear patterns across multiple fragments
- Design rule systems as constraints that enable creativity rather than limit it
- Organize protocol documents by mechanism or concept (e.g., vm_operations.md)
```

### Expanding World Canon
```
- Create new world/ files when patterns establish new canonical elements
- Develop specialized canonical documents for distinct aspects (e.g., department_structure.md)
- Express canonical elements in clear, unambiguous language
```

### Draft Generation
```
- Create drafts that explicitly demonstrate application of protocol rules
- Structure drafts to reveal canonical elements organically
- Use consistent naming: drafts/[number]-[concept]-fragment.md
```

## Ensuring Protocol-First Fiction

The primary focus of this workflow is to create fiction that:

1. Prioritizes strange systems and rules over special individuals
2. Builds narrative tension through logical implications of rules
3. Creates emergent storytelling through consistent application of constraints
4. Maintains canonical consistency across a distributed writing process

By following this cyclical workflow, LLMs assist in developing a coherent protocol fiction world that grows richer and more internally consistent with each iteration of the process.
