# Vocal Bridge Plugin Marketplace

Official Claude Code plugin marketplace for Vocal Bridge.

## Installation

Add this marketplace to Claude Code:

```
/plugin marketplace add vocalbridgeai/vocal-bridge-marketplace
```

## Available Plugins

### vocal-bridge

Manage Vocal Bridge voice agents from Claude Code.

**Features:**
- Create and deploy new voice agents (paid subscribers)
- View call logs and transcripts
- Update agent prompts and greetings
- Configure session limits (max call duration, history size)
- Place outbound calls with **Vapi/Retell-style per-call dynamic variables** (`{{var}}` interpolation)
- **Inject `client_actions` events mid-call** from your backend (outbound + inbound + web)
- Deliver `agent_to_app` events to a **signed HTTPS webhook** for phone-only deployments
- Stream real-time debug events
- Check call statistics
- Evaluate call recordings with a multimodal LLM (Pilot only)
- Authenticate with your Vocal Bridge account

**Install:**
```
/plugin install vocal-bridge@vocal-bridge
```

**Get started:**
```
/vocal-bridge:login vb_your_api_key
/vocal-bridge:help
```

## Links

- [Vocal Bridge](https://vocalbridgeai.com) - Deploy voice agents in minutes
- [Plugin Repository](https://github.com/vocalbridgeai/vocal-bridge-claude-plugin)
- [CLI on PyPI](https://pypi.org/project/vocal-bridge/)

## License

Apache-2.0
