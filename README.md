# Diataxis Writing Skill

A comprehensive skill for creating high-quality documentation using the Diataxis framework.

![GitHub Release](https://img.shields.io/github/v/release/amumulam/diataxis-writing)
![ClawHub](https://img.shields.io/badge/ClawHub-diataxis--writing-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Overview

This skill provides complete guidance for creating documentation based on the [Diataxis framework](https://diataxis.fr), including:

- **Four documentation types**: Tutorial, How-to Guide, Reference, Explanation
- **Decision tools**: Diataxis Compass for type selection
- **Templates**: 8 scenario-based templates
- **Checklists**: Quality checklists for each type
- **Diagnosis tools**: Automatic document type detection

## Features

### 1. Type Diagnosis

Automatically identifies the appropriate documentation type using the Diataxis Compass.

### 2. Templates

8 scenario-based templates:
- Tutorial
- How-to Guide
- Reference
- Explanation
- Troubleshooting
- Best Practices
- Learning Notes
- Exploratory Sharing

### 3. Checklists

Quality checklists for each documentation type to ensure consistency and completeness.

### 4. Output Management

Support for multiple output methods:
- Chat response
- Feishu documents (via MCP)
- Local Markdown files
- GitHub repositories

## Installation

### Option 1: Via ClawHub CLI (Recommended)

One-line installation with automatic updates:

```bash
clawhub install diataxis-writing
```

### Option 2: From GitHub Release

Download the packaged skill file:

```bash
# Download .skill file
curl -L https://github.com/amumulam/diataxis-writing/releases/download/v1.0.0/diataxis-writing.skill \
  -o /root/.openclaw/workspace/skills/diataxis-writing.skill
```

### Option 3: Manual Installation

Clone and copy to workspace:

```bash
git clone https://github.com/amumulam/diataxis-writing.git
cd diataxis-writing
cp -r . /root/.openclaw/workspace/skills/
```

### Verify Installation

```bash
ls /root/.openclaw/workspace/skills/diataxis-writing/SKILL.md
# Should exist
```

## Quick Start

1. **Install**: `clawhub install diataxis-writing`
2. **Trigger**: Mention "write a how-to guide" or "documentation type"
3. **Follow**: The skill will guide you through Diataxis framework

## Usage

The skill automatically triggers when you mention:

- Documentation creation or writing tasks
- Diataxis framework
- Document type selection
- Troubleshooting records
- Experience summaries
- Learning notes
- Best practices
- Technical sharing

### Example Triggers

- "Help me write a tutorial"
- "What type of documentation should this be?"
- "Create a how-to guide for..."
- "Check my documentation structure"

## Project Structure

```
diataxis-writing/
├── SKILL.md              # Core skill guide
├── CHANGELOG.md          # Version history
├── .gitignore           # Git ignore rules
│
├── checklist/           # Quality checklists (4 files)
├── references/          # Theoretical references (7 files)
├── templates/           # Documentation templates (8 files)
└── scripts/             # Helper scripts (2 files)
```

## Resources

- [Diataxis Official Documentation](https://diataxis.fr)
- [Diataxis GitHub Repository](https://github.com/evildmp/diataxis-documentation-framework)
- [OpenClaw Documentation](https://docs.openclaw.ai)
- [ClawHub Skill Page](https://clawhub.ai/skills/diataxis-writing)

## License

This skill is based on the official Diataxis framework from https://diataxis.fr.

## Acknowledgments

- **Diataxis Framework**: [Daniele Procida](https://vurt.eu) and contributors
- **Official Documentation**: https://diataxis.fr
- **Skill Creator Pattern**: Based on Anthropic's skill-creator guidelines
