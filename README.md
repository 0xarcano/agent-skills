# Agent Skills

A collection of skills for AI coding agents. Skills are packaged instructions and scripts that extend agent capabilities.

Skills follow the [Agent Skills](https://agentskills.io/) format.

## Available Skills

### yellow-best-practices

Yellow Network and Nitrolite (ERC-7824) development best practices for building state channel applications. Contains guidelines for building high-performance decentralized applications with near-instant finality.

Use when:

- Building applications with Yellow Network SDK
- Implementing state channels with Nitrolite
- Working with ClearNode connections and authentication
- Managing off-chain transactions and balances
- Creating and closing application sessions

Categories covered:

- ClearNode Connection (Critical)
- Authentication Flow (Critical)
- Application Sessions (High)
- State Management (High)
- Balance Monitoring (Medium)
- Security Best Practices (Critical)
- Error Handling (Medium)

## Installation

```shell
npx skills add your-org/agent-skills
```

## Usage

Skills are automatically available once installed. The agent will use them when relevant tasks are detected.

Examples:

```
Help me connect to a ClearNode
```

```
Create an application session for a payment app
```

```
How do I properly close a state channel?
```

## Skill Structure

Each skill contains:

- `SKILL.md` - Instructions for the agent
- `rules/` - Categorized best practice rules
- `references/` - Supporting documentation (optional)

## Documentation Sources

- [Yellow Network Documentation](https://docs.yellow.org/)
- [ERC-7824 Documentation](https://erc7824.org/)
- [Nitrolite SDK](https://www.npmjs.com/package/@erc7824/nitrolite)

## License

MIT
