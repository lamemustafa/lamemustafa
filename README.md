# Tapish Khandelwal

I fix remote MCP servers whose OAuth sign-in fails in Claude, and I build SSO and SCIM for B2B SaaS.

## What I fix

- **MCP connector OAuth.** Your server's sign-in fails in claude.ai, Claude Desktop or Claude Code. I find the step that breaks and fix it on your side.
- **SSO and SCIM.** SAML or OIDC sign-in, and SCIM provisioning with Okta and Microsoft Entra ID.

## Proof

- [ComplyEaze Bridge](https://github.com/ComplyEaze/bridge): my Rust/Tauri MCP server that reads and writes TallyPrime, listed in the official MCP Registry as `io.github.ComplyEaze/bridge-tally`.
- [My answers on connector issues](https://github.com/anthropics/claude-ai-mcp/issues?q=commenter%3Alamemustafa) in anthropics/claude-ai-mcp, including [#431](https://github.com/anthropics/claude-ai-mcp/issues/431), closed by Anthropic staff crediting my check.
- [claude-connector-fixes](https://github.com/lamemustafa/claude-connector-fixes): tested fixes, each marked as seen working or taken from a public issue.
- [entra-scim-notes](https://github.com/lamemustafa/entra-scim-notes): what Microsoft Entra ID Free actually sends to a custom SCIM endpoint, captured 21 Oct 2026. It disables a user by sending `active` as the string `"False"`.
- G2, 2019 to 2023: backend engineer on the Okta, Azure AD, Microsoft 365 and Duo integrations and a QuickBooks OAuth 2.0 flow.

## Hire me

Email **tapish@complyeaze.com** with the exact error text.

- Free 20-minute triage. If the fault is on Claude's side, I tell you and you pay nothing.
- MCP OAuth fix: $500 fixed, delivered in 3 working days, paid upfront. Prefer escrow? Book the same fix through [my Upwork offer](https://www.upwork.com/services/product/2109555434115908754).
- SSO/SCIM: fixed price, quoted after triage.

---
I also build [ComplyEaze](https://complyeaze.com), open-source compliance software for Indian CA firms ([Bridge](https://github.com/ComplyEaze/bridge), [Pack](https://github.com/ComplyEaze/pack)).
