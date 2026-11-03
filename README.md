# Black Duck LLM plugins

A collection of plugins, skills, and tools for AI coding agents to connect to Black Duck Software products.

## Available Plugins

| Plugin                                                                                                   | Description                                                         |
|----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **[bdsca](https://github.com/blackducksoftware/sca-llm-plugins/tree/main/claude-plugin-bdsca/README.md)** | Black Duck Software Composition Analysis plugin with MCP and skills |
| **[bdba](https://github.com/blackducksoftware/sca-llm-plugins/tree/main/claude-plugin-bdba/README.md)** | Black Duck Binary Analysis plugin with MCP and skills |

See each plugin's README for detailed features, usage, and examples.


## Installation

### Claude Code

#### Plugins

1. Start Claude Code:
```bash
claude
```

2. Add the marketplace:
```bash
/plugin marketplace add blackducksoftware/llm-plugins
```

3. Install a plugin:
```bash
# install the plugin for your product, or both
/plugin install blackduck-bdsca@blackduck-llm-plugins
/plugin install blackduck-bdba@blackduck-llm-plugins
/reload-plugins
```

4. Verify:
```bash
/plugin list
/mcp list
```

## Update

### Claude Code
In Claude code cli:
```bash
/plugin marketplace update blackducksoftware/llm-plugins
/reload-plugins
```

## Data sent to your LLM provider

Tool and Resource results go to the LLM that Claude Code uses. These may hold Vulnerability
findings, Project, Version and Component names, Policy settings, and Scan results. The API
tokens never go to the LLM.

Black Duck does not control how your LLM provider stores or uses this data, or whether the
provider trains models on it. Before you use the plugins with sensitive or regulated
findings, read your provider's terms and data processing agreement, and use its zero data
retention or enterprise options where you need them.

## Support

- [Black Duck Website](https://www.blackduck.com/)
- [Community Portal](https://community.blackduck.com)
- [Email](mailto:support@blackduck.com)
