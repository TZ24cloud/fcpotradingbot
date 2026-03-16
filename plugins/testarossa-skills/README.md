# Testarossa Skills Plugin

AI companion skills for Thaqif's FCPO trading assistant.

## Active Skills

| Skill | Trigger | Purpose |
|---|---|---|
| `save-memory` | "save", "save memory", "save progress" | Saves important context to memory files |

## Adding New Skills

1. Create a new folder: `skills/[skill-name]/`
2. Create `SKILL.md` inside with YAML frontmatter + protocol
3. Reference `skill-format.md` for the standard structure
4. Done — skill auto-activates based on description field

## Plugin Info
- **Name**: testarossa-skills
- **Version**: 1.0.0
- **Author**: Thaqif
- **Purpose**: FCPO trading support and memory management
