# llm-meter-kit

Estimate LLM cost of a file before you send it

Built for my own use; public in case it helps someone.

## Examples

```bash
python cost.py prompt.txt --model gpt-4o-mini --expect-out 500
```

## Install

```bash
# stdlib only
```

## Highlights

- Per-model pricing table in JSON
- Heuristic token estimate (~4 chars/token)
- Reports input/output tokens and USD estimate
- Zero dependencies

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   └── faq.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
├── cost.py
└── pricing.json
```

## FAQ

**Is this production ready?**  
It works for my use case; review the code before relying on it.

**Why no framework?**  
The stdlib covers what this project needs.

## License

MIT. Do whatever you want.
