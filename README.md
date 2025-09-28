# README
## Agents
This is an example agent configuration file for the [Continue](https://docs.continue.dev/#ide-extensions) platform.

## Example Agent Configuration

The `Local-host-agent.yaml` file defines a custom AI agent that can be used within the Continue environment. This agent specifies which AI models and MCP servers are available to it, along with its roles and capabilities.

## Models

The `models` section of the configuration file specifies the AI models that this agent can use. In this example, the `Local Copilot (La cabra)` model is configured using the Ollama provider with the `qwen2.5-coder:7b` model name.
This configs files can also be used to pre-prompt other agents like [Firebase](https://firebase.google.com/?hl=es-419), or Copilot agents.

## MCP Servers

The `mcpServers` section of the configuration file specifies the MCP servers that are available to this agent. In this example, the `anthropic/memory-mcp` server is configured for use by the agent.

This README provides a brief overview of the `Local-host-agent.yaml` file and its components."

## Rules
The rules written in the rules folder are prompts that can be aplied to agents to behave in different and more precise ways. They are used to make them do things in certain ways like naming_convention, or OS specific command suggestions. 
These rules are in contant development, refactoring and updating with the more usage is given, and the more requirements or difficulties are faced.
