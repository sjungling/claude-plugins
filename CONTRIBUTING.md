# Contributing to Claude Code Plugins

Thank you for your interest in contributing to this Claude Code plugin marketplace!

## How to Contribute

### Adding a New Plugin

1. **Fork this repository**

2. **Create a new plugin directory** under `plugins/`:
   ```bash
   mkdir plugins/your-plugin-name
   ```

3. **Create the required plugin files**:
   - `plugin.json` - Plugin metadata
   - `README.md` - Plugin documentation
   - Implementation files (e.g., `index.js`, etc.)

4. **Follow the plugin structure**:
   ```
   plugins/your-plugin-name/
   ├── plugin.json
   ├── README.md
   └── [implementation files]
   ```

5. **Update marketplace.json** to include your plugin:
   ```json
   {
     "id": "your-plugin-name",
     "path": "plugins/your-plugin-name",
     "name": "Your Plugin Display Name",
     "description": "Brief description",
     "version": "1.0.0"
   }
   ```

6. **Submit a Pull Request** with:
   - Clear description of what your plugin does
   - Any dependencies or requirements
   - Usage examples

### Plugin Requirements

- **plugin.json**: Must include id, name, description, version, and author
- **README.md**: Must document purpose, installation, usage, and configuration
- **Code Quality**: Follow JavaScript/TypeScript best practices
- **Testing**: Include tests if applicable
- **License**: Must be compatible with MIT license

### Plugin Categories

Consider categorizing your plugin:
- `utility` - General utility tools
- `integration` - Third-party service integrations
- `development` - Development tools and helpers
- `productivity` - Productivity enhancements
- `data` - Data processing and manipulation

### Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Help maintain a welcoming community

### Questions?

Open an issue for questions or clarifications about contributing.
