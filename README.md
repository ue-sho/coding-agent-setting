# Coding Agent Settings

This repository contains common settings for coding agents.

## Setup

To use these settings, create a symbolic link from the `claude-code` directory in this repository to `~/.claude`.

### Claude Code

This single command will link the entire configuration directory. **Note:** This will replace your existing `~/.claude` directory if you have one.

```bash
# Create a symbolic link to the claude-code directory
ln -s "$(pwd)/claude-code" ~/.claude
```

### Gemini CLI

This command will link the `gemini-cli` directory to `~/.gemini`.

```bash
# Create a symbolic link to the gemini-cli directory
ln -s "$(pwd)/gemini-cli" ~/.gemini
```

Now, any changes made within the `coding-agent-setting/claude-code` or `coding-agent-setting/gemini-cli` directories will automatically be reflected for the respective agents.
