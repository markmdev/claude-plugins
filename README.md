# Claude Code Plugins

Plugin marketplace by [@markmdev](https://github.com/markmdev).

## Install

```bash
/plugin marketplace add markmdev/claude-plugins
```

## Available Plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| **reflex** | Context router — auto-injects relevant docs and skills before Claude responds | `/plugin install reflex@markmdev` |

## Reflex

Reflex watches your conversation and uses a fast model to decide which docs and skills your agent needs before responding. Zero configuration — auto-discovers everything from frontmatter.

**Requires:** the `reflex` binary installed separately:
```bash
curl -sL https://raw.githubusercontent.com/markmdev/reflex/master/install.sh | sh
```
