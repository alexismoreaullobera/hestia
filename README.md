# Hestia

Hestia is a personal AI assistant made of **rooms**: each room is an autonomous MCP server (its tools, its data, its MCP Apps views), useful without AI and published in its own repository. The first one is [hestia-room-finance](https://github.com/alexismoreaullobera/hestia-room-finance).

This is the **platform** repository: what plugs the rooms together.

| Folder | What | Status |
|---|---|---|
| `shell/` | The Angular app opened every day: an MCP Apps host that finds the views of the rooms and shows them | In progress (S1: manual navigation, no agent) |

The agent, its thin .NET backend and the infrastructure come later.

## Shell

Requires Node (version in `shell/.nvmrc`) and a room running locally (see the room's README).

```bash
cd shell
npm ci
npm start
```
