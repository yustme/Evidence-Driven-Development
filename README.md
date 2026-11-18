# Evidence-Driven Development

A Codex skill for scoping a useful first version, implementing software changes, and verifying them through the user's normal workflow. It also covers parallel Git work, access boundaries, regression coverage, and release evidence.

## Install

Clone the skill into your personal Codex skills directory. If you already have a copy there, update that copy from the repository.

```sh
mkdir -p "$HOME/.codex/skills"
git clone https://github.com/yustme/evidence-driven-development.git "$HOME/.codex/skills/evidence-driven-development"
```

Invoke it explicitly in Codex, for example:

> Use $evidence-driven-development to scope and implement an orders CSV export. Verify that staff can download the right rows through the normal workflow.

## License

[MIT](LICENSE)
