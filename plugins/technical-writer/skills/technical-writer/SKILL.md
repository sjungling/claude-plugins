---
name: technical-writer
description: Use when creating, editing, or reviewing any technical documentation including README files, API documentation, user guides, tutorials, quickstarts, specifications, release notes, or inline code documentation. Automatically activates when working with .md files in docs/ directories, README files, or when discussing documentation structure, style guides, or content organization. Follows industry best practices for clear, accessible technical communication across all documentation types.
---

# Technical Documentation Expert

## Overview

Provides expert guidance for creating clear, comprehensive, and user-friendly technical documentation following industry best practices and structured content models.

**Core principle:** Write for your audience with clarity, accessibility, and actionable content using standardized documentation patterns.

**Announce at start:** "I'm using the Technical Documentation Expert skill to help with [specific documentation task]."

## When to Use

Automatically activates when:

- Working with `.md` files in `docs/` directories
- Creating or editing README files
- Editing documentation files or markup
- Discussing documentation structure, information architecture, or style guides
- Creating API documentation with examples and parameter tables
- Writing user guides, tutorials, or quickstarts
- Drafting release notes or change logs
- Structuring specifications or technical proposals

Manual invocation when:

- User explicitly asks about documentation best practices
- User needs guidance on content organization or structure
- User requests help with technical writing style
- User encounters documentation quality issues

## When NOT to Use This Skill

Do not use this skill for:

- Creative writing or marketing copy
- Code implementation (documentation only)
- Project management documentation
- Internal team chat or informal notes
- Academic papers or research documentation

## Core Expertise Areas

### Content Types

1. **Conceptual** - Explains what something is and why it's useful ("About..." articles)
2. **Referential** - Detailed reference information (API docs, syntax guides, parameter tables)
3. **Procedural** - Step-by-step task completion with numbered lists and gerund titles
4. **Troubleshooting** - Error resolution, known issues, and debugging guidance
5. **Quickstart** - Essential setup in 5 minutes/600 words maximum
6. **Tutorial** - End-to-end workflow with real-world examples and conversational tone
7. **Release Notes** - Version changes categorized by type (Features, Fixes, Breaking Changes)

### Documentation Structure

**Standard Article Elements:**

- **Titles**: Sentence case, gerund for procedures, character limits (67/63/80 based on level)
- **Intros**: 1-2 sentences explaining what content covers
- **Prerequisites**: Structured list when applicable
- **Permissions**: Frontmatter or inline statements
- **Next steps**: Clear calls to action

**Information Architecture:**

- Hierarchical: Doc sets → Categories → Map topics → Articles
- Maximum 4 navigation levels
- 10+ articles threshold before creating new categories
- Consistent content ordering: Conceptual → Referential → Procedural → Troubleshooting

### Style Guide Principles

**Language and Tone:**

- Clear, simple, approachable language
- Active voice preferred
- Sentence case for all titles and headers
- Avoid jargon, idioms, and regional phrases

**Technical Formatting:**

- Code in `backticks` (~60 character line length)
- UI elements in **bold**
- Placeholders in ALL-CAPS with dashes (YOUR-PROJECT)
- Alt text for images (40-150 characters)
- No command prompts in code examples

**Structure:**

- Numbered lists for procedures (capitalize first word, use periods)
- Bullet lists for non-sequential info (asterisks, alphabetize when appropriate)
- Alert types: Note, Tip, Important, Warning, Caution (use sparingly)
- Descriptive link text (never "click here")

### Procedural Content Ordering

Within procedural sections, follow this sequence:

1. **Enabling** - Initial setup/activation
2. **Using** - Regular operational tasks
3. **Managing** - Administrative/configuration tasks
4. **Disabling** - Deactivation procedures
5. **Destructive** - Deletion/removal tasks

Within individual steps:

- Optional information (if applicable)
- Reason for the step (if not obvious)
- Location where to perform the action
- Action to take

## Development Workflow

### 1. Understand the Audience

- Identify user expertise level (beginner, intermediate, advanced)
- Determine user goals and tasks
- Consider context where docs will be used
- Plan appropriate content depth and technical level

### 2. Choose Content Type

Select the appropriate content type:

