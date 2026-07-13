# Black Duck LLM plugins

A collection of plugins, skills, and tools for AI coding agents to connect to Black Duck Software products.

## Available Plugins

| Plugin                                                                                                   | Description                                                         |
|----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **[bdsca](https://github.com/blackducksoftware/sca-llm-plugin/tree/main/claude-plugin-bdsca/README.md)** | Black Duck Software Composition Analysis plugin with MCP and skills |

See each plugin's README for detailed features, usage, and examples.


## Installation

### Claude Code

#### Plugins

1. Add the marketplace:
```bash
claude plugin marketplace add blackducksoftware/llm-plugins
```

2. Install a plugin:
```bash
claude plugin install blackduck-bdsca
```

3. Verify:
```bash
claude plugin list
```

## Update

### Claude Code
In Claude code cli:
```bash
/plugin marketplace update blackducksoftware/llm-plugins
/reload-plugins
```
