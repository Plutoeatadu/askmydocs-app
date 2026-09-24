# askmydocs-app

Tiny retrieval pipeline: TF-IDF chunks + pluggable LLM step

Started as a weekend hack, grew on me.

## Getting started

```bash
pip install -r requirements.txt
```

## Highlights

- Chunk markdown with overlap, keep source paths
- Prints sources with scores for transparency
- TF-IDF retrieval: zero external services needed
- Swap in any LLM for the answer step

## Usage

```bash
python rag.py ./notes "how do I rotate logs?"
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── data/
│   └── sample.md
├── docs/
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── rag.py
└── requirements.txt
```

## License

MIT licensed, see LICENSE.
