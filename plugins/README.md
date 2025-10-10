# Plugins Directory

This directory contains Claude Code plugin definitions. Each plugin should be in its own subdirectory with the following structure:

```
plugins/
  └── plugin-name/
      ├── plugin.json       # Plugin metadata and configuration
      ├── README.md         # Plugin documentation
      └── [additional files] # Any additional plugin files
```

## Plugin Definition Format

Each plugin must have a `plugin.json` file with the following structure:

```json
{
  "id": "unique-plugin-id",
  "name": "Plugin Display Name",
  "description": "Brief description of what the plugin does",
  "version": "1.0.0",
  "author": "Author Name",
  "category": "category-name",
  "tags": ["tag1", "tag2"],
  "files": {
    "main": "path/to/main/file"
  }
}
```

## Adding a New Plugin

1. Create a new directory under `plugins/` with your plugin name
2. Add a `plugin.json` file with the plugin metadata
3. Add a `README.md` file with plugin documentation
4. Include any additional files needed for your plugin
5. Update the main `marketplace.json` file to include your plugin
