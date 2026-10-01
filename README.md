# Wanchain Agent Skills

Agent Skills for Wanchain, the cross-chain blockchain, built on the OrbitWan MCP server. Each folder under `skills/` is one skill in the open Agent Skills format: a `SKILL.md` with a name and a description, which Claude Code, Codex, Cursor and other compatible agents load.

## Skills

| Skill | Version | What it does |
|---|---|---|
| [wanchain-bridge-to-earn](skills/wanchain-bridge-to-earn/SKILL.md) | 0.7.1 | Earns rewards from Wanchain's Bridge to Earn program, usually paid in xWAN, by completing posted cross-chain transfer tasks. |
| [wanchain-xwan-express](skills/wanchain-xwan-express/SKILL.md) | 0.2.2 | Sells xWAN, Wanchain's escrowed WAN, for WAN at once through xWAN Express, a fixed-rate desk that OrbitWan runs. |

## Install

With the open skills CLI:

    npx skills add OrbitWan/wanchain-agent-skills

Or copy a skill's folder into your agent's skills directory.

## Requirements

The skills call the OrbitWan MCP server at https://mcp.orbitwan.io/mcp. Add it to your agent as a remote MCP server. Each skill's `compatibility` field lists what else it needs.

## Links

- Explorer: https://orbitwan.io
- MCP server: https://mcp.orbitwan.io/mcp

## License

MIT. See [LICENSE](LICENSE).
