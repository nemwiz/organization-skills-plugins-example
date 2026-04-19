# Example repository for plugins across the organization

This repository contains custom Claude skills for different departments at a dummy organization.

## Installation

For Cowork these are enabled by default.

To use these plugins with Claude Code:

1. Run `/plugin`
2. Navigate to `Marketplaces`
3. Select `+Add Marketplace`
4. Type `freeday-ai/freeday-skills`
5. Run `/reload-plugins`

## Plugin Structure

Each plugin follows this structure. [See the docs for more fields](https://code.claude.com/docs/en/plugin-marketplaces#plugin-entries)
```
department-name/
└── .claude-plugin/         
    ├── plugin.json
└── skills/             
    └── skill-1/             
        ├── SKILL.md
        └── ...
```

## Contributing

To add new skills:

1. Create a new `.md` file in the appropriate `skills/` directory
2. Follow the existing skill format and structure
