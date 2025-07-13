# Coding Agent Settings

This repository contains common settings for coding agents.

## Setup

To use these settings, create a symbolic link from the `claude-code` directory in this repository to `~/.claude`.

### Claude Code

This single command will link the entire configuration directory. **Note:** This will replace your existing `~/.claude` directory if you have one.

```bash
# Remove the existing .claude directory (use with caution)
rm -rf ~/.claude

# Create a symbolic link to the claude-code directory
ln -s "$(pwd)/claude-code" ~/.claude
```

Now, any changes made within the `coding-agent-setting/claude-code` directory will automatically be reflected for the Claude agent.
