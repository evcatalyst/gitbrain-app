# GitBrain App (`app.gitbrain.com`)

Cloudflare Workers + D1 app for:

- Signup / login
- MCP agent-token mint & authorize
- Dashboard (sessions / capsules)
- Wiki-style memory viewer

**Public host:** `app.gitbrain.com`  
**MCP door:** `https://mcp.gitbrain.com` (do not overload that Worker)

Scaffold landing — cloud agent / implementers fill in Workers code.

## Deploy notes (Platform Infra)

- Suggested Worker name: `gitbrain-app-m0`
- Attach custom domain `app.gitbrain.com`
- D1 for users, sessions, token hashes
- Secrets: session signing key, token pepper, MCP base URL

## License

Apache-2.0
