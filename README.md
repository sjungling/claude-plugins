# Claude Code Plugins

A personal marketplace for Claude Code plugins.

## About

This repository serves as a Claude Code plugin marketplace, providing a collection of custom plugins to extend Claude Code functionality.

## Structure

```
claude-plugins/
├── marketplace.json    # Marketplace metadata and plugin registry
├── plugins/           # Plugin definitions
│   └── [plugin-name]/ # Individual plugin directories
└── README.md          # This file
```

## Available Plugins

Currently, this marketplace is being set up. Plugins will be added soon.

## Using This Marketplace

To use plugins from this marketplace in Claude Code:

1. Add this repository URL to your Claude Code marketplace sources
2. Browse and install plugins from the Claude Code interface
3. Configure installed plugins according to their documentation

## Adding Plugins

To add a new plugin to this marketplace:

1. Create a new directory under `plugins/` with your plugin name
2. Add a `plugin.json` file with plugin metadata
3. Include a `README.md` with plugin documentation
4. Update `marketplace.json` to register your plugin
5. Submit a pull request

See the [plugins/README.md](plugins/README.md) for detailed information on plugin structure and requirements.

## License

MIT - See [LICENSE](LICENSE) file for details.
