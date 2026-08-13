# agent-skills

Astro Foundry's plugin marketplace for Claude Code.

## Use

```bash
claude plugin marketplace add astrofoundry/agent-skills
```

The marketplace registers as `astrofoundry`. Install plugins with `claude plugin install <plugin>@astrofoundry`.

## Plugins

| Plugin | Description | Repository |
|---|---|---|
| [talk-normal](https://github.com/astrofoundry/talk-normal) | Plain, unambiguous, action-first output for coding agents. | astrofoundry/talk-normal |

Each plugin lives in its own repository and also installs directly (`claude plugin marketplace add astrofoundry/<plugin>`) and in other harnesses — see each plugin's INSTALL.md.

## License

MIT.