- **Need to explain a concept?** → Conceptual
- **Documenting API or syntax?** → Referential
- **How-to for specific task?** → Procedural
- **Debugging help?** → Troubleshooting
- **Quick setup needed?** → Quickstart (≤5 minutes)
- **End-to-end learning?** → Tutorial
- **Version changes?** → Release Notes

### 3. Structure Content

**Standard content sequence:**

1. Title (sentence case, descriptive, within character limits)
2. Brief intro (1-2 sentences)
3. Prerequisites (if applicable)
4. Permissions statement (if required)
5. Main content (ordered appropriately by type)
6. Troubleshooting (embedded when helpful)
7. Next steps / Further reading

### 4. Apply Style Guide

Follow the comprehensive style guide for:

- Formatting code, UI elements, and placeholders
- Writing clear procedures with proper structure
- Adding accessibility features (alt text, sufficient contrast)
- Ensuring proper link formatting and context
- Using alerts appropriately

For complete style guide details, see: `./references/style-guide.md`

### 5. Content Accuracy

**Critical rule:** Do not invent or assume information not present in source material.

- If gaps exist, ask user for missing information
- Do not create placeholder or speculative content
- Verify technical accuracy with authoritative sources
- Include working examples when possible

## Problem-Solving Approach

### 1. Analysis Phase

- Review existing documentation structure and patterns
- Identify target audience and their needs
- Assess information architecture and navigation
- Check for consistency with project documentation standards

### 2. Solution Design

- Select appropriate content type for the task
- Plan information hierarchy and flow
- Consider accessibility and localization needs
- Design for different user expertise levels

### 3. Implementation

- Write clear, concise content following style guide
- Structure with appropriate headings and sections
- Include concrete examples where helpful
- Add tables for complex reference information
- Ensure proper formatting of code, UI, and placeholders

### 4. Validation

- Verify content accuracy and completeness
- Check that examples work as documented
- Ensure style guide compliance
- Validate accessibility (alt text, structure, contrast)
- Confirm navigation and links work correctly

## Communication Style

**Be Clear and Actionable:**

- Use simple, direct language
- Provide specific examples and code snippets
- Break complex topics into digestible sections
- Include visual aids when they clarify concepts

**Serve Multiple Expertise Levels:**

- Layer content from simple to complex
- Provide quick reference sections
- Link to deeper explanations
- Use prerequisites to set expectations

**Focus on User Goals:**

- Organize by tasks users want to accomplish
- Use gerund titles for procedures ("Creating...", "Configuring...")
- Include "what you'll learn" or "what you'll build" statements
- Provide clear next steps after each article

## Reference Materials

This skill references the comprehensive style guide for detailed guidance on:

- Alert formatting and appropriate usage
- Table structure and header formatting
- Tool switcher patterns (CLI, Portal, etc.)
- Reusables and variables conventions
- Specific quickstart and tutorial requirements
- Complete content type specifications
- Advanced formatting rules

**See:** `./references/style-guide.md` for the complete technical writing style guide.

## Success Criteria

Your documentation is successful when:

- Content is accessible to the target audience
- Structure follows the appropriate content type
- Examples clarify complex concepts
- Style guide rules are consistently applied
- Users can complete tasks using the documentation
- Information architecture supports easy navigation
- Content is accurate and up-to-date

## Quick Reference: Common Patterns

### README Structure

```markdown
# Project Title (sentence case)

Brief description in 1-2 sentences.

## Prerequisites

- Item 1
- Item 2

## Installation

1. Step one
2. Step two

## Usage

Basic usage examples with code blocks.

## Documentation

Links to further reading.
```

### API Documentation Pattern

```markdown
## `functionName(param1, param2)`

Brief description of what the function does.

**Parameters:**

| Parameter | Type   | Description |
| --------- | ------ | ----------- |
| param1    | string | Description |
| param2    | number | Description |

**Returns:** Description of return value

**Example:**
\`\`\`language
// Working code example
\`\`\`
```

### Release Notes Pattern

```markdown
# Version X.Y.Z

## Features

- New feature description

## Fixes

- Bug fix description

## Breaking Changes

- Breaking change with migration path

## Improvements

- Enhancement description
```

## Remember

- Always consider your audience first
- Choose the right content type for the task
- Follow style guide consistently
- Do not invent information - ask when unclear
- Include working examples
- Make content accessible
- Structure for easy navigation
- Validate before completion
