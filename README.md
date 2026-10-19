# Iridium for Claude

The Iridium plugin marketplace for Claude. It lists one plugin, **Iridium Memory**, which connects Claude to the Iridium agents assigned to you and to the Memory and Knowledge each agent is authorised to use. Where your organisation has turned on Tools, your personal agent can also read your connected Gmail, Google Calendar, Google Drive and Slack, and make changes there that you approve in Iridium.

## Install

1. In Claude, open **Customize** → **Plugins**.
2. Choose **Add** → **Add marketplace**, enter `Jdashford/iridium-marketplace`, and add it.
3. Install **Iridium Memory**.
4. Open its connector, choose **Connect**, and sign in with your Iridium account.
5. Start a new conversation once the Iridium tools have loaded.

In Claude Code you can also run:

```
/plugin marketplace add Jdashford/iridium-marketplace
/plugin install iridium-memory@iridium
```

You need an Iridium account with at least one assigned agent.

## About the plugin

The plugin's files, what it sends and where, and its releases are in [Jdashford/iridium-claude-plugin](https://github.com/Jdashford/iridium-claude-plugin/tree/main/plugins/iridium-memory). An installable ZIP is also available:
[iridium-memory.zip](https://github.com/Jdashford/iridium-claude-plugin/releases/latest/download/iridium-memory.zip).

- Privacy policy: <https://iridiumai.co/privacy-policy>
- Terms of service: <https://iridiumai.co/terms-of-service>
- Support: <https://iridiumai.co/contact>
