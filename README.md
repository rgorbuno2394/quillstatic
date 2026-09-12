# quillstatic

Static blog generator: markdown in, tidy HTML out

## Usage

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Getting started

```bash
pip install -r requirements.txt
```

## Features

- Single template, plain str.format, no Jinja
- Markdown posts with fenced code and tables
- RSS feed generation
- Index page with post list by date

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── faq.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── build.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## Why

Needed this for myself; figured others might too.

## License

MIT - see [LICENSE](LICENSE).
