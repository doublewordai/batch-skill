# Doubleword Batch API Skill

A skill for AI coding agents that teaches them how to work with the Doubleword Batch API for high-throughput, low-cost LLM inference.

## What is a Skill?

Skills are reusable capabilities for AI agents. They provide procedural knowledge that helps agents accomplish specific tasks more effectively.

This skill covers:

- Submitting batch jobs via the Doubleword API
- Monitoring batch status and downloading results
- Using the autobatcher Python client
- Tool calling and structured outputs
- Available models and pricing

## Installation

```bash tabs=install name=Skills sync=method
npx skills add https://github.com/doublewordai/batch-skill
```

```bash tabs=install name=Git sync=method
git clone https://github.com/doublewordai/batch-skill
```

## Supported Agents

This skill works with AI coding agents including:

- Claude Code
- Cursor
- Windsurf
- Codex
- Other agents that support the skills format

## Using the Skill

Once installed, you can ask your AI agent questions like:

- "How do I submit a batch job to Doubleword?"
- "Show me how to check batch status"
- "Help me download partial results"
- "What models are available and what do they cost?"

## Updating

```bash tabs=update name=Skills sync=method
npx skills update doubleword-batch
```

```bash tabs=update name=Git sync=method
cd ~/.claude/skills/batch-skill && git pull
```

## Links

- [GitHub Repository](https://github.com/doublewordai/batch-skill)
- [Doubleword Batch API Docs](https://docs.doubleword.ai/batches)
- [Doubleword Console](https://app.doubleword.ai)
- [Skills CLI](https://github.com/skills-sh/skills)

## License

MIT
