# CloudPloy/ChatGPT-plugin

Connect AWS, Google Cloud, a VPS, or another cloud account, and put Cloudflare in front of it, from ChatGPT or Codex. The agent talks to `https://app.cloudploy.com/mcp`. This repo is the install package. It doesn't run a second server.

Claude uses [CloudPloy/Claude-plugin](https://github.com/CloudPloyHQ/Claude-plugin).

## Package

```bash
zip -r dist/ChatGPT-plugin.zip \
  plugin.json mcp.json .mcp.json LICENSE README.md \
  skills assets .codex-plugin
```

Upload that zip in the OpenAI plugin dashboard. Reviewer login stays in the dashboard, not in the zip.

The directory name is `CloudPloy/ChatGPT-plugin`.
