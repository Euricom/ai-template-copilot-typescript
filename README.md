# README.md - Copilot    Template Project

A modern project structure optimized for efficient AI-assisted development using Copilot.

## Overview

This repository provides a standardized structure for AI-enhanced software development workflows. Rather than directly inputting commands, documentation, and feature requests into the CLI of Copilot, this structure offers a more organized, version-controlled, and collaborative approach to working with AI coding assistants.

## Directory Structure

```
{root}/
├── .copilot/
│   ├── prompts/                # Prompt files for copilot
|   |    ├── prime.prompt.md    # Context initialization command
│   |    └── ...
|   └── copilot-instructions.md # root instructions for copilot
├── ai_docs/            # AI-specific documentation
│   ├── AI_DOCS.md      # Documentation for AI docs system
│   └── ...
├── specs/              # Feature specifications
│   ├── SPECS.md        # Documentation for specs system
│   └── ...
└── README.md           
```

## Key Components

### 1. AI Documentation (`ai_docs/`)

Specialized documentation that enhances AI models' understanding of your project:

- **Domain-Specific Knowledge**: Terminology, architecture, and design patterns
- **Implementation Details**: System relationships and code examples
- **Enhanced Generation**: Helps Copilot generate code aligned with your project's patterns
- **Invocation Syntax**: Use `@[path/to/document]` to reference docs in conversations

### 2. Feature Specifications (`specs/`)

Structured specifications for planned features:

- **Implementation Blueprint**: Detailed specs for types, methods, tests, and validation
- **Consistent Design**: Standardized format ensures all necessary details are included
- **AI-Ready Format**: Optimized for consumption by Copilot
- **Invocation Syntax**: Use `@[path/to/spec.md]` to reference in conversations

## Using the Prime Command

The `prime.promp.md` prompt fills the context window with essential project information:

1. Run `/prime` in Copilot
2. Copilot will:
   - Display the project structure
   - Read key documentation files
   - Build a comprehensive understanding of the project

This allows Copilot to provide more accurate assistance with your project.




