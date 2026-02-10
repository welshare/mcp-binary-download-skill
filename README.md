# Welshare MCP Binary Downloads Skill

A Claude skill that instructs AI agents how to properly fetch protected binary user resources

## What are Skills?

Skills are folders of instructions, scripts, and resources that Claude loads dynamically to improve performance on specialized tasks. Rather than relying on Claude's general knowledge, skills provide domain-specific instructions and tools that make Claude consistently better at particular use cases.

Learn more: [Official Skills Repository](https://github.com/anthropics/skills/blob/main/README.md)

## Network Access

This skill requires whitelisted network access to:

- `wallet.welshare.app` (the server that passes through)
- `staging.wallet.welshare.app` (LOINC search)

## Installation

### Quick Install

1. **Download the latest release**: [fhir-questionnaire.skill](https://github.com/mcp-binary-download-skill/releases/latest/download/fhir-questionnaire.skill)
2. Install it in Claude Desktop or Claude Code

![Claude Skills](docs/claude.png)

### Manual Download

Visit the [Releases page](https://github.com/welshare/mcp-binary-download-skill/releases) to download a specific version.

## Development & Distribution

### For Developers

To package and distribute this skill:

```bash
# Create a distributable .skill package
make package

# Test the package contents
make test-package

# Clean build artifacts
make clean
```

**Documentation:**

- [SKILL.md](welshare-download-binary-resources/SKILL.md) - Skills are humanly readable
- [PACKAGING.md](PACKAGING.md) - Detailed packaging procedures
- [RELEASE.md](RELEASE.md) - How to create and publish releases

## Contents

- **SKILL.md** - Core instructions and workflows
