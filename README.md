# SingularityApp MCP

Connect your SingularityApp account to Cursor through the Model Context Protocol (MCP).

With this plugin, Cursor can help you work with tasks, projects, checklists, habits, Kanban boards, and time tracking in your SingularityApp account.

## Requirements

- A SingularityApp account
- Cursor with MCP support
- Access to the SingularityApp MCP service

## Install

1. Open **Cursor → Customize → Plugins**.
2. Find **SingularityApp** and click **Install**.
3. Open Cursor Agent and start using a SingularityApp action.
4. When Cursor requests access, sign in to SingularityApp and approve the connection.

No API key is required. Authentication is handled through OAuth.

## What the plugin can do

Depending on the permissions you approve, Cursor can:

- view, create, edit, complete, and archive tasks and checklist items;
- work with projects, sections, and tags;
- view habits and log daily completion;
- view Kanban boards and move cards between columns;
- view and log time-tracking data;
- access the account metadata required to operate the connection.

The plugin does not access your local files, Cursor chat history, prompts, or conversation memory.

## MCP endpoint

The plugin connects to the hosted SingularityApp MCP server:

`https://mcp.singularity-app.com/mcp`

## Permissions and revoking access

You choose whether to approve access when connecting the plugin.

You can view and revoke Cursor access at any time in your [SingularityApp connected apps settings](https://me.singularity-app.com/oauth-tokens).

## Privacy and terms

- Privacy Policy: https://singularity-app.com/policy/
- Terms of Service: https://singularity-app.com/terms_of_service/

## Support

For support, contact: info@singularity-app.com

When reporting an issue, please include:
- Cursor version;
- a short description of what happened;
- the action you were trying to perform;
- an error message or screenshot, without tokens or personal data.

## Development

This repository contains the Cursor Plugin manifest and MCP configuration. The MCP backend is hosted by SingularityApp; it is not bundled in this repository.

## License

[MIT](./LICENCE)
