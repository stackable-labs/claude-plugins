# Stackable Claude Code Plugins

Claude Code plugins for [Stackable Labs](https://stackablelabs.com/) extension development.

## Available Plugins

### stackable-extension-dev

SDK skills, validation tools, and live platform API access for AI-assisted extension development for enhanced Zendesk Messenger.

**Install:**

```bash
# Add this marketplace (one-time)
/plugin marketplace add stackable-labs/claude-plugins

# Install the plugin
/plugin install stackable-extension-dev@stackable-claude-plugins
```

**What's included:**

- **Agent Skills** — SDK reference and guided workflows (add capabilities, add components, add surfaces, validate extensions, and more)
- **MCP Server** — Live platform API access via HTTP transport with OAuth authentication (list apps, list/get extensions, validate manifests, etc.)

Skills and MCP config are bundled in the plugin and auto-update when new versions are published.

## License

[MIT](https://opensource.org/licenses/MIT)
