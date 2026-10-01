# code-review

Review a pull request or local diff for correctness, security, and test gaps, then report ranked findings with file and line references.

## Install

```sh
npx skills add jongio/skills --skill code-review
```

Reload your agent skills, then invoke `/code-review`.

## Development

```sh
npm ci --ignore-scripts
npm test
npm run eval:lint
```

The deterministic test checks the portable skill shape. The Vally capability eval verifies that
the agent follows the workflow.

## License

MIT. See [LICENSE](LICENSE).
